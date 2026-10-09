# Fields

[apps.json](apps.json) has `site`, `license`, `version` and `apps`, an array with one object per app. [apps.csv](apps.csv) has the same fields as columns, in this order; arrays are joined with semicolons.

| Field | Type | Meaning |
|---|---|---|
| `name` | string | App name as shown on the site. |
| `package` | string | Android package name. |
| `page` | string (URL) | The app’s page on h5.2113.net, with the full check results. |
| `category` | string | Category on the site. |
| `version` | string | versionName of the hosted APK. |
| `versionCode` | integer | versionCode of the hosted APK. |
| `released` | date (YYYY-MM-DD) | When the repository or GitHub release published this version. |
| `size` | integer (bytes) | Size of the APK file. |
| `sha256` | string (hex) | SHA-256 of the APK file. |
| `signers` | array of strings (hex) | SHA-256 fingerprints of the signing certificates. |
| `signedBy` | "developer" or "fdroid" | Who signed the file: the developer, or F-Droid with its own key. |
| `signatureSchemes` | array of "v1", "v2", "v3" | APK signature schemes present in the file. |
| `source` | "izzy", "fdroid" or "github" | Where the file comes from: IzzyOnDroid, F-Droid’s main repository or the project’s GitHub releases. |
| `sourceRelease` | string (URL) | The GitHub release the file was taken from. Only present when `source` is "github". |
| `sourceCode` | string (URL) or null | Source code repository; null when the listing doesn’t give one. |
| `license` | string (SPDX) or null | The app’s licence; null when the listing doesn’t give one. |
| `minSdk` | integer | Minimum API level declared in the APK’s manifest. When an app needs a higher level in practice, its page on the site says so. |
| `minAndroid` | string | `minSdk` as an Android version. |
| `targetSdk` | integer | Target API level. |
| `abis` | array of strings | CPU types the APK has native code for. Empty: no native code, runs on any CPU. |
| `permissions` | integer | Number of permissions declared in the manifest. |
| `trackers` | array of strings | Tracker libraries, by Exodus Privacy signature, whose code is inside the APK. Empty: none found. |
| `antiFeatures` | array of strings | Anti-feature labels given by F-Droid or IzzyOnDroid. |
| `olderVersions` | array of objects | Older releases we also host, each with version, versionCode, released, size and sha256. In the CSV: version names only. |

How the values are measured: https://h5.2113.net/how-we-check.html

The frozen snapshots in [reports/](reports/) are the data behind our [open-source APK report](https://h5.2113.net/reports/open-source-apk-report-2026.html). They add, per app, the full permission list, the permissions that need approval, tracker categories and the measurement time; the report page describes them.
