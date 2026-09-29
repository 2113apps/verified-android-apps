# How to verify an APK

Every APK hosted by [2113 Apps](https://h5.2113.net/) is the release its developer published, or F-Droid’s build of it, unchanged. You can check a file you downloaded yourself, in two steps: compare its hash, then check who signed it. The values to compare against are in [apps.json](apps.json) and on each app’s page.

## 1. Compare the file hash

The SHA-256 of your file must equal the `sha256` value for that app and version in `apps.json`, or “File SHA-256” on the app’s page.

| System | Command |
|---|---|
| Linux | `sha256sum app.apk` |
| macOS | `shasum -a 256 app.apk` |
| Windows (PowerShell) | `Get-FileHash app.apk -Algorithm SHA256` |

A match means the file is byte for byte the one we checked. Each version has its own hash, so compare against the version you actually downloaded: `apps.json` lists the current version, and under `olderVersions` any older ones we still host.

## 2. Check who signed it

The signing certificate shows whose release this is, and Android uses it to decide which updates may install over the app.

With the Android SDK build tools:

```
apksigner verify --print-certs app.apk
```

Compare the line `Signer #1 certificate SHA-256 digest` with the `signers` value in `apps.json`, or “Signer SHA-256” on the app’s page. If an app lists more than one fingerprint, its APK carries more than one certificate, for example after a signing-key rotation, and a match with any of them is expected.

With a Java JDK, `keytool -printcert -jarfile app.apk` prints the certificate’s SHA256 fingerprint too, in capitals with colons between the bytes. It only works on APKs that still carry the older v1 signature, which many current apps no longer do, so `apksigner` is the reliable way.

## What the signer tells you

- `"signedBy": "developer"`: signed with the developer’s own key. This is the case for files from IzzyOnDroid and GitHub releases, and for F-Droid apps that F-Droid publishes with the developer’s signature.
- `"signedBy": "fdroid"`: F-Droid built the app from its source code and signed it with F-Droid’s key. Such a copy can’t update the developer’s own builds, from Google Play or GitHub for example, or be updated by them, without uninstalling first.

## What a match does and doesn’t tell you

A matching hash and signer show that your file is identical to the published release we checked, signed with the expected key. They don’t show that the app’s code is safe or free of bugs. The tracker scan only shows which known tracker SDKs are in the code, not what the app sends. The full list of checks is at [How we check](https://h5.2113.net/how-we-check.html).

## Fields in apps.json

| Field | Meaning |
|---|---|
| `name`, `package` | App name and Android package name |
| `page` | The app’s page on 2113 Apps |
| `category` | Category on 2113 Apps |
| `version`, `versionCode`, `released` | The hosted version and when it was released |
| `size`, `sha256` | File size in bytes and SHA-256 of the APK |
| `signers`, `signedBy` | SHA-256 of the signing certificate(s), and whose key it is |
| `source`, `sourceRelease` | Where the file came from: `izzy` (IzzyOnDroid), `fdroid` (F-Droid) or `github`, with the GitHub release for the latter |
| `sourceCode`, `license` | The project’s source code and its licence |
| `minSdk`, `minAndroid`, `targetSdk` | Minimum and target Android API level |
| `abis` | CPU types with native code in the APK; empty means none is needed |
| `permissions` | Number of permissions the APK declares |
| `trackers` | Known tracker SDKs found in the code (Exodus Privacy signatures) |
| `olderVersions` | Older releases we also host, with their hashes |
