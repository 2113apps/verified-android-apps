# Verified Open-Source Android Apps

Open-source Android apps whose APKs are hosted and checked by [2113 Apps](https://h5.2113.net/). Every file is the release the developer published, or F-Droid’s build of it, unchanged. Before it goes up it is matched to the hash in the signed repository index or on the project’s GitHub release, its signing key is checked, and its code is scanned for trackers. Each entry links to the app’s page, which lists the file’s SHA-256, the signer’s fingerprint, the permissions and the CPU types. [How the checks work](https://h5.2113.net/how-we-check.html).

165 apps. This list is generated from the site and updated when the site is. The version, SHA-256 and signer of every file are in [apps.json](apps.json) and [apps.csv](apps.csv) (fields: [SCHEMA.md](SCHEMA.md)), and [VERIFY.md](VERIFY.md) shows how to check an APK you downloaded.

## Contents

- [Data, reports and citation](#data-reports-and-citation)
- [Topics and comparisons](#topics-and-comparisons)
- [Guides](#guides)
- [Root & Mods](#root--mods) (11)
- [Customization](#customization) (8)
- [Network & Privacy](#network--privacy) (22)
- [Media](#media) (34)
- [System Tools](#system-tools) (40)
- [Cloud & Self-Hosted](#cloud--self-hosted) (4)
- [Productivity](#productivity) (11)
- [Reading & Maps](#reading--maps) (4)
- [Games: Strategy Games](#games-strategy-games) (6)
- [Games: Sandbox Games](#games-sandbox-games) (2)
- [Games: Adventure & RPG](#games-adventure--rpg) (5)
- [Games: Simulation Games](#games-simulation-games) (2)
- [Games: Racing Games](#games-racing-games) (2)
- [Games: Educational Games](#games-educational-games) (1)
- [Games: Puzzle & Arcade](#games-puzzle--arcade) (2)
- [Games: PC Emulators](#games-pc-emulators) (1)
- [Games: Minecraft Launchers](#games-minecraft-launchers) (3)
- [Games: Console Emulators](#games-console-emulators) (6)
- [Games: Game Streaming](#games-game-streaming) (1)

## Topics and comparisons

- [Obtainium Alternatives for Android](https://h5.2113.net/topics/app-updaters/): Four open-source alternatives to Obtainium for installing and updating Android apps outside Google Play. Sources, silent installs and tracking flags compared.
- [Heroes 2 & 3, RCT2 and Transport Tycoon on Android](https://h5.2113.net/topics/classic-pc-games-android/): fheroes2, VCMI, OpenRCT2 and OpenTTD rebuild four classic PC strategy games as open source for Android. What each needs from the original game, and how to set it up.
- [Android Customization Apps: Open-Source Picks](https://h5.2113.net/topics/customization/): Six open-source apps to customize Android, from launchers and a desktop-style taskbar to system-wide icon packs and Quick Settings styling. What each needs.
- [Fossify Apps: Simple Mobile Tools Alternatives](https://h5.2113.net/topics/fossify-apps/): The Fossify apps that carry on Simple Mobile Tools, from gallery and dialer to keyboard and launcher. None requests internet access; all ten share one signing key.
- [Android Games With No Ads: 15 Open-Source Picks](https://h5.2113.net/topics/games-without-ads/): Fifteen open-source Android games, from strategy and roguelikes to puzzles, pinball and racing, whose files contain no ad libraries, no billing code and no trackers.
- [LSPosed Modules List: 9 Open-Source Picks](https://h5.2113.net/topics/lsposed-modules/): Nine open-source LSPosed and Xposed modules, from fixing old app installs to icon packs and freezing background apps. Xposed API confirmed in every APK, no trackers.
- [Minecraft Java Launchers for Android](https://h5.2113.net/topics/minecraft-java-launchers/): Three open-source launchers that run Minecraft Java Edition on Android, Amethyst, Zalith Launcher 2 and Fold Craft Launcher, compared on versions, mods and devices.
- [NewPipe Alternatives: Open-Source YouTube Apps](https://h5.2113.net/topics/newpipe-alternatives/): NewPipe, PipePipe, LibreTube, FreeTube Android, SkyTube and Tubular compared on features, how they reach YouTube, upkeep and devices. Every APK checked.
- [Open-Source Roguelikes for Android](https://h5.2113.net/topics/open-source-roguelikes/): Shattered Pixel Dungeon, Dungeon Crawl Stone Soup and Brogue CE compared on controls, depth, online features and who makes each Android version. All free, no ads.
- [Open-Source Strategy Games for Android](https://h5.2113.net/topics/open-source-strategy-games/): Mindustry, Unciv and The Battle for Wesnoth compared on pace, online play, data downloads, controllers and Android support. Every APK signature-checked.
- [KernelSU vs APatch vs Magisk Compared](https://h5.2113.net/topics/root-solutions/): KernelSU and APatch root Android from the kernel; Magisk patches the boot image. Kernel support, modules and requirements compared, with APKs checked.
- [Best Shizuku Apps: 16 Open-Source Picks](https://h5.2113.net/topics/shizuku-apps/): Sixteen open-source Android apps that use Shizuku for ADB-level access without root. We confirmed the Shizuku API inside every APK and scanned each for trackers.
- [Termux Plugins: All 7 Add-ons Explained](https://h5.2113.net/topics/termux-plugins/): What each Termux plugin adds, from Termux:API to Termux:GUI, how to set it up, and why plugins must come from the same source as Termux. All seven checked.
- [Open-Source VPN Apps for Android: 7 Compared](https://h5.2113.net/topics/vpn-apps/): WG Tunnel, OpenVPN for Android, OpenConnect, Tailscale, Shadowsocks, NekoBox and Windscribe compared by protocol and what you need to connect. Every APK checked.
- [Open-Source YouTube Music Clients for Android](https://h5.2113.net/topics/youtube-music-clients/): Metrolist, ArchiveTune, Kreate, VIVI Music, Gyawun, SimpMusic, OuterTune and Bloomee compared on sources, accounts, lyrics and devices. Every APK signature-checked.

## Guides

- [Android Developer Verification: Can You Still Sideload?](https://h5.2113.net/guides/android-developer-verification.html): Since 30 September 2026, Android checks apps from 7 app stores in Brazil, Indonesia, Singapore and Thailand. What that means for APKs you download, adb and F-Droid.
- [arm64-v8a vs armeabi-v7a: Which APK Do You Need?](https://h5.2113.net/guides/arm64-vs-armeabi.html): arm64-v8a is for 64-bit ARM phones, armeabi-v7a for 32-bit ARM. How to check which your phone runs, when to take the universal APK, and what happens if you pick wrong.
- [“Built for an Older Version of Android”: What It Means](https://h5.2113.net/guides/built-for-older-android.html): Why Android shows the “built for an older version of Android” warning, why Android 14 and later refuse to install some old apps, and the ways around each.
- [How to Extract boot.img From an OTA or payload.bin](https://h5.2113.net/guides/extract-boot-img.html): Get the stock boot.img or init\_boot.img you need for rooting: which image to use, why the build must match, and how to extract it on the phone or on a computer.
- [Add Your Own Game Files to Android Game Engines](https://h5.2113.net/guides/game-files-for-android-engines.html): Open-source engines such as VCMI and OpenRCT2 run games you already own. Which files each one needs, where they go on Android, and why Android/data is off limits.
- [Move Google Authenticator Codes to Aegis](https://h5.2113.net/guides/google-authenticator-to-aegis.html): Export your two-factor accounts from Google Authenticator as QR codes and scan them into Aegis: the steps, what can’t move, and how to back up Aegis afterwards.
- [How to Start Shizuku: Wireless Debugging, PC or Root](https://h5.2113.net/guides/how-to-start-shizuku.html): Three ways to start Shizuku (root, wireless debugging on Android 11+, or a computer), what to redo after a reboot, and fixes for when it won't start or keeps stopping.
- [How to Install APKs on Android TV and TV Boxes](https://h5.2113.net/guides/install-apk-android-tv.html): Allow unknown apps, get the file onto the TV by browser, USB or adb, and fix the two classic problems: 32-bit TV boxes and apps missing from the home screen.
- [How to Install LSPosed (Vector) and Enable Modules](https://h5.2113.net/guides/install-lsposed.html): The original LSPosed stopped at Android 14; its maintained fork Vector runs on 8.1 to 17. Which to install, the Zygisk setup you need, and how to enable modules.
- [How to Install XAPK, APKS and APKM Files on Android](https://h5.2113.net/guides/install-xapk-apks-apkm.html): XAPK, APKS and APKM files hold one app split into several APKs. What is in each, how to install them with App Manager or adb, and why “App not installed” appears.
- [KernelSU LKM vs GKI: Why LKM, and How to Install It](https://h5.2113.net/guides/kernelsu-lkm-vs-gki.html): Since v3.0, KernelSU officially supports only LKM mode. What LKM and GKI mean, how to check support and match your KMI, and how to install KernelSU with the manager.
- [How to Play Minecraft Java Edition on Android](https://h5.2113.net/guides/minecraft-java-on-android.html): Open-source launchers run Minecraft Java Edition on Android. What you need (you must own the game), which Java each version needs, and the first launch, step by step.
- [App Not Installed as Package Conflicts: How to Fix](https://h5.2113.net/guides/package-conflicts.html): What Android’s “package conflicts with an existing package” error means: a different signing key, a copy kept for another user, or a clash with another app, and each fix.
- [How to Remove Bloatware Without Root (Shizuku, Canta)](https://h5.2113.net/guides/remove-bloatware-without-root.html): Remove preinstalled apps without root using Shizuku and Canta: what it really does, which apps are risky, how to bring one back, and what changes in Android 17.
- [How to Update Apps You Installed From an APK](https://h5.2113.net/guides/update-sideloaded-apps.html): Why an APK update installs or fails, and four ways to keep sideloaded apps updated: a store app, Obtainium, the app’s own update check, or by hand.
- [How to Verify an APK’s Signature and SHA-256](https://h5.2113.net/guides/verify-apk-signature.html): Check a downloaded APK in two steps: its SHA-256 hash, then its signing certificate with apksigner, keytool or App Manager. Commands, real output, and what a match means.
- [Set Up a Work Profile on Android Without an Employer](https://h5.2113.net/guides/work-profile-without-employer.html): A work profile keeps a second set of apps and data apart on one phone. How to create one yourself with Test DPC or OwnDroid, what it separates, and how to remove it.

## Root & Mods

- **[APatch](https://h5.2113.net/apps/apatch.html)**: The manager for APatch, which roots Android by patching the kernel image and supports both Magisk-style and kernel modules.  
  ARM64 · kernel 3.18–6.1 · unlocked bootloader · no known trackers found · GPL-3.0-only · [source](https://github.com/bmax121/APatch)
- **[Cirno](https://h5.2113.net/apps/cirno.html)**: An app freezer for rooted phones: apps left in the background are frozen so they use no CPU. It has no interface and works automatically once enabled.  
  Root + LSPosed · Android 12+ · kernel 5.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/Freezer-Team/Cirno)
- **[Disable Target API Block](https://h5.2113.net/apps/disable-target-api-block.html)**: Lifts the block Android 14 and later put on installing apps built for very old Android versions, for every install method.  
  Root + LSPosed · Android 14+ · no known trackers found · MPL-2.0 · [source](https://github.com/buttercookie42/DisableTargetAPIBlock)
- **[Free Notifications](https://h5.2113.net/apps/free-notifications.html)**: Makes every notification channel editable again, including locked system ones like the Developer options notice.  
  Root + LSPosed · no known trackers found · EUPL-1.2 · [source](https://github.com/binarynoise/XposedModulets)
- **[HideMockLocation](https://h5.2113.net/apps/hidemocklocation.html)**: Hides an active mock location from the apps you choose, so they stop refusing to work.  
  Root + LSPosed · no known trackers found · MIT · [source](https://github.com/auag0/HideMockLocation)
- **[KernelSU](https://h5.2113.net/apps/kernelsu.html)**: The manager app for KernelSU, a root solution built into the Android kernel. It grants root per app and manages modules.  
  A KernelSU kernel · unlocked bootloader · no known trackers found · GPL-3.0-only · [source](https://github.com/tiann/KernelSU)
- **[KnoxPatch](https://h5.2113.net/apps/knoxpatch.html)**: Gets Samsung apps and features working again on a rooted Galaxy phone by hooking the checks that fail after rooting.  
  Samsung Galaxy · root + LSPosed · no known trackers found · GPL-3.0-or-later · [source](https://github.com/salvogiangri/KnoxPatch)
- **[Magisk](https://h5.2113.net/apps/magisk.html)**: The best-known way to root Android: patch your phone’s boot image with the Magisk app, flash it, and get root access, modules and Zygisk without touching the system partition.  
  Unlocked bootloader · fastboot · Android 6.0+ · no known trackers found · GPL-3.0 · [source](https://github.com/topjohnwu/Magisk)
- **[Neo Backup](https://h5.2113.net/apps/neo-backup.html)**: Back up your apps together with their data on a rooted phone, and put them back later or on a fresh install: one app at a time, in batches or on schedules, encrypted if you want.  
  Root · Android 8.0+ · no known trackers found · AGPL-3.0-only · [source](https://github.com/NeoApplications/Neo-Backup)
- **[NoStorageRestrict](https://h5.2113.net/apps/nostoragerestrict.html)**: Lets apps pick the Download and Android folders through the system folder picker again, which Android 11 blocked.  
  Root + LSPosed · Android 11+ · no known trackers found · GPL-3.0-only · [source](https://github.com/Xposed-Modules-Repo/com.github.dan.nostoragerestrict)
- **[Pengeek](https://h5.2113.net/apps/pengeek.html)**: A large set of system tweaks for Xiaomi phones on HyperOS, and the successor to CustoMIUIzer.  
  HyperOS · Android 15+ · root + LSPosed · no known trackers found · GPL-3.0-only · [source](https://github.com/MonwF/customiuizer)

## Customization

- **[ColorBlendr](https://h5.2113.net/apps/colorblendr.html)**: Take over the Material You palette that Android 12 and later builds from your wallpaper: pick your own seed color, tune saturation and lightness, and override single shades.  
  Root, Shizuku or wireless ADB · Android 12+ · no known trackers found · GPL-3.0-only · [source](https://github.com/Mahmud0808/ColorBlendr)
- **[Fossify Launcher](https://h5.2113.net/apps/fossify-launcher.html)**: A plain home screen that carries on from Simple Launcher: icons, folders and widgets on a grid you size yourself, an app drawer with search, and no account or news feed.  
  Default home app · Android 8.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/FossifyOrg/Launcher)
- **[Global Icon Pack](https://h5.2113.net/apps/global-icon-pack.html)**: Applies your icon pack across all of Android, including Settings, Recents and other screens a launcher can’t reach.  
  Root + LSPosed · no known trackers found · GPL-3.0-only · [source](https://github.com/RichardLuo0/global-icon-pack-android)
- **[Iconify](https://h5.2113.net/apps/iconify.html)**: Restyles Quick Settings, notifications, the volume panel and system icons on Pixel and AOSP ROMs, with previews.  
  Root · Pixel/AOSP ROM · Android 12+ · no known trackers found · GPL-3.0 · [source](https://github.com/Mahmud0808/Iconify)
- **[KISS Launcher](https://h5.2113.net/apps/kiss-launcher.html)**: A home screen built around one search box: type the first letters of an app, a contact or a setting and tap the result. What you open most rises to the top.  
  No root · Android 5.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/Neamar/KISS)
- **[Kvaesitso](https://h5.2113.net/apps/kvaesitso.html)**: A home screen app that puts search first: type instead of scrolling an app drawer, with a calculator, unit converter and quick actions built in, plus clock, calendar, weather and music widgets.  
  No root · Android 8.0+ · no known trackers found · GPL-3.0-or-later · [source](https://github.com/MM2-0/Kvaesitso)
- **[Lawnchair](https://h5.2113.net/apps/lawnchair.html)**: A Pixel-style home screen app built on Android’s Launcher3, with icon packs, grid and icon-size controls. This is the Lawnchair 15 beta; the stable version is on Google Play.  
  No root · no known trackers found · Apache-2.0 · [source](https://github.com/LawnchairLauncher/lawnchair)
- **[Taskbar](https://h5.2113.net/apps/taskbar.html)**: A PC-style start menu and a bar of recent apps that sit on top of any screen, plus floating app windows and a desktop mode for when your phone drives an external display.  
  No root · overlay permission · Android 5.0+ · no known trackers found · Apache-2.0 · [source](https://github.com/farmerbb/Taskbar)

## Network & Privacy

- **[AdAway](https://h5.2113.net/apps/adaway.html)**: A system-wide ad blocker. With root it rewrites the hosts file; without root it filters DNS requests through a local VPN. Either way, ads are blocked before they load.  
  Root, or VPN mode without root · Android 8.0+ · tracker code found: Sentry · GPL-3.0-only · [source](https://github.com/AdAway/AdAway)
- **[Aegis Authenticator](https://h5.2113.net/apps/aegis-authenticator.html)**: Two-factor login codes in an encrypted vault that never goes online. It imports from Google Authenticator and over a dozen other apps, and backs up to a folder you choose.  
  Android 6.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/beemdevelopment/Aegis)
- **[AIS-catcher](https://h5.2113.net/apps/ais-catcher.html)**: Turns your phone and a cheap RTL-SDR dongle into a portable AIS receiver for tracking ships, even offline.  
  RTL-SDR dongle · USB OTG · no known trackers found · GPL-3.0-only · [source](https://github.com/jvde-github/AIS-catcher-for-Android)
- **[Exodus](https://h5.2113.net/apps/exodus.html)**: Find out which tracking libraries are inside the apps you have installed. Exodus looks each one up in the reports of Exodus Privacy, a French non-profit.  
  No root · internet · Android 6.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/Exodus-Privacy/exodus-android-app)
- **[FireWall Blocks](https://h5.2113.net/apps/firewall-blocks.html)**: Blocks Wi-Fi or mobile data per app without root, through Shizuku or a local VPN.  
  Shizuku, or nothing in VPN mode · no known trackers found · MIT · [source](https://github.com/shynoiddev/FireWall-Blocks)
- **[Intra](https://h5.2113.net/apps/intra.html)**: A one-switch app that protects your DNS lookups from tampering: it sends them encrypted over HTTPS, which gets around blocking that works by faking DNS answers.  
  No root · Android 5.0+ · no known trackers found · Apache-2.0 · [source](https://github.com/Jigsaw-Code/Intra)
- **[Kizzy](https://h5.2113.net/apps/kizzy.html)**: Shows Discord Rich Presence from your Android phone, with presets and custom statuses.  
  A Discord account · no known trackers found · GPL-3.0-only · [source](https://github.com/dead8309/Kizzy)
- **[Meshtastic](https://h5.2113.net/apps/meshtastic.html)**: The official app for Meshtastic, the open-source off-grid radio project: pair your phone with a small LoRa radio and message others on the mesh, with no mobile network or internet.  
  A Meshtastic radio · 64-bit phone · Android 8.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/meshtastic/Meshtastic-Android)
- **[Mousedroid](https://h5.2113.net/apps/mousedroid.html)**: Turns your phone into a touchpad, keyboard and numpad for a Windows or Linux PC, over USB or Wi-Fi.  
  Desktop server on the PC · no root · no known trackers found · MIT · [source](https://github.com/darusc/Mousedroid)
- **[NekoBox](https://h5.2113.net/apps/nekobox.html)**: A proxy client built on sing-box, for Shadowsocks, VMess, VLESS, Trojan and other protocols.  
  Your own proxy server · ARM64 · no known trackers found · GPL-3.0-only · [source](https://github.com/MatsuriDayo/NekoBoxForAndroid)
- **[NetGuard](https://h5.2113.net/apps/netguard.html)**: Decide which apps may go online, separately for Wi-Fi and mobile data, without rooting your phone. Blocked traffic is dropped by a local VPN on the device.  
  No root · Android 6.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/M66B/NetGuard)
- **[Open SSTP Client](https://h5.2113.net/apps/open-sstp-client.html)**: An open-source client for SSTP, the VPN protocol that travels over TLS on port 443. It was built for SoftEther VPN servers and the VPN Azure service.  
  No root · an SSTP server · Android 6.0+ · no known trackers found · MIT · [source](https://github.com/kittoku/Open-SSTP-Client)
- **[OpenConnect](https://h5.2113.net/apps/openconnect.html)**: An open-source client for company and campus SSL VPNs: Cisco AnyConnect and ocserv, Palo Alto GlobalProtect, Fortinet, Pulse, Juniper, F5 and Array.  
  No root · a VPN account · Android 6.0+ · no known trackers found · GPL-2.0-or-later · [source](https://gitlab.com/openconnect/ics-openconnect)
- **[OpenVPN for Android](https://h5.2113.net/apps/openvpn-for-android.html)**: The open-source OpenVPN client for Android: import the .ovpn profile from your VPN provider, company or own server, and connect without root.  
  No root · an OpenVPN profile · Android 6.0+ · no known trackers found · GPL-2.0-only · [source](https://github.com/schwabe/ics-openvpn)
- **[PCAPdroid](https://h5.2113.net/apps/pcapdroid.html)**: See every connection your apps make, without root. PCAPdroid captures traffic through a local VPN on the phone, lets you inspect and export it, and can decrypt HTTPS.  
  No root · Android 6.0+ · no known trackers found · GPL-3.0-or-later · [source](https://github.com/emanuele-f/PCAPdroid)
- **[PCAPdroid mitm](https://h5.2113.net/apps/pcapdroid-mitm.html)**: An add-on that lets PCAPdroid decrypt HTTPS traffic on the phone, using mitmproxy.  
  The PCAPdroid app · ARM64 · no known trackers found · GPL-3.0-only · [source](https://github.com/emanuele-f/PCAPdroid-mitm)
- **[Private DNS Quick Toggle](https://h5.2113.net/apps/private-dns-quick-toggle.html)**: A Quick Settings tile that switches Android’s Private DNS between providers in one tap.  
  One-time grant via Shizuku or ADB · no known trackers found · MIT · [source](https://github.com/karasevm/PrivateDNSAndroid)
- **[Shadowsocks](https://h5.2113.net/apps/shadowsocks.html)**: The Shadowsocks project’s own Android client. Add your server or a subscription link, then send all apps, or only the ones you choose, through an encrypted proxy.  
  No root · a Shadowsocks server · Android 6.0+ · no known trackers found · GPL-3.0-or-later · [source](https://github.com/shadowsocks/shadowsocks-android)
- **[Tailscale](https://h5.2113.net/apps/tailscale.html)**: Connect your phone, computers and servers into one private network, a tailnet, built on WireGuard. Once you sign in, your devices can reach each other wherever they are.  
  No root · an account or Headscale · Android 8.0+ · no known trackers found · BSD-3-Clause · [source](https://github.com/tailscale/tailscale-android)
- **[VPN Hotspot](https://h5.2113.net/apps/vpn-hotspot.html)**: Normally, devices on your phone’s hotspot don’t go through its VPN. VPN Hotspot routes them through it, and lets you see and block connected devices. Root required.  
  Root · Android 10+ · 64-bit ARM · tracker code found: Google CrashLytics, Google Firebase Analytics · Apache-2.0 · [source](https://github.com/Mygod/VPNHotspot)
- **[WG Tunnel](https://h5.2113.net/apps/wg-tunnel.html)**: A WireGuard and AmneziaWG client that turns tunnels on and off by itself depending on the network you’re on, with a kill switch, split tunneling and encrypted DNS.  
  No root · a WireGuard config · no known trackers found · MIT · [source](https://github.com/wgtunnel/android)
- **[Windscribe](https://h5.2113.net/apps/windscribe.html)**: The Windscribe VPN app: pick a server location, connect with WireGuard, IKEv2 or OpenVPN, and get a monthly free allowance with an account. This is F-Droid’s build, without Google services.  
  Windscribe account · Android 7.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/Windscribe/Android-App)

## Media

- **[AntennaPod](https://h5.2113.net/apps/antennapod.html)**: A podcast manager and player with no ads and no account: subscribe to any podcast by its feed, download or stream episodes, and control exactly when downloads happen.  
  No root · Android 6.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/AntennaPod/AntennaPod)
- **[ArchiveTune](https://h5.2113.net/apps/archivetune.html)**: A YouTube Music player built on Metrolist’s framework, with quick switching between accounts, local files alongside streaming, podcasts, and detailed audio and lyrics options.  
  No root · Android 8.0+ · no known trackers found · GPL-3.0 · [source](https://github.com/rukamori/ArchiveTune)
- **[Audio Recorder](https://h5.2113.net/apps/audio-recorder.html)**: Record voice notes, lectures or meetings in M4A, WAV or 3GP, see the waveform as you go, and since version 2.5.0 record what other apps are playing. Works fully offline.  
  Android 8.0+ · no account · no known trackers found · Apache-2.0 · [source](https://github.com/Dimowner/AudioRecorder)
- **[Bloomee](https://h5.2113.net/apps/bloomee.html)**: A music player that plays your local files and online streams side by side. Its online sources come from a plugin system, and it adds synced lyrics, an equalizer and Last.fm scrobbling.  
  No root · 64-bit phone · no known trackers found · GPL-2.0-only · [source](https://github.com/HemantKArya/BloomeeTunes)
- **[Flow](https://h5.2113.net/apps/flow.html)**: Watch YouTube and play music from it without signing in, with recommendations worked out on your phone. An unofficial, open-source client; it isn't made by or connected with YouTube.  
  Android 8.0+ · 64-bit ARM · no known trackers found · GPL-3.0-only · [source](https://github.com/A-EDev/Flow)
- **[Fossify Gallery](https://h5.2113.net/apps/fossify-gallery.html)**: A photo and video gallery that stays offline: browse, edit, hide and lock your pictures, restore deleted ones from a recycle bin, and strip location data before you share.  
  No root · Android 8.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/FossifyOrg/Gallery)
- **[Fossify Music Player](https://h5.2113.net/apps/fossify-music-player.html)**: A player for the music files on your phone that carries on from Simple Music Player: browse by album, artist, genre or folder, with playlists, an equalizer and a sleep timer.  
  No root · Android 8.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/FossifyOrg/Music-Player)
- **[FreeTube Android](https://h5.2113.net/apps/freetube.html)**: The Android version of FreeTube: watch YouTube without an account, keep subscriptions, playlists and history on your phone, and organise channels into profiles.  
  No root · Android 10+ · no known trackers found · AGPL-3.0-or-later · [source](https://github.com/MarmadileManteater/FreeTubeAndroid)
- **[Gyawun Music](https://h5.2113.net/apps/gyawun-music.html)**: A light, open-source player for YouTube Music, with offline downloads, synced lyrics, an equalizer and podcasts, and no account sign-in in the app.  
  No root · 64-bit phone · Android 7.0+ · no known trackers found · GPL-3.0 · [source](https://github.com/sheikhhaziq/gyawun_music)
- **[ImageToolbox](https://h5.2113.net/apps/image-toolbox.html)**: A huge open-source image toolkit: batch resizing and conversion, hundreds of filters, EXIF editing, background removal, text recognition and PDF tools. This build has no Google services.  
  Android 7.0+ · 64-bit ARM · no known trackers found · Apache-2.0 · [source](https://github.com/T8RIN/ImageToolbox)
- **[Jellyfin](https://h5.2113.net/apps/jellyfin.html)**: The official Android app for Jellyfin, the free media server: stream your own films, series, music and audiobooks from a server you run, or download them to the phone.  
  Your own Jellyfin server · Android 5.0+ · no known trackers found · GPL-2.0-or-later · [source](https://github.com/jellyfin/jellyfin-android)
- **[Kodi](https://h5.2113.net/apps/kodi.html)**: A media center designed for the TV screen and a remote control: organise and play your own videos, music and photos from local storage and network shares.  
  No root · 64-bit ARM · Android 5.0+ · no known trackers found · GPL-2.0-or-later · [source](https://github.com/xbmc/xbmc)
- **[Kreate](https://h5.2113.net/apps/kreate.html)**: An open-source YouTube Music client that carries on from RiMusic: stream, cache or download songs, sign in to sync your library, and play on Android Auto or a TV.  
  No root · Android 6.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/knighthat/Kreate)
- **[LibreTube](https://h5.2113.net/apps/libretube.html)**: A YouTube client with subscriptions, playlists and downloads and no Google account. Version 32.1 fetches everything straight from YouTube by default; Piped is now optional.  
  No root · no Google account · no known trackers found · GPL-3.0-or-later · [source](https://github.com/libre-tube/LibreTube)
- **[Metrolist](https://h5.2113.net/apps/metrolist.html)**: An open-source YouTube Music client: stream and download from YouTube Music, sync your library if you sign in, and get synced lyrics, an equalizer and listen-together sessions.  
  No root · YouTube Music available where you are · no known trackers found · GPL-3.0-only · [source](https://github.com/MetrolistGroup/Metrolist)
- **[mpvExtended](https://h5.2113.net/apps/mpvextended.html)**: A video player built on mpv, the powerful open-source media engine, with an easier interface than mpv-android, file browsing, network shares and picture-in-picture.  
  No root · 64-bit phone · no known trackers found · Apache-2.0 · [source](https://github.com/marlboro-advance/mpvEx)
- **[NewPipe](https://h5.2113.net/apps/newpipe.html)**: A lightweight player for YouTube, PeerTube, SoundCloud and Bandcamp that works without an account or Google services, with background play, a popup player and downloads.  
  No root · no Google account · tracker code found: ACRA · GPL-3.0-or-later · [source](https://github.com/TeamNewPipe/NewPipe)
- **[Next Player](https://h5.2113.net/apps/next-player.html)**: A modern open-source video player: FFmpeg-based decoders for most formats, swipe gestures for volume, brightness and seeking, and playback straight from network shares.  
  No root · 64-bit phone · Android 7.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/anilbeesetti/nextplayer)
- **[Nova Video Player](https://h5.2113.net/apps/nova-video-player.html)**: An open-source video player for phones, tablets and Android TV: it plays files from the device and from network shares, and builds a library with posters and descriptions.  
  No root · Android 6.0+ · 32- or 64-bit · tracker code found: Sentry · Apache-2.0 · [source](https://github.com/nova-video-player/aos-AVP)
- **[Open Camera](https://h5.2113.net/apps/open-camera.html)**: A full-featured open-source camera: manual focus and exposure, RAW photos, HDR and exposure bracketing, a night mode, and date, location or text stamps on your photos.  
  No root · Android 6.0+ · no known trackers found · GPL-3.0-or-later · [source](https://sourceforge.net/p/opencamera/code)
- **[OuterTune](https://h5.2113.net/apps/outertune.html)**: A Material 3 music player that combines YouTube Music with your own music files. The version here is the last one with YouTube Music, which its maintainers no longer develop.  
  No root · Android 7.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/OuterTune/OuterTune)
- **[PhotonCamera](https://h5.2113.net/apps/photoncamera.html)**: An experimental camera that captures raw frames and stacks them for HDR, with manual controls.  
  ARM64 · beta · no known trackers found · GPL-3.0-or-later · [source](https://github.com/eszdman/PhotonCamera)
- **[PipePipe](https://h5.2113.net/apps/pipepipe.html)**: A fork of NewPipe with more of everything: SponsorBlock and Return YouTube Dislike, filters that hide Shorts and paid videos, gestures, a sleep timer and BiliBili support.  
  No root · 64-bit phone · tracker code found: ACRA · GPL-3.0-only · [source](https://github.com/InfinityLoop1308/PipePipe)
- **[Seal](https://h5.2113.net/apps/seal.html)**: A friendly Android front end for yt-dlp: share or paste a link from a supported site, pick video or audio, and Seal handles the download, whole playlists included.  
  No root · 64-bit phone · Android 5.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/JunkFood02/Seal)
- **[SimpMusic](https://h5.2113.net/apps/simpmusic.html)**: An open-source YouTube Music player for Android and desktop, with synced lyrics from several sources, a ten-band equalizer, Android Auto and offline downloads. No account needed.  
  No root · 64-bit phone · Android 8.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/maxrave-dev/SimpMusic)
- **[SkyTube](https://h5.2113.net/apps/skytube.html)**: A YouTube client that lets you filter what you see: block channels, hide low-view videos, keep bookmarks and subscriptions on your phone, and download videos.  
  No root · no Google account · Android 4.4+ · no known trackers found · GPL-3.0-only · [source](https://github.com/SkyTubeTeam/SkyTube)
- **[SmartTube](https://h5.2113.net/apps/smarttube.html)**: A YouTube client made for the TV screen and remote, for Android TVs, TV boxes and sticks: browse and play videos, skip segments with SponsorBlock, change playback speed.  
  Android TV or TV box · not for phones · tracker code found: Google CrashLytics · MIT · [source](https://github.com/yuliskov/SmartTube)
- **[SongSync](https://h5.2113.net/apps/songsync.html)**: Downloads lyrics for the songs in your local music library and can embed them in the files.  
  No root · local music files · no known trackers found · GPL-3.0-only · [source](https://github.com/Lambada10/SongSync)
- **[Spotube](https://h5.2113.net/apps/spotube.html)**: A music streaming app in which plugins supply everything: song information, playlists and audio. Out of the box it uses MusicBrainz and ListenBrainz for metadata and YouTube for audio.  
  No root · Android 7.0+ · no known trackers found · BSD-4-Clause · [source](https://github.com/KRTirtho/spotube)
- **[Tubular](https://h5.2113.net/apps/tubular.html)**: A fork of NewPipe that adds SponsorBlock and Return YouTube Dislike. Its developer has discontinued it, so this final version won’t receive fixes when YouTube changes.  
  No root · no Google account · tracker code found: ACRA · GPL-3.0-only · [source](https://github.com/polymorphicshade/Tubular)
- **[VIVI Music](https://h5.2113.net/apps/vivi.html)**: A YouTube Music client that puts its effort into looks: colors that follow the album art, animated backdrops, karaoke-style lyrics, plus downloads and Android Auto.  
  No root · no known trackers found · GPL-3.0-only · [source](https://github.com/vivizzz007/vivi-music)
- **[VLC](https://h5.2113.net/apps/vlc.html)**: The open-source player that plays almost anything: video and audio files in nearly every format, network streams, DVD images and the shared folders on your network.  
  No root · 64-bit phone · Android 4.2+ · no known trackers found · GPL-3.0-only · [source](https://code.videolan.org/videolan/vlc-android)
- **[Volume Manager](https://h5.2113.net/apps/volume-manager.html)**: Gives each app its own volume, from its own screen or a replacement volume popup.  
  Shizuku · Android 13+ · no known trackers found · GPL-2.0-only · [source](https://github.com/yume-chan/VolumeManager)
- **[YTDLnis](https://h5.2113.net/apps/ytdlnis.html)**: A full-featured Android front end for yt-dlp: queue and schedule downloads, trim by timestamp or chapter, embed subtitles and metadata, or run your own yt-dlp commands.  
  No root · 64-bit phone · Android 7.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/deniscerri/ytdlnis)

## System Tools

- **[Activity Launcher](https://h5.2113.net/apps/activity-launcher.html)**: Open the screens apps don’t show you: hidden settings pages and other activities, launched directly or pinned to your home screen as shortcuts.  
  No root · Android 4.1+ · no known trackers found · ISC · [source](https://github.com/butzist/ActivityLauncher)
- **[Amaze File Manager](https://h5.2113.net/apps/amaze-file-manager.html)**: An open-source Material Design file manager with tabs, a root explorer, AES file encryption, an app manager that backs up APKs, network shares and a built-in FTP server.  
  No root needed · Android 5.0+ · tracker code found: ACRA · GPL-3.0-only · [source](https://github.com/TeamAmaze/AmazeFileManager)
- **[Androoster](https://h5.2113.net/apps/androoster.html)**: A toolbox of on/off root tweaks for CPU, memory, kernel, I/O and network settings.  
  Root + BusyBox · no known trackers found · Apache-2.0 · [source](https://github.com/cioccarellia/androoster)
- **[APKUpdater](https://h5.2113.net/apps/apkupdater.html)**: Checks your installed apps for updates on APKMirror, Aptoide, F-Droid and GitHub, and can install them.  
  No root · no known trackers found · GPL-3.0-only · [source](https://github.com/rumboalla/apkupdater)
- **[App Lock](https://h5.2113.net/apps/app-lock.html)**: Put a PIN, pattern, password or your fingerprint in front of the apps you choose. Open source and fully offline: the app doesn’t even ask for internet access.  
  No root · Android 8.0+ · Shizuku optional · no known trackers found · MIT · [source](https://github.com/aload0/AppLock)
- **[App Manager](https://h5.2113.net/apps/app-manager.html)**: A power-user tool for everything about installed apps: scan them for trackers, install split APKs, back them up, revoke permissions, freeze apps or block their components.  
  No root for basics · root or ADB for more · Android 5.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/MuntashirAkon/AppManager)
- **[aShell](https://h5.2113.net/apps/ashell.html)**: The original local ADB shell for Shizuku: type the commands you’d run with adb shell straight on the phone, with examples, bookmarks and history to help.  
  Shizuku · Android 7.0+ · no known trackers found · GPL-3.0-or-later · [source](https://gitlab.com/sunilpaulmathew/ashell)
- **[aShell You](https://h5.2113.net/apps/ashell-you.html)**: A Material You terminal for ADB commands: run shell commands on the phone itself through Shizuku or root, or on another Android device over OTG or wireless debugging.  
  Shizuku or root · Android 9+ · no known trackers found · GPL-3.0-or-later · [source](https://github.com/DP-Hridayan/aShellYou)
- **[Aurora Store](https://h5.2113.net/apps/aurora-store.html)**: An open-source client for Google Play: search, download and update free apps from Play without the Play Store app, signed in anonymously or with your own account.  
  No root · no Google services needed · no known trackers found · GPL-3.0-or-later · [source](https://gitlab.com/AuroraOSS/AuroraStore)
- **[Canta](https://h5.2113.net/apps/canta.html)**: Remove the apps your phone maker pre-installed, without root. Canta works through Shizuku, marks which apps are risky to remove, and can put system apps back.  
  Shizuku · Android 9+ · no known trackers found · LGPL-3.0-or-later · [source](https://github.com/samolego/Canta)
- **[Current Activity](https://h5.2113.net/apps/current-activity.html)**: A small tool for developers and tinkerers: it shows the package name and activity class of whatever is on screen, in a floating window you can move and copy from.  
  No root · usage access · Android 7.0+ · no known trackers found · GPL-3.0-or-later · [source](https://github.com/codehasan/Current-Activity)
- **[Droid-ify](https://h5.2113.net/apps/droid-ify.html)**: A tidier way to use F-Droid: browse and install from F-Droid, IzzyOnDroid and your own repositories, keep apps updated in the background, and install without prompts through Shizuku or root.  
  No root needed · Android 6.0+ · no known trackers found · GPL-3.0-or-later · [source](https://github.com/Droid-ify/client)
- **[Edge Seek](https://h5.2113.net/apps/edge-seek.html)**: Turns the edges of your screen into sliders for volume and brightness, with a dimmer below the minimum brightness.  
  No root · no known trackers found · Apache-2.0 · [source](https://github.com/LSafer/edgeseek)
- **[Flicky](https://h5.2113.net/apps/flicky.html)**: An app store for open-source apps that you can use with a TV remote. It browses F-Droid, IzzyOnDroid and other repositories, and installs and updates apps on Android TV and Google TV.  
  No root · Android 6.0+ · made for TV · no known trackers found · GPL-3.0-only · [source](https://github.com/mlm-games/flicky)
- **[Florid](https://h5.2113.net/apps/florid.html)**: A redesigned client for browsing, installing and updating apps from F-Droid and other repositories you add. It sends a daily usage ping, which you can switch off.  
  No root · ARM64 · Android 7.0+ · no known trackers found · GPL-3.0 · [source](https://github.com/Nandanrmenon/florid)
- **[Fossify File Manager](https://h5.2113.net/apps/fossify-file-manager.html)**: An open-source file manager that carries on from Simple File Manager: favourites, search, ZIP archives, a storage analyser, locks for hidden files, and root access if you have it.  
  No root needed · all files access · Android 8.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/FossifyOrg/File-Manager)
- **[Geto](https://h5.2113.net/apps/geto.html)**: Set system settings for one app: Geto applies them when it launches that app and restores them from a notification afterwards. Its author built it to switch developer options off for a banking app.  
  Android 7.0+ · adb to grant one permission · no known trackers found · GPL-3.0-only · [source](https://github.com/JackEblan/Geto)
- **[Hail](https://h5.2113.net/apps/hail.html)**: Switch off the apps you rarely use instead of uninstalling them: Hail disables, hides or suspends them, and brings them back with a tap when you need them.  
  Shizuku, root or device owner · Android 6.0+ · no known trackers found · GPL-3.0-or-later · [source](https://github.com/aistra0528/Hail)
- **[Install with Options](https://h5.2113.net/apps/install-with-options.html)**: Installs APKs with options normally reserved for adb: test-only apps, downgrades, split APKs and Android 14’s blocked old apps.  
  Shizuku or root · tracker code found: Bugsnag · MIT · [source](https://github.com/zacharee/InstallWithOptions)
- **[Key Mapper](https://h5.2113.net/apps/key-mapper.html)**: Turn almost any button into a shortcut: volume and side keys, gamepads, keyboards and headset buttons can trigger more than 100 actions, even with the screen off in Expert Mode.  
  No root · accessibility service · Android 8.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/keymapperorg/KeyMapper)
- **[LocalSend](https://h5.2113.net/apps/localsend.html)**: An open-source AirDrop alternative that works across Android, Windows, macOS, Linux and iOS: pick a nearby device on the same network and send files or text directly.  
  No root · same local network · Android 7.0+ · no known trackers found · Apache-2.0 · [source](https://github.com/localsend/localsend)
- **[Material Files](https://h5.2113.net/apps/material-files.html)**: A clean, open-source file manager in Material Design: open and create archives, browse network shares, and reach files ordinary apps can’t, with root or, since version 1.7.5, Shizuku.  
  No root needed · Android 6.0+ · no known trackers found · GPL-3.0-or-later · [source](https://github.com/zhanghai/MaterialFiles)
- **[Neo Store](https://h5.2113.net/apps/neo-store.html)**: An alternative app for browsing and installing open-source apps from F-Droid, IzzyOnDroid and other repositories, with filters, download statistics and silent updates through root or Shizuku.  
  No root · Android 8.0+ · no known trackers found · GPL-3.0-or-later · [source](https://codeberg.org/NeoApplications/Neo-Store)
- **[Obtainium](https://h5.2113.net/apps/obtainium.html)**: Installs and updates Android apps straight from where developers publish them, such as GitHub releases, and tells you when a new version is out.  
  No root · no known trackers found · GPL-3.0-only · [source](https://github.com/ImranR98/Obtainium)
- **[OwnDroid](https://h5.2113.net/apps/owndroid.html)**: Puts Android’s device-owner and work-profile controls on your own phone: block uninstalls, disable the camera, manage users and more.  
  Shizuku, Dhizuku or ADB to activate · no known trackers found · GPL-3.0-or-later · [source](https://github.com/BinTianqi/OwnDroid)
- **[Payload Dumper](https://h5.2113.net/apps/payload-dumper.html)**: Extracts boot.img and other partition images from an OTA zip or payload.bin on the phone, with hash verification.  
  No root · a full OTA package · no known trackers found · GPL-3.0-only · [source](https://github.com/rajmani7584/Payload-Dumper-Android)
- **[Prism File Explorer](https://h5.2113.net/apps/prism-file-explorer.html)**: A Material 3 file manager with tabs, ZIP archives and built-in viewers for images, video, audio, PDF and code.  
  No root · no known trackers found · GPL-3.0-only · [source](https://github.com/Raival-e/Prism-File-Explorer)
- **[RustDesk](https://h5.2113.net/apps/rustdesk.html)**: Control a computer or another phone remotely, or let someone help you with yours. RustDesk is open source and can run entirely on a server you host yourself.  
  No root · Android 5.1+ · 6.0+ to share the screen · no known trackers found · GPL-3.0-only · [source](https://github.com/rustdesk/rustdesk)
- **[Shizuku](https://h5.2113.net/apps/shizuku.html)**: Lets other apps use Android’s system APIs with the same rights as ADB. You start it once with wireless debugging or root, and apps that support it can do what normally needs a computer.  
  Root, or wireless debugging on Android 11+ · no known trackers found · Apache-2.0 · [source](https://github.com/RikkaApps/Shizuku)
- **[Termux](https://h5.2113.net/apps/termux.html)**: A terminal emulator and Linux environment for Android. Install packages with pkg or apt, then run shells, scripting languages, SSH, Git and much more, without root.  
  No root · Android 7.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/termux/termux-app)
- **[Termux:API](https://h5.2113.net/apps/termux-api.html)**: The add-on that connects the Termux command line to Android itself. With it, your scripts can show notifications, read sensors and location, send SMS, take photos and much more.  
  Termux from F-Droid · Android 7.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/termux/termux-api)
- **[Termux:Boot](https://h5.2113.net/apps/termux-boot.html)**: A tiny add-on that runs your own Termux scripts every time the phone finishes starting, so servers and background jobs come back by themselves after a reboot.  
  Termux from F-Droid · Android 5.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/termux/termux-boot)
- **[Termux:Float](https://h5.2113.net/apps/termux-float.html)**: A terminal that floats above your other apps, so a Termux session can stay on screen while you read documentation, follow a guide or keep an eye on a long job.  
  Termux from F-Droid · overlay permission · Android 7.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/termux/termux-float)
- **[Termux:GUI](https://h5.2113.net/apps/termux-gui.html)**: An add-on that lets programs running in Termux draw native Android interfaces, such as windows, dialogs, buttons and home screen widgets, without VNC or an X server.  
  Termux from F-Droid · a GUI library · Android 7.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/termux/termux-gui)
- **[Termux:Styling](https://h5.2113.net/apps/termux-styling.html)**: Change how Termux looks without editing config files: pick a color scheme and a terminal font from a menu, and Termux applies them straight away.  
  Termux from F-Droid · Android 5.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/termux/termux-styling)
- **[Termux:Tasker](https://h5.2113.net/apps/termux-tasker.html)**: A plugin that lets automation apps such as Tasker run your Termux scripts, so a shell script can react to a time, a place, a notification or any other trigger.  
  Termux from F-Droid · Tasker or similar · Android 5.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/termux/termux-tasker)
- **[Termux:Widget](https://h5.2113.net/apps/termux-widget.html)**: Turns your Termux scripts into buttons: a home screen widget that lists them, shortcuts for single scripts, and device controls that run them without opening Termux.  
  Termux from F-Droid · Android 7.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/termux/termux-widget)
- **[Test DPC](https://h5.2113.net/apps/test-dpc.html)**: Google's sample app for Android Enterprise: create a work profile on your own phone, or make a spare device fully managed, and try the policies Android offers. Built for testing, not daily use.  
  Android 5.0+ · adb for device owner · no known trackers found · Apache-2.0 · [source](https://github.com/googlesamples/android-testdpc)
- **[Universal Installer](https://h5.2113.net/apps/universal-installer.html)**: An open-source installer for APK files and split-APK bundles, with optional silent installs through Shizuku or root, OBB game data placement, and an update tracker for apps from GitHub and F-Droid.  
  Android 7.0+ · Shizuku or root optional · no known trackers found · GPL-3.0-only · [source](https://github.com/pass-with-high-score/universal-installer)
- **[USB HID Client](https://h5.2113.net/apps/usb-hid-client.html)**: Makes your phone act as a real USB keyboard and mouse, with no software on the computer, even in BIOS.  
  Root (Magisk or KernelSU) · no known trackers found · GPL-3.0-only · [source](https://github.com/Arian04/android-hid-client)

## Cloud & Self-Hosted

- **[Cryptomator](https://h5.2113.net/apps/cryptomator.html)**: Encrypts files on your phone before they are uploaded, so the cloud only ever stores scrambled data. Opens vaults made with the desktop app. Without a paid license key, access is read-only.  
  License key to edit vaults · Android 8.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/cryptomator/android)
- **[Home Assistant](https://h5.2113.net/apps/home-assistant.html)**: The official Android app for Home Assistant, in the minimal flavor that works without Google Play services. It needs a Home Assistant server that you run yourself.  
  Your own Home Assistant server · Android 6.0+ · tracker code found: AltBeacon · Apache-2.0 · [source](https://github.com/home-assistant/android)
- **[Immich](https://h5.2113.net/apps/immich.html)**: The mobile app for Immich, a self-hosted photo and video library: back up the camera roll to a server you run, then browse, search and share it from the phone.  
  Your own Immich server · Android 8.0+ · no known trackers found · AGPL-3.0-only · [source](https://github.com/immich-app/immich)
- **[Nextcloud](https://h5.2113.net/apps/nextcloud.html)**: The official Android app for Nextcloud Files: reach the files on your own Nextcloud server, or an account with a provider, upload photos automatically and keep chosen folders synced.  
  A Nextcloud server · 64-bit phone · Android 9+ · no known trackers found · GPL-2.0-only · [source](https://github.com/nextcloud/android)

## Productivity

- **[AnySoftKeyboard](https://h5.2113.net/apps/anysoftkeyboard.html)**: An open-source on-screen keyboard that you can shape to your liking: word suggestions and next-word prediction, gesture typing, themes, and extra languages as separate packs.  
  No root · Android 6.0+ · no known trackers found · Apache-2.0 · [source](https://github.com/AnySoftKeyboard/AnySoftKeyboard)
- **[Breezy Weather](https://h5.2113.net/apps/breezy-weather.html)**: A weather app that lets you choose the source: forecasts from more than 50 weather services, with rain in the next hour, severe weather alerts, air quality, pollen and widgets.  
  No root · Android 6.0+ · no known trackers found · LGPL-3.0-only · [source](https://github.com/breezy-weather/breezy-weather)
- **[Fossify Calendar](https://h5.2113.net/apps/fossify-calendar.html)**: An open-source calendar that works offline: day, week, month and year views, recurring events, reminders, built-in public holidays for 70 countries and home screen widgets.  
  No root · Android 8.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/FossifyOrg/Calendar)
- **[Fossify Clock](https://h5.2113.net/apps/fossify-clock.html)**: An open-source clock app that carries on from Simple Clock: alarms with gradual volume and an adjustable snooze, a world clock, timers, a stopwatch and widgets.  
  No root · Android 8.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/FossifyOrg/Clock)
- **[Fossify Contacts](https://h5.2113.net/apps/fossify-contacts.html)**: An open-source contacts app that carries on from Simple Contacts: groups and favourites, vCard import and export, and private contacts that other apps can’t read.  
  No root · Android 8.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/FossifyOrg/Contacts)
- **[Fossify Keyboard](https://h5.2113.net/apps/fossify-keyboard.html)**: A plain on-screen keyboard that carries on from Simple Keyboard: 44 layouts, from Portuguese to Colemak, an emoji picker and a clipboard manager, but no word suggestions.  
  No root · Android 8.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/FossifyOrg/Keyboard)
- **[Fossify Notes](https://h5.2113.net/apps/fossify-notes.html)**: A plain notes app that carries on from Simple Notes Pro: text notes and checklists, home screen widgets, optional locks, and backups that stay on your phone.  
  No root · Android 8.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/FossifyOrg/Notes)
- **[Fossify Phone](https://h5.2113.net/apps/fossify-phone.html)**: An open-source phone app that carries on from Simple Dialer: a call log, favourites and speed dial, blocking of numbers or unknown callers, and multi-SIM support.  
  Default phone app · Android 8.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/FossifyOrg/Phone)
- **[HeliBoard](https://h5.2113.net/apps/heliboard.html)**: An on-screen keyboard that works fully offline: word suggestions from dictionaries you add, typing in several languages at once, themes, clipboard history, and one-handed and split modes.  
  No root · Android 5.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/HeliBorg/HeliBoard)
- **[Tomato](https://h5.2113.net/apps/tomato.html)**: A minimalist Pomodoro timer: focus for 25 minutes, take a short break, and follow your focus time in daily, weekly, monthly and yearly statistics. It never goes online.  
  Android 8.0+ · no account · no known trackers found · GPL-3.0-only · [source](https://github.com/nsh07/Tomato)
- **[Unexpected Keyboard](https://h5.2113.net/apps/unexpected-keyboard.html)**: A small on-screen keyboard where you swipe a key toward one of its corners to type the symbol printed there, so more characters fit on one page. Designed for programmers using Termux.  
  No root · Android 5.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/Julow/Unexpected-Keyboard)

## Reading & Maps

- **[Kiwix](https://h5.2113.net/apps/kiwix.html)**: Reads Wikipedia and other websites offline from downloaded ZIM archives. This is the full version, which can open ZIM files from any folder, unlike the Google Play version.  
  No root · 64-bit phone · Android 7.1+ · no known trackers found · GPL-3.0 · [source](https://github.com/kiwix/kiwix-android)
- **[KOReader](https://h5.2113.net/apps/koreader.html)**: A document reader built first for e-ink readers such as Kindle and Kobo, and available on Android: EPUB, PDF, DjVu, comics and more, with dictionaries and Calibre built in.  
  No root · 64-bit phone · Android 4.3+ · no known trackers found · AGPL-3.0-only · [source](https://github.com/koreader/koreader)
- **[OsmAnd~](https://h5.2113.net/apps/osmand.html)**: Offline maps and turn-by-turn navigation based on OpenStreetMap, for driving, cycling, hiking and boating. This is OsmAnd~, the build F-Droid makes from the source code.  
  No root · 64-bit phone · Android 7.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/osmandapp/Osmand)
- **[Wikipedia](https://h5.2113.net/apps/wikipedia.html)**: The Wikimedia Foundation’s own Wikipedia app: search and read articles, save them for reading offline, and edit. This copy is F-Droid’s build, without Google’s services.  
  Android 6.0+ · account optional · no known trackers found · Apache-2.0 · [source](https://github.com/wikimedia/apps-android-wikipedia)

## Games: Strategy Games

- **[fheroes2](https://h5.2113.net/games/fheroes2.html)**: Play Heroes of Might and Magic II on your phone with an engine rewritten from scratch. Bring the original game’s files or try the free demo; this is the project’s own APK.  
  Heroes II files or demo · Android 5.1+ · no known trackers found · GPL-2.0 · [source](https://github.com/ihhub/fheroes2)
- **[Lichess](https://h5.2113.net/games/lichess.html)**: The official app of Lichess, the free and open-source chess site: play people online, play the computer offline, solve puzzles and analyse your games.  
  Android 8.0+ · 64-bit ARM · account optional · no known trackers found · GPL-3.0-or-later · [source](https://github.com/lichess-org/mobile)
- **[Mindustry](https://h5.2113.net/games/mindustry.html)**: Build drills, conveyor belts and factories that feed your turrets and units, and defend your core through campaigns on two planets. Free and open source; this is F-Droid’s build.  
  Android 5.0+ · no account · no known trackers found · GPL-3.0-or-later · [source](https://github.com/Anuken/Mindustry)
- **[The Battle for Wesnoth](https://h5.2113.net/games/wesnoth.html)**: Lead fantasy armies through story campaigns or online battles, turn by turn on a hex map. On Android, only the 1.19 development branch exists, and the project calls it an alpha.  
  Android 6.0+ · 64-bit ARM · 0.6 GB download · no known trackers found · GPL-2.0-or-later · [source](https://github.com/wesnoth/wesnoth)
- **[Unciv](https://h5.2113.net/games/unciv.html)**: Found cities, research technologies and grow an empire turn by turn, against the computer or friends. Small, free and open source, with mods; this is F-Droid’s build.  
  Android 5.0+ · no account · no known trackers found · MPL-2.0 · [source](https://github.com/yairm210/Unciv)
- **[VCMI](https://h5.2113.net/games/vcmi.html)**: Play Heroes of Might and Magic III on your phone with a rebuilt, open-source engine. Bring the original game files (the GOG version works); VCMI supplies everything else.  
  Heroes III files · Android 5.0+ · 64-bit ARM · no known trackers found · GPL-2.0-or-later · [source](https://github.com/vcmi/vcmi)

## Games: Sandbox Games

- **[Luanti](https://h5.2113.net/games/luanti.html)**: A block-building game engine: install a game from its built-in library, then play alone, with friends or on public servers. Formerly called Minetest; this is F-Droid’s build.  
  Android 5.0+ · a game from ContentDB · no known trackers found · LGPL-2.1-or-later · [source](https://github.com/luanti-org/luanti)
- **[Principia](https://h5.2113.net/games/principia.html)**: Build cars, calculators, robots and whole games out of more than 200 physical objects, circuits and Lua scripts, then play levels made by the community. Once a paid game, now free and open source.  
  Android 5.0+ · online for community levels · no known trackers found · [source](https://github.com/Bithack/principia)

## Games: Adventure & RPG

- **[Brogue CE Android](https://h5.2113.net/games/brogue-ce.html)**: Fight your way down a randomly generated dungeon to retrieve the Amulet of Yendor from its 26th level. A personal, unofficial port of Brogue: Community Edition to Android.  
  Android 7.0+ · no account · offline · no known trackers found · AGPL-3.0-or-later · [source](https://github.com/tyrannotorus/c-brogue-ce-android)
- **[Dungeon Crawl Stone Soup](https://h5.2113.net/games/dungeon-crawl-stone-soup.html)**: Pick a species and a background, then dive for the Orb of Zot through a dungeon full of monsters and fickle gods. A deep, free roguelike that runs entirely offline.  
  Android 5.0+ · no account · offline · no known trackers found · GPL-2.0-or-later · [source](https://github.com/crawl/crawl)
- **[Endless Sky](https://h5.2113.net/games/endless-sky.html)**: Fly a starship between star systems, trade, take on missions and fight pirates. This is an unofficial Android port of the desktop game; it needs no internet and no permissions.  
  Android 5.0+ · OpenGL ES 3.0 · works offline · no known trackers found · GPL-3.0-only · [source](https://github.com/thewierdnut/endless-mobile)
- **[HyperRogue](https://h5.2113.net/games/hyperrogue.html)**: A turn-based roguelike on a hyperbolic plane: hunt for treasure through dozens of lands in a world where you almost never pass the same place twice. This is the free GPL build, not HyperRogue Gold.  
  Android 5.0+ · works offline · no known trackers found · GPL-2.0-only · [source](https://github.com/zenorogue/hyperrogue)
- **[Shattered Pixel Dungeon](https://h5.2113.net/games/shattered-pixel-dungeon.html)**: Pick a hero, go down, and try to survive: every run has new levels, enemies and loot, and dying means starting over. Free and open source, from a single developer.  
  Android 5.0+ · no account · no known trackers found · GPL-3.0-only · [source](https://github.com/00-Evan/shattered-pixel-dungeon)

## Games: Simulation Games

- **[OpenRCT2](https://h5.2113.net/games/openrct2.html)**: Build and run theme parks from RollerCoaster Tycoon 2 on Android, with an open-source re-implementation of the game. You copy over files from a desktop copy of the game; the rest is included.  
  RCT2 desktop files · Android 7.0+ · no known trackers found · GPL-3.0 · [source](https://github.com/OpenRCT2/OpenRCT2)
- **[OpenTTD](https://h5.2113.net/games/openttd.html)**: Build railways, roads, airports and shipping lines and grow a transport company over decades. An unofficial Android port of OpenTTD, ready to play with its free graphics and sound.  
  Android 7.0+ · no original files needed · no known trackers found · LGPL-2.1-or-later · [source](https://github.com/n-ice-community/commandergenius)

## Games: Racing Games

- **[Pixel Wheels](https://h5.2113.net/games/pixel-wheels.html)**: Race pixel-art cars around nine tracks seen from above, firing guns, mines and missiles at your rivals. Free, open source, and playable offline from start to finish.  
  Android 4.4+ · works offline · no known trackers found · [source](https://github.com/agateau/pixelwheels)
- **[SuperTuxKart](https://h5.2113.net/games/supertuxkart.html)**: Race Tux and friends through 21 tracks with power-ups, or play battles, soccer and egg hunts, alone or online. Free and open source, with no ads or microtransactions.  
  Android 5.0+ · account only for online races · no known trackers found · [source](https://github.com/supertuxkart/stk-code)

## Games: Educational Games

- **[GCompris](https://h5.2113.net/games/gcompris.html)**: Nearly 200 learning activities for children from 2 to 10: reading, counting, the clock, science, geography, logic games and more. Free, open source, no ads and no in-app purchases.  
  Android 9+ · 64-bit ARM · no known trackers found · AGPL-3.0-only · [source](https://invent.kde.org/education/gcompris)

## Games: Puzzle & Arcade

- **[Simon Tatham's Puzzles](https://h5.2113.net/games/simon-tatham-puzzles.html)**: Forty small logic puzzles, from Sudoku-style Solo to Loopy, Bridges and Mines, each generating a new grid whenever you want one. Free, offline and without ads.  
  Android 5.0+ · no known trackers found · MIT · [source](https://github.com/chrisboyle/sgtpuzzles)
- **[Vector Pinball](https://h5.2113.net/games/vector-pinball.html)**: Pinball drawn with lines and circles, where the physics matter more than the graphics: nine tables, multiball, local high scores, and not a single permission requested.  
  Android 4.4+ · no known trackers found · GPL-3.0-only · [source](https://github.com/dozingcat/Vector-Pinball)

## Games: PC Emulators

- **[Winlator](https://h5.2113.net/games/winlator.html)**: Runs Windows (x86-64) games and programs on an Android phone, using Wine to handle Windows and Box64 to translate the x86 code.  
  64-bit ARM phone · Android 8+ · no root · no known trackers found · LGPL-2.1 · [source](https://github.com/brunodev85/winlator)

## Games: Minecraft Launchers

- **[Amethyst Launcher](https://h5.2113.net/games/amethyst-launcher.html)**: Runs the PC (Java) edition of Minecraft on Android. It continues PojavLauncher and supports Forge and Fabric mods.  
  Android 5+ · Microsoft account with Minecraft Java · no known trackers found · LGPL-3.0 · [source](https://github.com/AngelAuraMC/Amethyst-Android)
- **[Fold Craft Launcher](https://h5.2113.net/games/fold-craft-launcher.html)**: A Minecraft Java Edition launcher for Android that combines HMCL’s version and mod management with the Amethyst engine.  
  Android 8.0+ · Minecraft: Java Edition, sold by Mojang · no known trackers found · GPL-3.0 · [source](https://github.com/FCL-Team/FoldCraftLauncher)
- **[Zalith Launcher 2](https://h5.2113.net/games/zalith-launcher-2.html)**: A newly designed Minecraft Java Edition launcher for Android. It uses the PojavLauncher engine under a modern Material Design 3 interface.  
  Android 8+ · Microsoft account with Minecraft Java · no known trackers found · GPL-3.0 · [source](https://github.com/ZalithLauncher/ZalithLauncher2)

## Games: Console Emulators

- **[Dolphin Emulator](https://h5.2113.net/games/dolphin-emulator.html)**: The open-source GameCube and Wii emulator, on Android. It needs a 64-bit phone and a GPU with OpenGL ES 3.0 or Vulkan, and you bring your own games.  
  Your own games · 64-bit phone · Android 5.0+ · no known trackers found · GPL-2.0-or-later · [source](https://github.com/dolphin-emu/dolphin)
- **[Lemuroid](https://h5.2113.net/games/lemuroid.html)**: One app for many retro consoles, built on libretro: it finds the games on your phone, saves your progress automatically and works with touch controls or a gamepad. Games are not included.  
  Your own games · Android 6.0+ · no known trackers found · GPL-3.0-or-later · [source](https://github.com/Swordfish90/Lemuroid)
- **[melonDS](https://h5.2113.net/games/melonds.html)**: An emulator for Nintendo DS and DSi games. DS games need no BIOS files, thanks to a built-in open-source replacement; the games themselves are not included.  
  Your own DS games · Android 7.0+ · no known trackers found · GPL-3.0 · [source](https://github.com/rafaelvcaetano/melonDS-android)
- **[PPSSPP](https://h5.2113.net/games/ppsspp.html)**: A PSP emulator that needs no BIOS file, adds sharper graphics and save states, and works with touch controls, gamepads or a keyboard. Games are not included.  
  Your own PSP games · OpenGL ES 2.0 · Android 2.3+ · no known trackers found · GPL-2.0-or-later · [source](https://github.com/hrydgard/ppsspp)
- **[RetroArch](https://h5.2113.net/games/retroarch.html)**: One frontend for many emulators: RetroArch runs emulator cores for many consoles and computers under a single interface, with its core downloader built in. Games are not included.  
  Your own games and BIOS · Android 4.1+ · no known trackers found · GPL-3.0-only · [source](https://github.com/libretro/RetroArch)
- **[Vita3K](https://h5.2113.net/games/vita3k.html)**: An experimental PlayStation Vita emulator. It runs homebrew and many commercial Vita games that you dump from your own console.  
  64-bit phone · Android 9+ · your own games · no known trackers found · GPL-2.0 · [source](https://github.com/Vita3K/Vita3K)

## Games: Game Streaming

- **[Moonlight](https://h5.2113.net/games/moonlight.html)**: Plays the games on your own gaming PC on an Android phone, tablet or TV. The game runs on the PC, with Sunshine or NVIDIA GeForce Experience; Moonlight shows the picture and sends your controls back.  
  A gaming PC as the host · Android 5.0+ · no known trackers found · GPL-3.0 · [source](https://github.com/moonlight-stream/moonlight-android)

## Data, reports and citation

- **[apps.json](apps.json)** and **[apps.csv](apps.csv)**: one row per app, updated with the site. Every field is described in [SCHEMA.md](SCHEMA.md).
- **[reports/](reports/)**: frozen snapshots behind our [open-source APK report](https://h5.2113.net/reports/open-source-apk-report-2026.html). They don’t change after publication, so the report’s numbers can be reproduced from them.
- **Version 1.0** (2026-10-01) is tagged `v1.0`. To cite the data, use “Cite this repository” on GitHub ([CITATION.cff](CITATION.cff)).
- **Limits:** a matching hash and signing certificate show that a file is the developer’s or repository’s original, not that the app is safe. The tracker scan finds known third-party libraries in the code; it doesn’t see what an app sends. The apps are the ones we host, chosen because people look for them, not a random sample.
- **Corrections** are welcome: see [CONTRIBUTING.md](CONTRIBUTING.md).

## About this list

2113 Apps doesn’t modify, rebuild or re-sign any app. A tracker scan shows which known tracker SDKs are in the code, not what an app sends; “no known trackers found” means none of the Exodus Privacy signatures matched. Developers can add a “Get it on 2113 Apps” badge to their README: see [For developers](https://h5.2113.net/developers.html). Corrections: hello@2113.net.

## License

The text and data in this repository are licensed under [CC BY 4.0](LICENSE). You may share and adapt them, commercially too, as long as you credit 2113 Apps with a link to https://h5.2113.net/. Each app is under its own licence, listed with it.
