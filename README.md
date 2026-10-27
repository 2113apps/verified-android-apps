# Verified Open-Source Android Apps

Open-source Android apps whose APKs are hosted and checked by [2113 Apps](https://h5.2113.net/). Every file is the release the developer published, or F-Droid’s build of it, unchanged. Before it goes up, its signing key is checked; wherever a hash is published, in the signed repository index, on the project’s GitHub release or on the developer’s website, the file must match it; and its code is scanned for trackers. Each entry links to the app’s page, which lists the file’s SHA-256, the signer’s fingerprint, the permissions and the CPU types. [How the checks work](https://h5.2113.net/how-we-check.html).

298 apps. This list is generated from the site and updated when the site is. The version, SHA-256 and signer of every file are in [apps.json](apps.json) and [apps.csv](apps.csv) (fields: [SCHEMA.md](SCHEMA.md)), and [VERIFY.md](VERIFY.md) shows how to check an APK you downloaded.

## Contents

- [Data, reports and citation](#data-reports-and-citation)
- [Topics and comparisons](#topics-and-comparisons)
- [Guides](#guides)
- [Root & Mods](#root--mods) (13)
- [Customization](#customization) (12)
- [Network & Privacy](#network--privacy) (43)
- [Media](#media) (45)
- [System Tools](#system-tools) (58)
- [Cloud & Self-Hosted](#cloud--self-hosted) (6)
- [Productivity](#productivity) (42)
- [Reading & Maps](#reading--maps) (10)
- [Games: Strategy Games](#games-strategy-games) (13)
- [Games: Sandbox Games](#games-sandbox-games) (2)
- [Games: Adventure & RPG](#games-adventure--rpg) (12)
- [Games: Simulation Games](#games-simulation-games) (4)
- [Games: Racing Games](#games-racing-games) (2)
- [Games: Educational Games](#games-educational-games) (1)
- [Games: Puzzle & Arcade](#games-puzzle--arcade) (14)
- [Games: PC Emulators](#games-pc-emulators) (3)
- [Games: Minecraft Launchers](#games-minecraft-launchers) (4)
- [Games: Console Emulators](#games-console-emulators) (12)
- [Games: Game Streaming](#games-game-streaming) (2)

## Topics and comparisons

- [Obtainium Alternatives for Android](https://h5.2113.net/topics/app-updaters/): Four open-source alternatives to Obtainium for installing and updating Android apps outside Google Play. Sources, silent installs and tracking flags compared.
- [Heroes 2 & 3, Caesar III, RCT2 and More on Android](https://h5.2113.net/topics/classic-pc-games-android/): fheroes2, VCMI, Julius, OpenRCT2 and OpenTTD rebuild five classic PC strategy and building games as open source for Android. What each needs, and how to set it up.
- [Android Customization Apps: Open-Source Picks](https://h5.2113.net/topics/customization/): Six open-source apps to customize Android, from launchers and a desktop-style taskbar to system-wide icon packs and Quick Settings styling. What each needs.
- [Fossify Apps: Simple Mobile Tools Alternatives](https://h5.2113.net/topics/fossify-apps/): The Fossify apps that carry on Simple Mobile Tools, from gallery, dialer and SMS to keyboard and launcher. None requests internet access; all eleven share one key.
- [Android Games With No Ads: 15 Open-Source Picks](https://h5.2113.net/topics/games-without-ads/): Fifteen open-source Android games, from strategy and roguelikes to puzzles, pinball and racing, whose files contain no ad libraries, no billing code and no trackers.
- [LSPosed Modules List: 9 Open-Source Picks](https://h5.2113.net/topics/lsposed-modules/): Nine open-source LSPosed and Xposed modules, from fixing old app installs to icon packs and freezing background apps. Xposed API confirmed in every APK, no trackers.
- [Minecraft Java Launchers for Android](https://h5.2113.net/topics/minecraft-java-launchers/): Four open-source launchers that run Minecraft Java Edition on Android, Amethyst, Zalith Launcher 2, FCL and MojoLauncher, compared on versions, mods and devices.
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
- [Back Up Android Photos to a PC with Syncthing](https://h5.2113.net/guides/back-up-android-photos-to-pc-syncthing.html): Copy new photos from your Android phone to a Windows, Mac or Linux computer over Wi-Fi with Syncthing-Fork, and keep them when you delete them on the phone.
- [How to Block Ads on Android Without Root](https://h5.2113.net/guides/block-ads-android-without-root.html): Three ways to block ads on Android without root: an ad-blocking Private DNS, a blocker app like AdAway, NetGuard or Rethink, or a browser add-on, and what none can block.
- [“Built for an Older Version of Android”: What It Means](https://h5.2113.net/guides/built-for-older-android.html): Why Android shows the “built for an older version of Android” warning, why Android 14 and later refuse to install some old apps, and the ways around each.
- [How to Extract boot.img From an OTA or payload.bin](https://h5.2113.net/guides/extract-boot-img.html): Get the stock boot.img or init\_boot.img you need for rooting: which image to use, why the build must match, and how to extract it on the phone or on a computer.
- [Add Your Own Game Files to Android Game Engines](https://h5.2113.net/guides/game-files-for-android-engines.html): Open-source engines such as VCMI and OpenRCT2 run games you already own. Which files each one needs, where they go on Android, and why Android/data is off limits.
- [Move Google Authenticator Codes to Aegis](https://h5.2113.net/guides/google-authenticator-to-aegis.html): Export your two-factor accounts from Google Authenticator as QR codes and scan them into Aegis: the steps, what can’t move, and how to back up Aegis afterwards.
- [Move Google Password Manager Passwords to KeePassDX](https://h5.2113.net/guides/google-password-manager-to-keepassdx.html): Export Google Password Manager passwords, turn the CSV into an encrypted KeePass file with KeePassXC, and use it in KeePassDX on Android, plus why passkeys stay behind.
- [How to Root Android: Unlock the Bootloader and Magisk](https://h5.2113.net/guides/how-to-root-android.html): Rooting Android step by step: what unlocking the bootloader wipes and breaks, fastboot and Samsung steps, patching boot or init\_boot with Magisk, and undoing it.
- [How to Start Shizuku: Wireless Debugging, PC or Root](https://h5.2113.net/guides/how-to-start-shizuku.html): Three ways to start Shizuku (root, wireless debugging on Android 11+, or a computer), what to redo after a reboot, and fixes for when it won't start or keeps stopping.
- [How to Unlock the Bootloader on Android, by Brand](https://h5.2113.net/guides/how-to-unlock-bootloader.html): Unlocking an Android bootloader the official way, brand by brand: OEM unlocking, fastboot, Xiaomi’s HyperOS application, Motorola and Sony codes, and what you lose.
- [How to Install APKs on Android TV and TV Boxes](https://h5.2113.net/guides/install-apk-android-tv.html): Allow unknown apps, get the file onto the TV by browser, USB or adb, and fix the two classic problems: 32-bit TV boxes and apps missing from the home screen.
- [How to Install an APK on Android, Step by Step](https://h5.2113.net/guides/install-apk-android.html): Install an APK on Android: allow the app that opens it, tap Install, and fix the usual errors. Covers Play Protect, Samsung Auto Blocker, adb and older Android.
- [How to Install LSPosed (Vector) and Enable Modules](https://h5.2113.net/guides/install-lsposed.html): Three things are called LSPosed now: the old 1.9.2, the closed-source LSPosed 2.x and the open-source fork Vector. Which to install, Zygisk, modules and fixes.
- [How to Install XAPK, APKS and APKM Files on Android](https://h5.2113.net/guides/install-xapk-apks-apkm.html): XAPK, APKS and APKM files hold one app split into several APKs. What is in each, how to install them with App Manager or adb, and why “App not installed” appears.
- [KernelSU LKM vs GKI: Why LKM, and How to Install It](https://h5.2113.net/guides/kernelsu-lkm-vs-gki.html): Since v3.0, KernelSU officially supports only LKM mode. What LKM and GKI mean, how to check support and match your KMI, and how to install KernelSU with the manager.
- [Mindustry Review: Is It Worth Playing on Android?](https://h5.2113.net/guides/mindustry-review.html): We haven’t played it ourselves: what Steam and Google Play players, the press and the developer say about Mindustry, and what that means on an Android phone.
- [How to Play Minecraft Java Edition on Android](https://h5.2113.net/guides/minecraft-java-on-android.html): Open-source launchers run Minecraft Java Edition on Android. What you need (you must own the game), which Java each version needs, and the first launch, step by step.
- [App Not Installed as Package Conflicts: How to Fix](https://h5.2113.net/guides/package-conflicts.html): What Android’s “package conflicts with an existing package” error means: a different signing key, a copy kept for another user, or a clash with another app, and each fix.
- [PojavLauncher Is Discontinued: What to Use Instead](https://h5.2113.net/guides/pojavlauncher-discontinued.html): PojavLauncher stopped in 2025 and its last APK can’t run newer Minecraft. Which launcher to use instead, and how to bring your worlds and controls along.
- [How to Remove Bloatware Without Root (Shizuku, Canta)](https://h5.2113.net/guides/remove-bloatware-without-root.html): Remove preinstalled apps without root using Shizuku and Canta: what it really does, which apps are risky, how to bring one back, and what changes in Android 17.
- [RetroArch Cores on Android: Which Core to Use](https://h5.2113.net/guides/retroarch-cores-android.html): Which RetroArch core to use for each console on Android, how to download and update cores, where they are stored, which need BIOS files, and why some don’t show up.
- [Shattered Pixel Dungeon Review: Worth It on Android?](https://h5.2113.net/guides/shattered-pixel-dungeon-review.html): We haven’t played it ourselves: what Google Play and Steam players, the press and the developer say about Shattered Pixel Dungeon, and who the free roguelike suits.
- [Termux Commands: The Basics, With Examples](https://h5.2113.net/guides/termux-commands.html): The Termux commands to know first: pkg for packages, termux-setup-storage, SSH on port 8022, Termux:API, volume-key shortcuts, and what to run when something fails.
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
- **[KernelSU Next](https://h5.2113.net/apps/kernelsu-next.html)**: The manager app for KernelSU Next, a kernel-based root solution forked from KernelSU. It patches your boot image, grants root per app and manages modules.  
  Unlocked bootloader · supported kernel · Android 8+ · no known trackers found · GPL-3.0 · [source](https://github.com/KernelSU-Next/KernelSU-Next)
- **[KnoxPatch](https://h5.2113.net/apps/knoxpatch.html)**: Gets Samsung apps and features working again on a rooted Galaxy phone by hooking the checks that fail after rooting.  
  Samsung Galaxy · root + LSPosed · no known trackers found · GPL-3.0-or-later · [source](https://github.com/salvogiangri/KnoxPatch)
- **[Magisk](https://h5.2113.net/apps/magisk.html)**: The best-known way to root Android: patch your phone’s boot image with the Magisk app, flash it, and get root access, modules and Zygisk without touching the system partition.  
  Unlocked bootloader · fastboot · Android 7.0+ · no known trackers found · GPL-3.0 · [source](https://github.com/topjohnwu/Magisk)
- **[MMRL](https://h5.2113.net/apps/mmrl.html)**: A module manager for rooted phones: browse repositories, read what a module contains, and install, update or remove it through your root solution’s own installer.  
  Root with Magisk, KernelSU or APatch for installing · no known trackers found · GPL-3.0-only · [source](https://github.com/MMRLApp/MMRL)
- **[Neo Backup](https://h5.2113.net/apps/neo-backup.html)**: Back up your apps together with their data on a rooted phone, and put them back later or on a fresh install: one app at a time, in batches or on schedules, encrypted if you want.  
  Root · Android 8.0+ · no known trackers found · AGPL-3.0-only · [source](https://github.com/NeoApplications/Neo-Backup)
- **[NoStorageRestrict](https://h5.2113.net/apps/nostoragerestrict.html)**: Lets apps pick the Download and Android folders through the system folder picker again, which Android 11 blocked.  
  Root + LSPosed · Android 11+ · no known trackers found · GPL-3.0-only · [source](https://github.com/Xposed-Modules-Repo/com.github.dan.nostoragerestrict)
- **[Pengeek](https://h5.2113.net/apps/pengeek.html)**: A large set of system tweaks for Xiaomi phones on HyperOS, and the successor to CustoMIUIzer.  
  HyperOS · Android 15+ · root + Vector or LSPosed 2 · no known trackers found · GPL-3.0 · [source](https://github.com/MonwF/customiuizer)

## Customization

- **[Arcticons](https://h5.2113.net/apps/arcticons.html)**: Over 15,000 hand-drawn, white line icons that restyle your home screen in one go, for launchers that accept icon packs, plus clock widgets and a wallpaper collection.  
  No root · a launcher that supports icon packs · no known trackers found · GPL-3.0-only · [source](https://github.com/Arcticons-Team/Arcticons)
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
- **[Olauncher](https://h5.2113.net/apps/olauncher.html)**: A home screen with the time, the date and up to eight app names in plain text, and no icons. Swipe left or right to open two apps you pick; type to find the rest.  
  Android 7.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/tanujnotes/Olauncher)
- **[Taskbar](https://h5.2113.net/apps/taskbar.html)**: A PC-style start menu and a bar of recent apps that sit on top of any screen, plus floating app windows and a desktop mode for when your phone drives an external display.  
  No root · overlay permission · Android 5.0+ · no known trackers found · Apache-2.0 · [source](https://github.com/farmerbb/Taskbar)
- **[Video Live Wallpaper](https://h5.2113.net/apps/video-live-wallpaper.html)**: Turn a video or animated GIF already on your phone into a silent looping wallpaper, then choose its speed and whether to crop it to fill the screen or fit the whole frame.  
  No root · Android 8.0+ · a local video or GIF · no known trackers found · Apache-2.0 · [source](https://github.com/codeg0blin/video-live-wallpaper)
- **[µLauncher](https://h5.2113.net/apps/mulauncher.html)**: A home screen with just the date, the time and your wallpaper. Apps open with swipes, taps, drawn shapes or the volume keys, and everything else is a searchable list.  
  Android 5.0+ · no known trackers found · MIT · [source](https://github.com/jrpie/Launcher)

## Network & Privacy

- **[AdAway](https://h5.2113.net/apps/adaway.html)**: A system-wide ad blocker. With root it rewrites the hosts file; without root it filters DNS requests through a local VPN. Either way, ads are blocked before they load.  
  Root, or VPN mode without root · Android 8.0+ · tracker code found: Sentry · GPL-3.0-only · [source](https://github.com/AdAway/AdAway)
- **[Aegis Authenticator](https://h5.2113.net/apps/aegis-authenticator.html)**: Two-factor login codes in an encrypted vault that never goes online. It imports from Google Authenticator and over a dozen other apps, and backs up to a folder you choose.  
  Android 6.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/beemdevelopment/Aegis)
- **[AIS-catcher](https://h5.2113.net/apps/ais-catcher.html)**: Turns your phone and a cheap RTL-SDR dongle into a portable AIS receiver for tracking ships, even offline.  
  RTL-SDR dongle · USB OTG · no known trackers found · GPL-3.0-only · [source](https://github.com/jvde-github/AIS-catcher-for-Android)
- **[Brave](https://h5.2113.net/apps/brave.html)**: A Chromium-based web browser that blocks most ads and trackers out of the box, with its own search engine, optional rewards, a crypto wallet and a paid VPN.  
  Android 10+ · 64-bit ARM phone · no known trackers found · MPL-2.0 · [source](https://github.com/brave/brave-browser)
- **[DuckDuckGo](https://h5.2113.net/apps/duckduckgo.html)**: DuckDuckGo’s web browser for Android: its private search, tracker blocking, a Fire Button that clears your data, and optional tracker blocking for your other apps.  
  Android 9+ · no known trackers found · Apache-2.0 · [source](https://github.com/duckduckgo/Android)
- **[Ente Auth](https://h5.2113.net/apps/ente-auth.html)**: An open-source authenticator for two-factor codes. Use it offline with no account, or with an Ente account so the codes sync, end-to-end encrypted, to your other phones, computers and the web.  
  Android 7.0+ · account optional · tracker code found: Sentry · AGPL-3.0-only · [source](https://github.com/ente-io/ente/)
- **[Exodus](https://h5.2113.net/apps/exodus.html)**: Find out which tracking libraries are inside the apps you have installed. Exodus looks each one up in the reports of Exodus Privacy, a French non-profit.  
  No root · internet · Android 6.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/Exodus-Privacy/exodus-android-app)
- **[FireWall Blocks](https://h5.2113.net/apps/firewall-blocks.html)**: Blocks Wi-Fi or mobile data per app without root, through Shizuku or a local VPN.  
  Shizuku, or nothing in VPN mode · no known trackers found · MIT · [source](https://github.com/shynoiddev/FireWall-Blocks)
- **[Gadgetbridge](https://h5.2113.net/apps/gadgetbridge.html)**: Use a smartwatch, fitness band, earbuds or scale without the maker’s app and account: notifications on your wrist, activity and sleep data, music controls and more, all kept on your phone.  
  No root · Android 6.0+ · a supported gadget · no known trackers found · AGPL-3.0-only · [source](https://codeberg.org/Freeyourgadget/Gadgetbridge)
- **[Intra](https://h5.2113.net/apps/intra.html)**: A one-switch app that protects your DNS lookups from tampering: it sends them encrypted over HTTPS, which gets around blocking that works by faking DNS answers.  
  No root · Android 5.0+ · no known trackers found · Apache-2.0 · [source](https://github.com/Jigsaw-Code/Intra)
- **[InviZible Pro](https://h5.2113.net/apps/invizible-pro.html)**: Tor, DNSCrypt and Purple I2P in one open-source app, with a firewall. It routes the phone’s traffic through them as a local VPN, or with root through iptables.  
  Android 5.0+ · 64-bit ARM · root optional · no known trackers found · GPL-3.0-or-later · [source](https://github.com/Gedsh/InviZible)
- **[IronFox](https://h5.2113.net/apps/ironfox.html)**: A Firefox-based browser set up for privacy out of the box: telemetry and crash reports off, uBlock Origin offered on first start, history cleared on exit, and the JavaScript compiler off for security.  
  No root · Android 8.0+ · 64-bit ARM phone · tracker code found: Mozilla Telemetry · MPL-2.0 · [source](https://gitlab.com/ironfox-oss/IronFox)
- **[KDE Connect](https://h5.2113.net/apps/kde-connect.html)**: Pair your phone with your computer over the local network to share files and the clipboard, read and answer phone notifications on the PC, and use the phone as a touchpad or media remote.  
  KDE Connect on the computer · Android 6.0+ · no known trackers found · GPL-3.0-only · [source](https://invent.kde.org/network/kdeconnect-android)
- **[Keepass2Android](https://h5.2113.net/apps/keepass2android.html)**: A password manager for KeePass files that can keep your database in your own cloud storage or server, unlock it again with a few characters, and fill in passwords in apps and browsers.  
  Android 5.0+ · a KeePass database or a new one · tracker code found: OpenTelemetry (OpenCensus, OpenTracing) · GPL-3.0 · [source](https://github.com/PhilippC/keepass2android)
- **[KeePassDX](https://h5.2113.net/apps/keepassdx.html)**: Your passwords in an encrypted KeePass file that you keep wherever you like. KeePassDX fills in logins and passkeys, generates passwords and one-time codes, and never goes online.  
  No root · Android 4.4+ (passkeys: Android 14+) · no known trackers found · GPL-3.0-or-later · [source](https://github.com/Kunzisoft/KeePassDX)
- **[Kizzy](https://h5.2113.net/apps/kizzy.html)**: Shows Discord Rich Presence from your Android phone, with presets and custom statuses.  
  A Discord account · no known trackers found · GPL-3.0-only · [source](https://github.com/dead8309/Kizzy)
- **[Meshtastic](https://h5.2113.net/apps/meshtastic.html)**: The official app for Meshtastic, the open-source off-grid radio project: pair your phone with a small LoRa radio and message others on the mesh, with no mobile network or internet.  
  A Meshtastic radio · 64-bit phone · Android 8.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/meshtastic/Meshtastic-Android)
- **[Mousedroid](https://h5.2113.net/apps/mousedroid.html)**: Turns your phone into a touchpad, keyboard and numpad for a Windows or Linux PC, over USB or Wi-Fi.  
  Desktop server on the PC · no root · no known trackers found · MIT · [source](https://github.com/darusc/Mousedroid)
- **[Mullvad VPN: privacy is a universal right](https://h5.2113.net/apps/mullvad-vpn.html)**: The app for Mullvad’s paid VPN service: WireGuard connections, an account that is just a random number, and options against tracking and censorship. The app is open source; the service is €5 a month.  
  Android 9+ · Mullvad account (€5/month) · no known trackers found · GPL-3.0-or-later · [source](https://github.com/mullvad/mullvadvpn-app)
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
- **[Orbot](https://h5.2113.net/apps/orbot.html)**: Route the apps on your phone through Tor, all of them or only the ones you pick, with bridges for places where Tor is blocked. Orbot can also host onion services and help others reach Tor.  
  No root · Android 7.0+ · 64-bit ARM phone · no known trackers found · BSD-3-Clause · [source](https://github.com/guardianproject/orbot-android)
- **[PCAPdroid](https://h5.2113.net/apps/pcapdroid.html)**: See every connection your apps make, without root. PCAPdroid captures traffic through a local VPN on the phone, lets you inspect and export it, and can decrypt HTTPS.  
  No root · Android 6.0+ · no known trackers found · GPL-3.0-or-later · [source](https://github.com/emanuele-f/PCAPdroid)
- **[PCAPdroid mitm](https://h5.2113.net/apps/pcapdroid-mitm.html)**: An add-on that lets PCAPdroid decrypt HTTPS traffic on the phone, using mitmproxy.  
  The PCAPdroid app · ARM64 · no known trackers found · GPL-3.0-only · [source](https://github.com/emanuele-f/PCAPdroid-mitm)
- **[personalDNSfilter](https://h5.2113.net/apps/personaldnsfilter.html)**: A small DNS filter by Ingo Zenz: it answers lookups for blocked ad, tracker and malware domains with an empty address, filtering on the phone through a local VPN that carries only DNS.  
  No root · Android 4.2+ · Private DNS off · no known trackers found · GPL-2.0-only · [source](https://github.com/IngoZenz/personaldnsfilter)
- **[Private DNS Quick Toggle](https://h5.2113.net/apps/private-dns-quick-toggle.html)**: A Quick Settings tile that switches Android’s Private DNS between providers in one tap.  
  One-time grant via Shizuku or ADB · no known trackers found · MIT · [source](https://github.com/karasevm/PrivateDNSAndroid)
- **[Proton Authenticator](https://h5.2113.net/apps/proton-authenticator.html)**: Generate two-factor codes without an account, keep automatic backups in a local folder, and sign in to Proton only for encrypted sync. This is the separate F-Droid package.  
  Android 8.1+ · camera optional for QR codes · no known trackers found · GPL-3.0-or-later · [source](https://github.com/protonpass/android-authenticator)
- **[Proton Pass](https://h5.2113.net/apps/proton-pass.html)**: Proton’s password manager, synced to your Proton account: logins, passkeys, notes and cards, autofill, and email aliases that hide your address. F-Droid builds it without the crash reporter.  
  No root · Android 8.1+ · a Proton account · no known trackers found · GPL-3.0-or-later · [source](https://github.com/protonpass/android-pass)
- **[Proton VPN](https://h5.2113.net/apps/proton-vpn.html)**: The Proton VPN app with its free plan: one device, servers in ten countries and no data cap. This copy is F-Droid’s build, without Google’s code, and it needs a Proton account.  
  Android 8.0+ · Proton account (free) · tracker code found: Sentry · GPL-3.0-only · [source](https://github.com/ProtonVPN/android-app)
- **[Rethink: DNS + Firewall + VPN](https://h5.2113.net/apps/rethink-dns.html)**: Encrypted DNS with optional block lists, a firewall that decides which apps may go online, and a WireGuard client, all from one local VPN on the phone. No root needed.  
  Android 6.0+ · 64-bit ARM · no known trackers found · Apache-2.0 · [source](https://github.com/celzero/rethink-app)
- **[Shadowsocks](https://h5.2113.net/apps/shadowsocks.html)**: The Shadowsocks project’s own Android client. Add your server or a subscription link, then send all apps, or only the ones you choose, through an encrypted proxy.  
  No root · a Shadowsocks server · Android 6.0+ · no known trackers found · GPL-3.0-or-later · [source](https://github.com/shadowsocks/shadowsocks-android)
- **[sing-box](https://h5.2113.net/apps/sing-box.html)**: The sing-box project’s own Android app: it runs a sing-box configuration you supply, from a file, a QR code or a web address, and routes your apps through it with Android’s VPN service.  
  No root · Android 7.0+ · your own sing-box config · no known trackers found · GPL-3.0-or-later · [source](https://github.com/SagerNet/sing-box)
- **[Tailscale](https://h5.2113.net/apps/tailscale.html)**: Connect your phone, computers and servers into one private network, a tailnet, built on WireGuard. Once you sign in, your devices can reach each other wherever they are.  
  No root · an account or Headscale · Android 8.0+ · no known trackers found · BSD-3-Clause · [source](https://github.com/tailscale/tailscale-android)
- **[Tor Browser](https://h5.2113.net/apps/tor-browser.html)**: Browse privately through the Tor network: Tor Browser hides your location from the sites you visit, clears everything when you close it, and connects through bridges where Tor is blocked.  
  No root · Android 5.0+ · 64-bit ARM phone · tracker code found: Mozilla Telemetry, Sentry · MPL-2.0 · [source](https://gitlab.torproject.org/tpo/applications/tor-browser.git)
- **[Ungoogled Chromium](https://h5.2113.net/apps/ungoogled-chromium.html)**: Google’s Chromium browser with the parts that talk to Google taken out: no Google sync, no Safe Browsing lookups, no usage statistics, while the browser stays as close to Chromium as possible.  
  No root · Android 10+ · 64-bit ARM phone · no known trackers found · GPL-3.0 · [source](https://github.com/ungoogled-software/ungoogled-chromium-android)
- **[v2rayNG](https://h5.2113.net/apps/v2rayng.html)**: An open-source proxy client built on Xray-core. Add your own server or subscription and it routes the phone’s traffic, or chosen apps, through it as a VPN.  
  Android 7.0+ · 64-bit ARM · your own server · no known trackers found · GPL-3.0 · [source](https://github.com/2dust/v2rayNG)
- **[VPN Hotspot](https://h5.2113.net/apps/vpn-hotspot.html)**: Normally, devices on your phone’s hotspot don’t go through its VPN. VPN Hotspot routes them through it, and lets you see and block connected devices. Root required.  
  Root · Android 10+ · 64-bit ARM · tracker code found: Google CrashLytics, Google Firebase Analytics · Apache-2.0 · [source](https://github.com/Mygod/VPNHotspot)
- **[WG Tunnel](https://h5.2113.net/apps/wg-tunnel.html)**: A WireGuard and AmneziaWG client that turns tunnels on and off by itself depending on the network you’re on, with a kill switch, split tunneling and encrypted DNS.  
  No root · a WireGuard config · no known trackers found · MIT · [source](https://github.com/wgtunnel/android)
- **[Windscribe](https://h5.2113.net/apps/windscribe.html)**: The Windscribe VPN app: pick a server location, connect with WireGuard, IKEv2 or OpenVPN, and get a monthly free allowance with an account. This is F-Droid’s build, without Google services.  
  Windscribe account · Android 7.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/Windscribe/Android-App)
- **[WireGuard](https://h5.2113.net/apps/wireguard.html)**: The official app for WireGuard, the fast, modern VPN protocol: add your tunnel from a QR code, a file or by hand, and turn it on from the app or a Quick Settings tile. The direct-download version.  
  No root · Android 7.0+ · a WireGuard server or config · no known trackers found · Apache-2.0 · [source](https://git.zx2c4.com/wireguard-android/)

## Media

- **[AntennaPod](https://h5.2113.net/apps/antennapod.html)**: A podcast manager and player with no ads and no account: subscribe to any podcast by its feed, download or stream episodes, and control exactly when downloads happen.  
  No root · Android 6.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/AntennaPod/AntennaPod)
- **[ArchiveTune](https://h5.2113.net/apps/archivetune.html)**: A YouTube Music player built on Metrolist’s framework, with quick switching between accounts, local files alongside streaming, podcasts, and detailed audio and lyrics options.  
  No root · Android 8.0+ · no known trackers found · GPL-3.0 · [source](https://github.com/rukamori/ArchiveTune)
- **[Audio Recorder](https://h5.2113.net/apps/audio-recorder.html)**: Dmytro Ponomarenko’s open-source recorder: voice notes, lectures or meetings in M4A, WAV or 3GP with a live waveform, and on Android 10 and later what other apps are playing. Fully offline.  
  Android 8.0+ · no account · no known trackers found · Apache-2.0 · [source](https://github.com/Dimowner/AudioRecorder)
- **[Audiobookshelf](https://h5.2113.net/apps/audiobookshelf.html)**: Listen to the audiobooks and podcasts on your own Audiobookshelf server, download them for offline listening, read ebooks, and keep your place in sync between devices.  
  No root · Android 7.0+ · your own Audiobookshelf server · no known trackers found · GPL-3.0-only · [source](https://github.com/advplyr/audiobookshelf-app)
- **[Auxio](https://h5.2113.net/apps/auxio.html)**: A music player for your own files that reads tags properly, plays albums without gaps and evens out the volume between them. It has no internet access at all.  
  Android 7.0+ · music files on your phone · no known trackers found · GPL-3.0-only · [source](https://github.com/OxygenCobalt/Auxio)
- **[Aves Libre](https://h5.2113.net/apps/aves.html)**: A gallery for the photos and videos on your phone that also shows and edits their metadata, finds motion photos and panoramas, and maps where your pictures were taken.  
  No root · Android 7.0+ · 64-bit ARM · no known trackers found · BSD-3-Clause · [source](https://github.com/deckerst/aves)
- **[Bloomee](https://h5.2113.net/apps/bloomee.html)**: A music player that plays your local files and online streams side by side. Its online sources come from a plugin system, and it adds synced lyrics, an equalizer and Last.fm scrobbling.  
  No root · 64-bit phone · no known trackers found · GPL-2.0-only · [source](https://github.com/HemantKArya/BloomeeTunes)
- **[Flow](https://h5.2113.net/apps/flow.html)**: Watch YouTube and play music from it without signing in, with recommendations worked out on your phone. An unofficial, open-source client; it isn't made by or connected with YouTube.  
  Android 8.0+ · 64-bit ARM · no known trackers found · GPL-3.0-only · [source](https://github.com/Flow-Tube/Flow)
- **[Fossify Gallery](https://h5.2113.net/apps/fossify-gallery.html)**: A photo and video gallery that stays offline: browse, edit, hide and lock your pictures, restore deleted ones from a recycle bin, and strip location data before you share.  
  No root · Android 8.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/FossifyOrg/Gallery)
- **[Fossify Music Player](https://h5.2113.net/apps/fossify-music-player.html)**: A player for the music files on your phone that carries on from Simple Music Player: browse by album, artist, genre or folder, with playlists, an equalizer and a sleep timer.  
  No root · Android 8.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/FossifyOrg/Music-Player)
- **[FreeTube Android](https://h5.2113.net/apps/freetube.html)**: The Android version of FreeTube: watch YouTube without an account, keep subscriptions, playlists and history on your phone, and organise channels into profiles.  
  No root · Android 10+ · no known trackers found · AGPL-3.0-or-later · [source](https://github.com/MarmadileManteater/FreeTubeAndroid)
- **[Gramophone](https://h5.2113.net/apps/gramophone.html)**: A Material Design player for music stored on your phone: synced lyrics down to the word, ReplayGain, playlists kept as ordinary files, and no internet access at all.  
  No root · Android 5.0+ · music files on your phone · no known trackers found · GPL-3.0-only · [source](https://github.com/FoedusProgramme/Gramophone)
- **[Gyawun Music](https://h5.2113.net/apps/gyawun-music.html)**: A light, open-source player for YouTube Music, with offline downloads, synced lyrics, an equalizer and podcasts, and no account sign-in in the app.  
  No root · 64-bit phone · Android 7.0+ · no known trackers found · GPL-3.0 · [source](https://github.com/sheikhhaziq/gyawun_music)
- **[ImageToolbox](https://h5.2113.net/apps/image-toolbox.html)**: A huge open-source image toolkit: batch resizing and conversion, hundreds of filters, EXIF editing, background removal, text recognition and PDF tools. This build has no Google services.  
  Android 7.0+ · 64-bit ARM · no known trackers found · Apache-2.0 · [source](https://github.com/T8RIN/ImageToolbox)
- **[Jellyfin](https://h5.2113.net/apps/jellyfin.html)**: The official Android app for Jellyfin, the free media server: stream your own films, series, music and audiobooks from a server you run, or download them to the phone.  
  Your own Jellyfin server · Android 5.0+ · no known trackers found · GPL-2.0-or-later · [source](https://github.com/jellyfin/jellyfin-android)
- **[Just Player](https://h5.2113.net/apps/just-player.html)**: A plain video player with no library and no ads: open a file or a streaming link and it plays, with swipe gestures, picture-in-picture, subtitle choice and audio sync for Bluetooth earphones.  
  No root · 64-bit phone · Android 6.0+ · no known trackers found · Unlicense · [source](https://github.com/moneytoo/Player)
- **[Kodi](https://h5.2113.net/apps/kodi.html)**: A media center designed for the TV screen and a remote control: organise and play your own videos, music and photos from local storage and network shares.  
  No root · 64-bit ARM · Android 5.0+ · no known trackers found · GPL-2.0-or-later · [source](https://github.com/xbmc/xbmc)
- **[Kreate](https://h5.2113.net/apps/kreate.html)**: An open-source YouTube Music client that carries on from RiMusic: stream, cache or download songs, sign in to sync your library, and play on Android Auto or a TV.  
  No root · Android 6.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/knighthat/Kreate)
- **[LibreTube](https://h5.2113.net/apps/libretube.html)**: A YouTube client with subscriptions, playlists and downloads and no Google account. Version 32.1 fetches everything straight from YouTube by default; Piped is now optional.  
  No root · no Google account · no known trackers found · GPL-3.0-or-later · [source](https://github.com/libre-tube/LibreTube)
- **[Metrolist](https://h5.2113.net/apps/metrolist.html)**: An open-source YouTube Music client: stream and download from YouTube Music, sync your library if you sign in, and get synced lyrics, an equalizer and listen-together sessions.  
  No root · YouTube Music available where you are · no known trackers found · GPL-3.0-only · [source](https://github.com/MetrolistGroup/Metrolist)
- **[mpv-android](https://h5.2113.net/apps/mpv-android.html)**: The mpv media player on Android. It plays almost any video or audio format, draws styled subtitles with libass, and lets you tune playback in mpv’s own configuration files.  
  No root · Android 6.0+ · no known trackers found · MIT · [source](https://github.com/mpv-android/mpv-android)
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
- **[Open Recorder](https://h5.2113.net/apps/open-recorder.html)**: A screen recorder for Android 10 and later that can record the sound of other apps, your microphone or both, saves MP4 files on the phone, and has no way to go online.  
  No root · Android 10+ · no known trackers found · GPL-3.0-only · [source](https://github.com/NoneBaiano/OpenRecorder)
- **[OuterTune](https://h5.2113.net/apps/outertune.html)**: A Material 3 music player that combines YouTube Music with your own music files. The version here is the last one with YouTube Music, which its maintainers no longer develop.  
  No root · Android 7.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/OuterTune/OuterTune)
- **[Photo Editor](https://h5.2113.net/apps/photo-editor.html)**: Open or take a photo, draw over it, place text, emoji and stickers, apply color effects, undo changes and save the result in the sample app for the PhotoEditor library.  
  Android 5.0+ · network for stickers and UI font · no known trackers found · MIT · [source](https://github.com/burhanrashid52/PhotoEditor)
- **[PhotonCamera](https://h5.2113.net/apps/photoncamera.html)**: An experimental camera that captures raw frames and stacks them for HDR, with manual controls.  
  ARM64 · beta · no known trackers found · GPL-3.0-or-later · [source](https://github.com/eszdman/PhotonCamera)
- **[PipePipe](https://h5.2113.net/apps/pipepipe.html)**: A fork of NewPipe with more of everything: SponsorBlock and Return YouTube Dislike, filters that hide Shorts and paid videos, gestures, a sleep timer and BiliBili support.  
  No root · 64-bit phone · tracker code found: ACRA · GPL-3.0-only · [source](https://github.com/InfinityLoop1308/PipePipe)
- **[Retro Music](https://h5.2113.net/apps/retro-music.html)**: A player for the music files on your phone, with a choice of 17 now-playing screens, crossfade, a sleep timer, a tag editor and synced lyrics from your own files, all unlocked.  
  No root · Android 7.0+ · your own music files · no known trackers found · GPL-3.0-only · [source](https://github.com/RetroMusicPlayer/RetroMusicPlayer)
- **[RootlessJamesDSP](https://h5.2113.net/apps/rootlessjamesdsp.html)**: A system-wide sound processor for phones without root: it captures what other apps play, runs it through the JamesDSP engine for EQ, bass, reverb or your own impulse responses, and plays it back.  
  No root · Shizuku or ADB once · Android 10+ · no known trackers found · GPL-3.0-or-later · [source](https://github.com/ThePBone/RootlessJamesDSP)
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
- **[Tux Paint](https://h5.2113.net/apps/tux-paint.html)**: The children’s drawing program used in schools around the world, with nearly a thousand stamps, colouring-book pages, sound effects and dozens of Magic tools. No ads, no purchases, no internet.  
  Android 5.0+ · 64-bit ARM · no known trackers found · GPL-2.0-or-later · [source](https://github.com/tux4kids/Tuxpaint-Android)
- **[VIVI Music](https://h5.2113.net/apps/vivi.html)**: A YouTube Music client that puts its effort into looks: colors that follow the album art, animated backdrops, karaoke-style lyrics, plus downloads and Android Auto.  
  No root · no known trackers found · GPL-3.0-only · [source](https://github.com/vivizzz007/vivi-music)
- **[VLC](https://h5.2113.net/apps/vlc.html)**: The open-source player that plays almost anything: video and audio files in nearly every format, network streams, DVD images and the shared folders on your network.  
  No root · 64-bit phone · Android 4.2+ · no known trackers found · GPL-3.0-only · [source](https://code.videolan.org/videolan/vlc-android)
- **[Volume Manager](https://h5.2113.net/apps/volume-manager.html)**: Gives each app its own volume, from its own screen or a replacement volume popup.  
  Shizuku · Android 13+ · no known trackers found · GPL-2.0-only · [source](https://github.com/yume-chan/VolumeManager)
- **[YTDLnis](https://h5.2113.net/apps/ytdlnis.html)**: A full-featured Android front end for yt-dlp: queue and schedule downloads, trim by timestamp or chapter, embed subtitles and metadata, or run your own yt-dlp commands.  
  No root · 64-bit phone · Android 7.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/deniscerri/ytdlnis)

## System Tools

- **[Accrescent](https://h5.2113.net/apps/accrescent.html)**: A small app store that checks every app it installs against a signing key recorded in advance, needs no account and updates its apps in the background. Still in alpha, with about forty apps.  
  No root · Android 10+ · no account · no known trackers found · Apache-2.0 · [source](https://github.com/accrescent/accrescent)
- **[Activity Launcher](https://h5.2113.net/apps/activity-launcher.html)**: Open the screens apps don’t show you: hidden settings pages and other activities, launched directly or pinned to your home screen as shortcuts.  
  No root · Android 4.1+ · no known trackers found · ISC · [source](https://github.com/butzist/ActivityLauncher)
- **[Amaze File Manager](https://h5.2113.net/apps/amaze-file-manager.html)**: An open-source Material Design file manager with tabs, a root explorer, AES file encryption, an app manager that backs up APKs, network shares and a built-in FTP server.  
  No root needed · Android 6.0+ · tracker code found: ACRA · GPL-3.0-only · [source](https://github.com/TeamAmaze/AmazeFileManager)
- **[Androoster](https://h5.2113.net/apps/androoster.html)**: A toolbox of on/off root tweaks for CPU, memory, kernel, I/O and network settings.  
  Root + BusyBox · no known trackers found · Apache-2.0 · [source](https://github.com/cioccarellia/androoster)
- **[APK Extractor](https://h5.2113.net/apps/apk-extractor.html)**: Copy the APK of any app on your phone to a folder you choose, one app or many at once. Apps that come as split APKs are saved as one .apks archive, so the backup can be reinstalled.  
  No root · Android 10+ · no known trackers found · GPL-3.0-or-later · [source](https://github.com/pgxor/com.vadhod.apkextractor)
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
- **[AVNC](https://h5.2113.net/apps/avnc.html)**: Control a computer from your phone: AVNC connects to any VNC server, on your network or through an SSH tunnel, with touch gestures, a bar of extra keys and clipboard sync.  
  No root · Android 5.0+ · a VNC server · no known trackers found · GPL-3.0-or-later · [source](https://github.com/gujjwal00/avnc)
- **[Binary Eye](https://h5.2113.net/apps/binary-eye.html)**: A barcode scanner without ads: point the camera at a QR code, barcode or Data Matrix, see exactly what it contains, then open, copy or act on it, or create codes of your own.  
  No root · Android 5.0+ · a camera · no known trackers found · MIT · [source](https://github.com/markusfisch/BinaryEye)
- **[Canta](https://h5.2113.net/apps/canta.html)**: Remove the apps your phone maker pre-installed, without root. Canta works through Shizuku, marks which apps are risky to remove, and can put system apps back.  
  Shizuku · Android 9+ · no known trackers found · LGPL-3.0-or-later · [source](https://github.com/samolego/Canta)
- **[ConnectBot](https://h5.2113.net/apps/connectbot.html)**: Log in to your servers from the phone: SSH with keys or passwords, Mosh for flaky connections, port forwarding and jump hosts. This is the open-source build, which needs no Google Play services.  
  Android 7.0+ · a server to connect to · no known trackers found · Apache-2.0 · [source](https://github.com/connectbot/connectbot)
- **[Current Activity](https://h5.2113.net/apps/current-activity.html)**: A small tool for developers and tinkerers: it shows the package name and activity class of whatever is on screen, in a floating window you can move and copy from.  
  No root · usage access · Android 7.0+ · no known trackers found · GPL-3.0-or-later · [source](https://github.com/codehasan/Current-Activity)
- **[Droid-ify](https://h5.2113.net/apps/droid-ify.html)**: A tidier way to use F-Droid: browse and install from F-Droid, IzzyOnDroid and your own repositories, keep apps updated in the background, and install without prompts through Shizuku or root.  
  No root needed · Android 6.0+ · no known trackers found · GPL-3.0-or-later · [source](https://github.com/Droid-ify/client)
- **[DSU Sideloader](https://h5.2113.net/apps/dsu-sideloader.html)**: A front end for Android’s Dynamic System Updates: pick a GSI file and boot it as a temporary guest system next to your own, then reboot back to your phone’s system.  
  Android 10+ · ADB, Shizuku or root · unlock for most GSIs · no known trackers found · Apache-2.0 · [source](https://github.com/VegaBobo/DSU-Sideloader)
- **[Edge Seek](https://h5.2113.net/apps/edge-seek.html)**: Turns the edges of your screen into sliders for volume and brightness, with a dimmer below the minimum brightness.  
  No root · no known trackers found · Apache-2.0 · [source](https://github.com/LSafer/edgeseek)
- **[F-Droid Basic](https://h5.2113.net/apps/f-droid.html)**: The official app for F-Droid, the catalogue of free and open-source Android apps. Version 2.0 is a full redesign that updates your apps in the background.  
  Android 7.0+ · tracker code found: ACRA · GPL-3.0-or-later · [source](https://gitlab.com/fdroid/fdroidclient)
- **[FakeTraveler](https://h5.2113.net/apps/faketraveler.html)**: Pick a point on a map and FakeTraveler reports it to your phone as its location, using Android’s own mock-location option, to test apps or keep your real position to yourself.  
  No root · Android 5.0+ · Developer options · no known trackers found · GPL-3.0-or-later · [source](https://github.com/mcastillof/FakeTraveler)
- **[Files](https://h5.2113.net/apps/files-shortcut.html)**: Put Android’s built-in file browser in your launcher. This 0.2 MB shortcut opens DocumentsUI in browsing mode; it is not another file manager and never reads your files itself.  
  Android 8.0+ · a working system DocumentsUI app · no known trackers found · Apache-2.0 · [source](https://github.com/surf5726/documentsui-shortcut)
- **[Flicky](https://h5.2113.net/apps/flicky.html)**: An app store for open-source apps that you can use with a TV remote. It browses F-Droid, IzzyOnDroid and other repositories, and installs and updates apps on Android TV and Google TV.  
  No root · Android 6.0+ · made for TV · no known trackers found · GPL-3.0-only · [source](https://github.com/mlm-games/flicky)
- **[Florid](https://h5.2113.net/apps/florid.html)**: A redesigned client for browsing, installing and updating apps from F-Droid and other repositories you add. It sends a daily usage ping, which you can switch off.  
  No root · ARM64 · Android 7.0+ · no known trackers found · GPL-3.0 · [source](https://github.com/Nandanrmenon/florid)
- **[Fossify File Manager](https://h5.2113.net/apps/fossify-file-manager.html)**: An open-source file manager that carries on from Simple File Manager: favourites, search, ZIP archives, a storage analyser, locks for hidden files, and root access if you have it.  
  No root needed · all files access · Android 8.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/FossifyOrg/File-Manager)
- **[Geto](https://h5.2113.net/apps/geto.html)**: Set system settings for one app: Geto applies them when it launches that app and restores them from a notification afterwards. Its author built it to switch developer options off for a banking app.  
  Android 7.0+ · adb to grant one permission · no known trackers found · GPL-3.0-only · [source](https://github.com/JackEblan/Geto)
- **[GitNex](https://h5.2113.net/apps/gitnex.html)**: Manage your Forgejo or Gitea server from the phone: browse repositories and files, work through issues and pull requests, read diffs and get notifications, for Codeberg or your own instance.  
  No root · a Forgejo or Gitea server · Android 8.0+ · tracker code found: ACRA · GPL-3.0-only · [source](https://codeberg.org/gitnex/GitNex)
- **[Hail](https://h5.2113.net/apps/hail.html)**: Switch off the apps you rarely use instead of uninstalling them: Hail disables, hides or suspends them, and brings them back with a tap when you need them.  
  Shizuku, root or device owner · Android 6.0+ · no known trackers found · GPL-3.0-or-later · [source](https://github.com/aistra0528/Hail)
- **[Install with Options](https://h5.2113.net/apps/install-with-options.html)**: Installs APKs with options normally reserved for adb: test-only apps, downgrades, split APKs and Android 14’s blocked old apps.  
  Shizuku or root · tracker code found: Bugsnag · MIT · [source](https://github.com/zacharee/InstallWithOptions)
- **[InstallerX Revived](https://h5.2113.net/apps/installerx-revived.html)**: A replacement for the system’s install screen that also opens split-APK bundles, installs silently when Shizuku, root or Dhizuku gives it the rights, and lets you set rules per source app.  
  No root needed · Shizuku or root for more · Android 8.0+ · no known trackers found · GPL-3.0 · [source](https://github.com/wxxsfxyzm/InstallerX-Revived)
- **[Key Mapper](https://h5.2113.net/apps/key-mapper.html)**: Turn almost any button into a shortcut: volume and side keys, gamepads, keyboards and headset buttons can trigger more than 100 actions, even with the screen off in Expert Mode.  
  No root · accessibility service · Android 8.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/keymapperorg/KeyMapper)
- **[Klick’r](https://h5.2113.net/apps/klickr-auto-clicker.html)**: An open-source auto clicker that repeats taps and gestures, or reacts to the screen: when an image, a colour, a number or some text appears, it acts.  
  No root · Android 7.0+ · accessibility service · no known trackers found · GPL-3.0 · [source](https://github.com/Nain57/Smart-AutoClicker)
- **[LibreTorrent](https://h5.2113.net/apps/libretorrent.html)**: A torrent client without ads or a search engine: open .torrent files, magnet links or your own RSS feeds, pick the files you want, stream while downloading, and limit it to Wi-Fi or charging.  
  No root · 64-bit phone · Android 7.0+ · tracker code found: ACRA · GPL-3.0-or-later · [source](https://gitlab.com/proninyaroslav/libretorrent)
- **[LocalSend](https://h5.2113.net/apps/localsend.html)**: An open-source AirDrop alternative that works across Android, Windows, macOS, Linux and iOS: pick a nearby device on the same network and send files or text directly.  
  No root · same local network · Android 7.0+ · no known trackers found · Apache-2.0 · [source](https://github.com/localsend/localsend)
- **[Material Files](https://h5.2113.net/apps/material-files.html)**: A clean, open-source file manager in Material Design: open and create archives, browse network shares, and reach files ordinary apps can’t, with root or, since version 1.7.5, Shizuku.  
  No root needed · Android 6.0+ · no known trackers found · GPL-3.0-or-later · [source](https://github.com/zhanghai/MaterialFiles)
- **[microG Services](https://h5.2113.net/apps/microg.html)**: An open-source stand-in for Google Play services, for custom ROMs without Google’s apps. It handles push notifications, location and Google sign-in for the apps that need them.  
  A custom ROM that supports microG · Android 4.4+ · tracker code found: Google Analytics, Google Firebase Analytics, Google AdMob · Apache-2.0 · [source](https://github.com/microg/GmsCore)
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
- **[SAI (Split APKs Installer)](https://h5.2113.net/apps/sai.html)**: An installer for apps that come as several APK files, such as .apks, .xapk and .apkm downloads, with optional root or Shizuku installs and APK backups of installed apps.  
  No root · Android 5.0+ · root or Shizuku optional · no known trackers found · GPL-3.0-only · [source](https://github.com/Aefyr/SAI)
- **[Screen Lock](https://h5.2113.net/apps/screen-lock.html)**: A launcher icon that acts like one press of the power button. It uses Shizuku instead of Accessibility or device-admin access, and can be assigned to a launcher’s double-tap gesture.  
  Android 7.0+ · Shizuku installed, running and authorized · no known trackers found · MIT · [source](https://github.com/tiendnm/zukulock)
- **[SD Maid SE](https://h5.2113.net/apps/sd-maid-se.html)**: Finds what uninstalled apps left behind, system junk, app caches and duplicate files, and lists all of it before anything is deleted. Scanning is free; some cleaning needs the upgrade.  
  No root · Android 8.0+ · root or Shizuku optional · no known trackers found · GPL-3.0-only · [source](https://github.com/d4rken-org/sdmaid-se)
- **[Shelter](https://h5.2113.net/apps/shelter.html)**: Creates a work profile on your phone and manages it: install apps inside to keep them apart from your main apps, freeze them when you’re not using them, or run two copies of one app.  
  No root · Android 7.0+ · no other work profile · no known trackers found · GPL-3.0-only · [source](https://gitea.angry.im/PeterCxy/Shelter)
- **[Shizuku](https://h5.2113.net/apps/shizuku.html)**: Lets other apps use Android’s system APIs with the same rights as ADB. You start it with wireless debugging on Android 11+, from a computer with ADB, or with root.  
  Android 7+ · wireless debugging, a PC with ADB, or root · no known trackers found · Apache-2.0 · [source](https://github.com/RikkaApps/Shizuku)
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
- **[DAVx⁵](https://h5.2113.net/apps/davx5.html)**: Connects Android’s calendar, contacts and task apps to a CalDAV or CardDAV server you choose, such as Nextcloud, and keeps them in sync. This is the free open-source edition, from the developers.  
  No root · Android 7.0+ · a CalDAV/CardDAV server · no known trackers found · GPL-3.0-only · [source](https://github.com/bitfireAT/davx5-ose)
- **[Home Assistant](https://h5.2113.net/apps/home-assistant.html)**: The official Android app for Home Assistant, in the minimal flavor that works without Google Play services. It needs a Home Assistant server that you run yourself.  
  Your own Home Assistant server · Android 6.0+ · tracker code found: AltBeacon · Apache-2.0 · [source](https://github.com/home-assistant/android)
- **[Immich](https://h5.2113.net/apps/immich.html)**: The mobile app for Immich, a self-hosted photo and video library: back up the camera roll to a server you run, then browse, search and share it from the phone.  
  Your own Immich server · Android 8.0+ · no known trackers found · AGPL-3.0-only · [source](https://github.com/immich-app/immich)
- **[Nextcloud](https://h5.2113.net/apps/nextcloud.html)**: The official Android app for Nextcloud Files: reach the files on your own Nextcloud server, or an account with a provider, upload photos automatically and keep chosen folders synced.  
  A Nextcloud server · 64-bit phone · Android 9+ · no known trackers found · GPL-2.0-only · [source](https://github.com/nextcloud/android)
- **[Syncthing-Fork](https://h5.2113.net/apps/syncthing-fork.html)**: The community-maintained Android app for Syncthing: choose folders on your phone and keep them in sync with your computer or other phones, device to device, and decide when it’s allowed to run.  
  Android 6.0+ · Syncthing on your other devices · no known trackers found · MPL-2.0 · [source](https://github.com/researchxxl/syncthing-android)

## Productivity

- **[AnkiDroid](https://h5.2113.net/apps/ankidroid.html)**: Study with flashcards that come back just before you’d forget them. AnkiDroid opens Anki decks, syncs with Anki on your computer through AnkiWeb, and works offline.  
  Android 7.0+ · AnkiWeb account optional · tracker code found: ACRA · AGPL-3.0-or-later · [source](https://github.com/ankidroid/Anki-Android)
- **[AnySoftKeyboard](https://h5.2113.net/apps/anysoftkeyboard.html)**: An open-source on-screen keyboard that you can shape to your liking: word suggestions and next-word prediction, gesture typing, themes, and extra languages as separate packs.  
  No root · Android 6.0+ · no known trackers found · Apache-2.0 · [source](https://github.com/AnySoftKeyboard/AnySoftKeyboard)
- **[Breezy Weather](https://h5.2113.net/apps/breezy-weather.html)**: A weather app that lets you choose the source: forecasts from more than 50 weather services, with rain in the next hour, severe weather alerts, air quality, pollen and widgets.  
  No root · Android 6.0+ · no known trackers found · LGPL-3.0-only · [source](https://github.com/breezy-weather/breezy-weather)
- **[Briar](https://h5.2113.net/apps/briar.html)**: A messenger without a central server: messages travel directly between phones, over Tor when there is internet, or over the same Wi-Fi network, Bluetooth or a USB stick when there isn’t.  
  No root · Android 5.0+ · no phone number · no known trackers found · GPL-3.0-or-later · [source](https://code.briarproject.org/briar/briar)
- **[Conversations](https://h5.2113.net/apps/conversations.html)**: A messenger for the open XMPP network, also known as Jabber: pick any server, or run your own, then chat, call and share files with end-to-end encryption switched on by default.  
  No root · Android 6.0+ · an XMPP account · no known trackers found · GPL-3.0-only · [source](https://codeberg.org/iNPUTmice/Conversations)
- **[Easy Notes](https://h5.2113.net/apps/easy-notes.html)**: Keep Markdown notes, pictures and home-screen widgets on the phone, with search, themes, an app lock and a separate encrypted vault—without an account or built-in sync.  
  No root · Android 8.0+ · no known trackers found · GPL-3.0-or-later · [source](https://github.com/Kin69/EasyNotes)
- **[Element X](https://h5.2113.net/apps/element-x.html)**: The new app from Element for Matrix, the open network for encrypted chat. It replaces Element Classic, which Element is retiring at the end of 2026.  
  Android 7.0+ · 64-bit ARM · a Matrix account · tracker code found: Sentry · AGPL-3.0-or-later · [source](https://github.com/element-hq/element-x-android)
- **[Etar](https://h5.2113.net/apps/etar.html)**: A calendar app that shows whatever calendars your phone already has, Google, CalDAV or offline ones kept only on the phone, in month, week, day and agenda views, without ever going online itself.  
  No root · Android 6.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/Etar-Group/Etar-Calendar)
- **[FairEmail](https://h5.2113.net/apps/fairemail.html)**: A full email app for any IMAP or POP3 account, including Gmail and Outlook, that asks before loading images or opening links and supports PGP and S/MIME. This is the developer’s GitHub build.  
  Android 6.0+ · works without Google services · no known trackers found · GPL-3.0-or-later · [source](https://github.com/M66B/FairEmail)
- **[Fcitx5 for Android](https://h5.2113.net/apps/fcitx5.html)**: The Fcitx 5 input method framework from Linux desktops, as an Android keyboard: Chinese Pinyin, Shuangpin and Wubi built in, Japanese, Korean, Vietnamese, Rime and others as plugins.  
  No root · Android 6.0+ · 64-bit ARM · no known trackers found · LGPL-2.1-only · [source](https://github.com/fcitx5-android/fcitx5-android)
- **[FlorisBoard](https://h5.2113.net/apps/florisboard.html)**: A customisable on-screen keyboard that never goes online: a theme editor, clipboard history, emoji and extensions for layouts and themes, in an open-source app.  
  No root · Android 8.0+ · no known trackers found · Apache-2.0 · [source](https://github.com/florisboard/florisboard)
- **[Fossify Calendar](https://h5.2113.net/apps/fossify-calendar.html)**: An open-source calendar that works offline: day, week, month and year views, recurring events, reminders, built-in public holidays for 207 countries and territories, and home screen widgets.  
  No root · Android 8.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/FossifyOrg/Calendar)
- **[Fossify Clock](https://h5.2113.net/apps/fossify-clock.html)**: An open-source clock app that carries on from Simple Clock: alarms with gradual volume and an adjustable snooze, a world clock, timers, a stopwatch and widgets.  
  No root · Android 8.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/FossifyOrg/Clock)
- **[Fossify Contacts](https://h5.2113.net/apps/fossify-contacts.html)**: An open-source contacts app that carries on from Simple Contacts: groups and favourites, vCard import and export, and private contacts that other apps can’t read.  
  No root · Android 8.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/FossifyOrg/Contacts)
- **[Fossify Keyboard](https://h5.2113.net/apps/fossify-keyboard.html)**: The successor to Simple Mobile Tools’ Simple Keyboard has 44 layouts, from Portuguese to Colemak, an emoji picker and a clipboard manager, but no word suggestions.  
  No root · Android 8.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/FossifyOrg/Keyboard)
- **[Fossify Messages](https://h5.2113.net/apps/fossify-messages.html)**: An SMS and MMS app that carries on from Simple SMS Messenger: group conversations, blocking by number or keyword, scheduled messages and JSON backups, without internet access.  
  No root · Android 8.0+ · default SMS app · no known trackers found · GPL-3.0-only · [source](https://github.com/FossifyOrg/Messages)
- **[Fossify Notes](https://h5.2113.net/apps/fossify-notes.html)**: A plain notes app that carries on from Simple Notes Pro: text notes and checklists, home screen widgets, optional locks, and backups that stay on your phone.  
  No root · Android 8.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/FossifyOrg/Notes)
- **[Fossify Phone](https://h5.2113.net/apps/fossify-phone.html)**: An open-source phone app that carries on from Simple Dialer: a call log, favourites and speed dial, blocking of numbers or unknown callers, and multi-SIM support.  
  Default phone app · Android 8.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/FossifyOrg/Phone)
- **[HeliBoard](https://h5.2113.net/apps/heliboard.html)**: An on-screen keyboard that works fully offline: word suggestions from dictionaries you add, typing in several languages at once, themes, clipboard history, and one-handed and split modes.  
  No root · Android 5.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/HeliBorg/HeliBoard)
- **[Jitsi Meet](https://h5.2113.net/apps/jitsi-meet.html)**: Open-source video meetings: join from a link or a room name, on the public meet.jit.si service or on any Jitsi server. This build leaves out Google’s libraries and the analytics.  
  Android 8.0+ · 64-bit ARM · no known trackers found · Apache-2.0 · [source](https://github.com/jitsi/jitsi-meet)
- **[Joplin](https://h5.2113.net/apps/joplin.html)**: Notes and to-do lists in notebooks, written in Markdown or a rich-text editor, synced between phone and computer through a service you choose, with end-to-end encryption if you turn it on.  
  No root · Android 7.0+ · no known trackers found · AGPL-3.0-or-later · [source](https://github.com/laurent22/joplin)
- **[LibreOffice](https://h5.2113.net/apps/libreoffice.html)**: The Document Foundation’s Android app for reading office documents: Word, Excel and PowerPoint files, OpenDocument and more, rendered by LibreOffice itself, with an optional experimental editing mode.  
  No root · Android 5.0+ · 64-bit ARM · no known trackers found · MPL-2.0 · [source](https://git.libreoffice.org/core)
- **[Logseq](https://h5.2113.net/apps/logseq.html)**: An outliner that keeps every note as a plain Markdown file in a folder on your phone, with links between pages, tasks and flashcards. This is the file-based app, now called Logseq OG.  
  No root · Android 5.1+ · All files access · no known trackers found · AGPL-3.0-only · [source](https://github.com/logseq/logseq)
- **[Loop Habit Tracker](https://h5.2113.net/apps/loop-habit-tracker.html)**: Track the habits you want to build, from a daily walk to a number of pages read, and watch a strength score that forgives the odd missed day. Everything stays on your phone.  
  Android 9+ · no account · no known trackers found · GPL-3.0-only · [source](https://github.com/iSoron/uhabits)
- **[Markor](https://h5.2113.net/apps/markor.html)**: Write notes, lists and documents as plain files in a folder of your own: Markdown with a live preview, todo.txt task lists, quick notes and formats from CSV to YAML, with no account.  
  No root · Android 4.3+ · no known trackers found · Apache-2.0 · [source](https://github.com/gsantner/markor)
- **[Molly](https://h5.2113.net/apps/molly.html)**: A hardened version of Signal that uses Signal’s servers, so you chat with your Signal contacts as usual, and adds a passphrase that encrypts the app’s data and a memory wipe when it locks.  
  No root · Android 8.1+ · a phone number · no known trackers found · AGPL-3.0 · [source](https://github.com/mollyim/mollyim-android)
- **[Nekogram](https://h5.2113.net/apps/nekogram.html)**: Telegram with a few more switches: hide parts of the interface you don’t use, translate messages and whole chats with the engine you choose, and see details such as chat IDs. Uses your account.  
  No root · Android 6.0+ · a Telegram account · tracker code found: Google Firebase Analytics, Sentry · GPL-2.0 · [source](https://github.com/Nekogram/Nekogram)
- **[Offline Translator](https://h5.2113.net/apps/offline-translator.html)**: Download language packs once, then translate text, photos and documents without sending their contents to a translation server. OCR, dictionaries and transliteration also run on the phone.  
  Android 6.0+ · 64-bit ARM · internet once for language packs · no known trackers found · GPL-3.0-or-later · [source](https://github.com/DavidVentura/offline-translator)
- **[QUIK](https://h5.2113.net/apps/quik-sms.html)**: The continuation of QKSMS, the popular open-source texting app that stopped in 2023: SMS and MMS with scheduled and delayed sending, blocking, voice messages and backups, and no internet access.  
  No root · Android 6.0+ · default SMS app · no known trackers found · GPL-3.0-only · [source](https://github.com/quik-sms/quik)
- **[Session](https://h5.2113.net/apps/session.html)**: An end-to-end encrypted messenger without a phone number or email: you get an Account ID, and messages travel through a network of nodes that hides your IP address.  
  No root · Android 8.0+ · no phone number · no known trackers found · GPL-3.0 · [source](https://github.com/session-foundation/session-android)
- **[Signal](https://h5.2113.net/apps/signal.html)**: The Signal messenger in the version Signal offers on its website for phones without Google Play: one file for every device, which checks Signal’s server for updates every six hours.  
  No root · Android 6.0+ · a phone number · no known trackers found · AGPL-3.0-only · [source](https://github.com/signalapp/Signal-Android)
- **[Simple Keyboard](https://h5.2113.net/apps/simple-keyboard.html)**: Raimondas Rimkus’s deliberately small keyboard gives you keys, layouts and a few optional gestures—not prediction, emoji, GIFs or a network connection.  
  No root · Android 7.0+ · no known trackers found · Apache-2.0 · [source](https://github.com/rkkr/simple-keyboard)
- **[SimpleX Chat](https://h5.2113.net/apps/simplex-chat.html)**: A messenger without accounts: you connect to people through one-time links or QR codes, messages are end-to-end encrypted and relayed through servers you can swap for your own.  
  No root · Android 8.0+ · 64-bit ARM phone · no known trackers found · AGPL-3.0-or-later · [source](https://github.com/simplex-chat/simplex-chat)
- **[Tasks.org](https://h5.2113.net/apps/tasks-org.html)**: A to-do list app with nested subtasks, repeating tasks, start dates and reminders by time or place. It works offline, or syncs with your own CalDAV server and other services.  
  No root · Android 8.0+ · no account needed · tracker code found: OpenTelemetry (OpenCensus, OpenTracing) · GPL-3.0-only · [source](https://github.com/tasks/tasks)
- **[Telegram](https://h5.2113.net/apps/telegram.html)**: The Telegram messenger as Telegram publishes it on its website: the same chats, channels, groups and calls as the Google Play app, installed as a separate app that checks for its own updates.  
  No root · Android 6.0+ · a phone number · no known trackers found · GPL-2.0-or-later · [source](https://github.com/DrKLO/Telegram)
- **[Telegram X](https://h5.2113.net/apps/telegram-x.html)**: A second official Telegram app for Android, written from scratch on Telegram’s TDLib library, with its own interface and features. It uses your normal Telegram account and chats.  
  No root · Android 7.0+ · a Telegram account · no known trackers found · GPL-3.0 · [source](https://github.com/TGX-Android/Telegram-X)
- **[Thumb-Key](https://h5.2113.net/apps/thumb-key.html)**: A keyboard made for two thumbs: nine big keys in a 3×3 grid, the commonest letters on taps and the rest on swipes, so you learn where letters are instead of relying on word prediction.  
  No root · Android 7.0+ · no known trackers found · AGPL-3.0-only · [source](https://github.com/dessalines/thumb-key)
- **[Tomato](https://h5.2113.net/apps/tomato.html)**: A minimalist Pomodoro timer: focus for 25 minutes, take a short break, and follow your focus time in daily, weekly, monthly and yearly statistics. It never goes online.  
  Android 8.0+ · no account · no known trackers found · GPL-3.0-only · [source](https://github.com/nsh07/Tomato)
- **[Translate You](https://h5.2113.net/apps/translate-you.html)**: One translation app for many services: Mozhi, LibreTranslate, DeepL, Yandex and more, or your own server if you run one, with text from photos read on the phone.  
  No root · Android 6.0+ · internet for translating · no known trackers found · GPL-3.0-only · [source](https://github.com/you-apps/TranslateYou)
- **[Tusky](https://h5.2113.net/apps/tusky.html)**: A lightweight app for Mastodon and compatible fediverse servers: follow your timelines, post and save drafts, switch between accounts, and get notifications without Google’s push service.  
  No root · a Mastodon-compatible account · Android 7.0+ · no known trackers found · GPL-3.0-only · [source](https://codeberg.org/tusky/Tusky)
- **[Tuta Mail](https://h5.2113.net/apps/tuta-mail.html)**: The Android app for Tuta, formerly Tutanota: encrypted email, contacts and calendar from a German provider, with notifications that work without Google Play services.  
  No root · Android 8.0+ · a Tuta account · no known trackers found · GPL-3.0-or-later · [source](https://github.com/tutao/tutanota)
- **[Unexpected Keyboard](https://h5.2113.net/apps/unexpected-keyboard.html)**: A small on-screen keyboard where you swipe a key toward one of its corners to type the symbol printed there, so more characters fit on one page. Designed for programmers using Termux.  
  No root · Android 5.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/Julow/Unexpected-Keyboard)

## Reading & Maps

- **[Compass](https://h5.2113.net/apps/compass.html)**: A focused compass for phones with a magnetic sensor. Read exact bearings, switch between magnetic and true north, use sighting mode, and check whether nearby metal is disturbing the sensor.  
  Android 7.0+ · magnetic compass sensor · no known trackers found · GPL-3.0-or-later · [source](https://github.com/Kr0oked/Compass)
- **[EinkBro](https://h5.2113.net/apps/einkbro.html)**: Browse and read on an E-Ink tablet with high-contrast controls, edge taps or volume-key page turns, reader mode, vertical text and ways to save pages as EPUB or PDF.  
  Android 7.0+ · WebView · internet access · no known trackers found · GPL-3.0-or-later · [source](https://github.com/plateaukao/einkbro)
- **[Kiwix](https://h5.2113.net/apps/kiwix.html)**: Reads Wikipedia and other websites offline from downloaded ZIM archives. This is the full version, which can open ZIM files from any folder, unlike the Google Play version.  
  No root · 64-bit phone · Android 7.1+ · no known trackers found · GPL-3.0 · [source](https://github.com/kiwix/kiwix-android)
- **[KOReader](https://h5.2113.net/apps/koreader.html)**: A document reader built first for e-ink readers such as Kindle and Kobo, and available on Android: EPUB, PDF, DjVu, comics and more, with dictionaries and Calibre built in.  
  No root · 64-bit phone · Android 4.3+ · no known trackers found · AGPL-3.0-only · [source](https://github.com/koreader/koreader)
- **[Librera Reader](https://h5.2113.net/apps/librera-reader.html)**: An e-book reader for PDF, EPUB, MOBI, DjVu, FB2, comics and office documents, with read-aloud, dictionaries and online catalogues. This is the ad-free F-Droid edition, Librera FD.  
  No root · Android 7.0+ · no known trackers found · GPL-3.0-or-later · [source](https://github.com/foobnix/LibreraReader)
- **[Mihon](https://h5.2113.net/apps/mihon.html)**: An open-source reader for manga, webtoons and comics, carrying on from Tachiyomi. It keeps a library, reads your own files and records your progress on tracking sites.  
  Android 8.0+ · your own comics or content · tracker code found: Google CrashLytics, Google Firebase Analytics · Apache-2.0 · [source](https://github.com/mihonapp/mihon)
- **[MuPDF viewer](https://h5.2113.net/apps/mupdf-viewer.html)**: Artifex’s own Android viewer for its MuPDF engine: it opens PDF, XPS, EPUB, MOBI, FB2 and CBZ comic files for reading, with search and a table of contents, and does little else.  
  No root · Android 5.0+ · no known trackers found · AGPL-3.0-or-later · [source](https://github.com/ArtifexSoftware/mupdf-android-viewer)
- **[Organic Maps](https://h5.2113.net/apps/organic-maps.html)**: Offline maps from OpenStreetMap with turn-by-turn navigation for driving, cycling and walking, hiking routes, contour lines and Wikipedia articles, all usable offline once downloaded.  
  No root · Android 5.0+ · maps downloaded once · no known trackers found · Apache-2.0 · [source](https://github.com/organicmaps/organicmaps)
- **[OsmAnd~](https://h5.2113.net/apps/osmand.html)**: Offline maps and turn-by-turn navigation based on OpenStreetMap, for driving, cycling, hiking and boating. This is OsmAnd~, the build F-Droid makes from the source code.  
  No root · 64-bit phone · Android 7.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/osmandapp/Osmand)
- **[Wikipedia](https://h5.2113.net/apps/wikipedia.html)**: The Wikimedia Foundation’s own Wikipedia app: search and read articles, save them for reading offline, and edit. This copy is F-Droid’s build, without Google’s services.  
  Android 7.0+ · account optional · no known trackers found · Apache-2.0 · [source](https://github.com/wikimedia/apps-android-wikipedia)

## Games: Strategy Games

- **[Anuto TD](https://h5.2113.net/games/anuto-td.html)**: A classic endless tower defense with hand-drawn graphics: build and upgrade towers along a path, survive as many waves as you can, and chase the high score. No ads, no purchases, no permissions.  
  Android 6.0+ · portrait · no known trackers found · GPL-2.0-only · [source](https://github.com/mjaun/android-anuto)
- **[Chess for Android](https://h5.2113.net/games/chess-for-android.html)**: One chessboard for an offline engine, saved-game study, puzzles, Lichess and the old FICS server. Version 10.6.0 also adds a low-refresh e-ink theme and tap-to-move preset.  
  Android 7.0+ · internet only for Lichess or FICS · no known trackers found · MIT · [source](https://github.com/jcarolus/android-chess)
- **[DroidFish](https://h5.2113.net/games/droidfish.html)**: Analyse chess positions with Stockfish 16.1, play against it or a friend on the same phone, and keep your games in PGN files. No longer on Google Play; this is F-Droid’s build.  
  Android 4.1+ · no account · no known trackers found · GPL-3.0-only · [source](https://github.com/peterosterlund2/droidfish)
- **[Feudal Tactics](https://h5.2113.net/games/feudal-tactics.html)**: Conquer a randomly generated island of hexagons, one kingdom at a time: buy peasants, merge them into knights, build castles, and keep enough coins to pay everyone. Short games, no internet.  
  Android 7.0+ · offline · no known trackers found · GPL-3.0-or-later · [source](https://github.com/Sesu8642/FeudalTactics)
- **[fheroes2](https://h5.2113.net/games/fheroes2.html)**: Play Heroes of Might and Magic II on your phone with an engine rewritten from scratch. Bring the original game’s files or try the free demo; this is the project’s own APK.  
  Heroes II files or demo · Android 5.1+ · no known trackers found · GPL-2.0 · [source](https://github.com/ihhub/fheroes2)
- **[Freebloks](https://h5.2113.net/games/freebloks.html)**: Fit your pieces onto the board so each one touches your others only at the corners, and squeeze your opponents out. Play the computer, people on the same phone, online or over Bluetooth.  
  Android 7.0+ · no account · no known trackers found · GPL-2.0-only · [source](https://github.com/shlusiak/Freebloks-Android)
- **[Lichess](https://h5.2113.net/games/lichess.html)**: The official app of Lichess, the free and open-source chess site: play people online, play the computer offline, solve puzzles and analyse your games.  
  Android 8.0+ · 64-bit ARM · account optional · no known trackers found · GPL-3.0-or-later · [source](https://github.com/lichess-org/mobile)
- **[Ludo](https://h5.2113.net/games/ludo.html)**: Play Ludo entirely offline with two to four colors: pass one phone among up to four people, fill empty seats with bots, or mix both in the same match.  
  Android 7.0+ · 64-bit ARM · one shared device · no known trackers found · GPL-3.0-only · [source](https://github.com/sidhant947/Ludo)
- **[Mindustry](https://h5.2113.net/games/mindustry.html)**: Build drills, conveyor belts and factories that feed your turrets and units, and defend your core through campaigns on two planets. Free and open source; this is F-Droid’s build.  
  Android 5.0+ · no account · no known trackers found · GPL-3.0-or-later · [source](https://github.com/Anuken/Mindustry)
- **[Mobile Maia](https://h5.2113.net/games/mobile-maia.html)**: Play chess against an engine that plays like a person at your level rather than like a perfect machine, then review the game with Stockfish, all offline. Mobile Maia brings Maia-3 to Android.  
  No root · Android 7.0+ · no account or internet · no known trackers found · AGPL-3.0-only · [source](https://github.com/Dash1971/maia-chess-android)
- **[The Battle for Wesnoth](https://h5.2113.net/games/wesnoth.html)**: Lead fantasy armies through story campaigns or online battles, turn by turn on a hex map. On Android, only the 1.19 development branch exists, and the project calls it an alpha.  
  Android 6.0+ · ARM64 · manual data ZIP currently required · no known trackers found · GPL-2.0-or-later · [source](https://github.com/wesnoth/wesnoth)
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

- **[Andor’s Trail](https://h5.2113.net/games/andors-trail.html)**: Search for your missing brother across a large fantasy world: talk to villagers, take on quests, fight turn-based battles and improve your gear. Free and offline, with no ads or purchases.  
  Android 5.0+ · offline · no account · no known trackers found · [source](https://github.com/AndorsTrailRelease/andors-trail)
- **[Brogue CE Android](https://h5.2113.net/games/brogue-ce.html)**: Fight your way down a randomly generated dungeon to retrieve the Amulet of Yendor from its 26th level. A personal, unofficial port of Brogue: Community Edition to Android.  
  Android 7.0+ · no account · offline · no known trackers found · AGPL-3.0-or-later · [source](https://github.com/tyrannotorus/c-brogue-ce-android)
- **[Cataclysm: Bright Nights](https://h5.2113.net/games/cataclysm-bn.html)**: Survive a procedurally generated world after the Cataclysm: scavenge, build, drive and fight, in a fork of Cataclysm: Dark Days Ahead that went its own way in 2020, with Lua mods and a way to win.  
  No root · Android 10+ · Vulkan 1.1 · 64-bit · no known trackers found · CC-BY-SA-3.0 · [source](https://github.com/cataclysmbn/Cataclysm-BN)
- **[Cataclysm: Dark Days Ahead](https://h5.2113.net/games/cataclysm-dda.html)**: Survive in a generated world overrun by zombies and stranger things: scavenge, craft, build vehicles and bases, and keep your character fed, healthy and sane. Turn-based, deep and unforgiving.  
  No root · Android 5.0+ · 64-bit ARM phone · no known trackers found · CC-BY-SA-3.0 · [source](https://github.com/CleverRaven/Cataclysm-DDA)
- **[Dungeon Crawl Stone Soup](https://h5.2113.net/games/dungeon-crawl-stone-soup.html)**: Pick a species and a background, then dive for the Orb of Zot through a dungeon full of monsters and fickle gods. A deep, free roguelike that runs entirely offline.  
  Android 5.0+ · no account · offline · no known trackers found · GPL-2.0-or-later · [source](https://github.com/crawl/crawl)
- **[EasyRPG Player](https://h5.2113.net/games/easyrpg-player.html)**: Play the many games made with RPG Maker 2000 and 2003 on your phone. Put the game folders in one place, pick a game from the list and play with on-screen buttons, a controller or a keyboard.  
  No root · Android 5.0+ · games not included · no known trackers found · GPL-3.0-or-later · [source](https://github.com/EasyRPG/Player)
- **[Endless Sky](https://h5.2113.net/games/endless-sky.html)**: Fly a starship between star systems, trade, take on missions and fight pirates. This is an unofficial Android port of the desktop game; it needs no internet and no permissions.  
  Android 5.0+ · OpenGL ES 3.0 · works offline · no known trackers found · GPL-3.0-only · [source](https://github.com/thewierdnut/endless-mobile)
- **[FLARE](https://h5.2113.net/games/flare-rpg.html)**: A single-player 2D action RPG engine with a finished free campaign to play on it. On Android you install the engine here and copy the game data, a free 613-megabyte download, onto the phone.  
  Game data (free download) · Android 4.1+ · no known trackers found · GPL-3.0-or-later · [source](https://github.com/flareteam/flare-engine)
- **[HyperRogue](https://h5.2113.net/games/hyperrogue.html)**: A turn-based roguelike on a hyperbolic plane: hunt for treasure through dozens of lands in a world where you almost never pass the same place twice. This is the free GPL build, not HyperRogue Gold.  
  Android 5.0+ · works offline · no known trackers found · GPL-2.0-only · [source](https://github.com/zenorogue/hyperrogue)
- **[Rat King Pixel Dungeon 2](https://h5.2113.net/games/rkpd2.html)**: Shattered Pixel Dungeon with every hero made stronger, and a new one: the Rat King, who has the main abilities of every class. A fan-made fork that installs next to the original.  
  Android 4.0+ · offline · English only · no known trackers found · GPL-3.0 · [source](https://github.com/Zrp200/rkpd2)
- **[ScummVM](https://h5.2113.net/games/scummvm.html)**: Play the adventure games of the 1980s and 1990s on your phone: ScummVM replaces the games’ original programs, so their data files run on Android with touch controls. Games are not included.  
  No root · Android 5.0+ · your own game files · no known trackers found · GPL-3.0-or-later · [source](https://github.com/scummvm/scummvm)
- **[Shattered Pixel Dungeon](https://h5.2113.net/games/shattered-pixel-dungeon.html)**: Pick a hero, go down, and try to survive: every run has new levels, enemies and loot, and dying means starting over. Free and open source, from a single developer.  
  Android 5.0+ · no account · no known trackers found · GPL-3.0-only · [source](https://github.com/00-Evan/shattered-pixel-dungeon)

## Games: Simulation Games

- **[Augustus](https://h5.2113.net/games/augustus.html)**: Caesar III with new rules and buildings: roadblocks, highways, new goods and monuments, on top of Julius’s widescreen and touch support. It runs on your own copy of the 1998 game.  
  Caesar III game files · Android 5.0+ · no known trackers found · AGPL-3.0 · [source](https://github.com/Keriew/augustus)
- **[Julius](https://h5.2113.net/games/julius.html)**: Play the 1998 city builder Caesar III on a phone or tablet with game files you own. Julius rebuilds the engine with the same rules and save files, plus widescreen and touch controls.  
  Caesar III game files · Android 5.0+ · no known trackers found · AGPL-3.0 · [source](https://github.com/bvschaik/julius)
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

- **[AAAAXY](https://h5.2113.net/games/aaaaxy.html)**: A retro-looking platformer where rooms loop back on themselves and corridors are longer inside than out. Explore one big, non-linear map at your own pace; no lives, no ads, no internet.  
  64-bit ARM · Android 6.0+ · 4–6 hours to the end · no known trackers found · Apache-2.0 · [source](https://github.com/divVerent/aaaaxy)
- **[Antimine](https://h5.2113.net/games/antimine.html)**: Clear minefields without setting one off, on boards built so you shouldn’t have to guess, from 9×9 up to 100×100. Offline, without ads in this build, and translated into Brazilian Portuguese.  
  Android 5.0+ · offline · tracker code found: ACRA · GPL-3.0-only · [source](https://github.com/lucasnlm/antimine-android)
- **[Breakout 71](https://h5.2113.net/games/breakout-71.html)**: A brick breaker built for short runs: clear seven levels, catch the coins that broken bricks drop to build your combo, and pick an upgrade after every level. Small, offline and without ads.  
  No root · Android 6.0+ · no known trackers found · AGPL-3.0-only · [source](https://gitlab.com/lecarore/breakout71)
- **[Burger Party](https://h5.2113.net/games/burger-party.html)**: Stack buns, meat, cheese and salad in the order each customer asks for, before the clock runs out, in the United States, on a pirate ship and in Japan. No ads and no purchases.  
  No root · no account · offline · no known trackers found · GPL-3.0-or-later · [source](https://github.com/agateau/burgerparty)
- **[Gauguin](https://h5.2113.net/games/gauguin.html)**: A Sudoku-like puzzle where every group of cells must reach its target by adding, subtracting, multiplying or dividing. Endless grids from 3×3 to 11×11, with no ads and no internet.  
  Android 7.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/meikpiep/gauguin)
- **[LibreSudoku](https://h5.2113.net/games/libresudoku.html)**: Classic and Killer Sudoku in three sizes and four difficulties, generated on your phone, with notes, hints, statistics and your own puzzle collections. Free, ad-free and offline.  
  Android 8.0+ · no known trackers found · GPL-3.0-only · [source](https://github.com/kaajjo/LibreSudoku)
- **[Minesweeper](https://h5.2113.net/games/minesweeper.html)**: This is john-athan’s open-source Minesweeper project: classic mine clearing plus timed Medium and memory-heavy Hard modes, custom boards, flag controls and local records.  
  Android 5.0+ · works offline · no known trackers found · GPL-3.0-or-later · [source](https://github.com/john-athan/minesweeper)
- **[Open Patience](https://h5.2113.net/games/open-patience.html)**: Klondike and FreeCell solitaire without ads or tracking: undo and redo, a one-tap finish once a game can be completed, and a list of your fastest wins, in an app that asks for no permissions.  
  No root · Android 7.0+ · 64-bit ARM · no known trackers found · AGPL-3.0-only · [source](https://github.com/d-rk/open-patience)
- **[Open Surge: retro game engine](https://h5.2113.net/games/open-surge.html)**: A fast 16-bit-style platformer starring Surge the Rabbit, and the open-source engine it runs on: play the demo levels, change them on your phone, or load games other people made.  
  No root · ARM phone or TV · Android 5.0+ · no known trackers found · GPL-3.0-or-later · [source](https://github.com/alemart/opensurge)
- **[osu!](https://h5.2113.net/games/osu.html)**: Tap circles, follow sliders and spin to the music in the free rhythm game, now on Android: the same osu!(lazer) as on computers, with all four game modes, online rankings and multiplayer.  
  No root · Android 5.0+ · free osu! account for online play · tracker code found: Sentry · MIT · [source](https://github.com/ppy/osu)
- **[PySolFC](https://h5.2113.net/games/pysolfc.html)**: Choose from a very large offline collection of solitaire variants—not only Klondike and FreeCell, but Mahjongg, Shisen-Sho, memory and puzzle families—with hints and undo.  
  Android 5.0+ · ARM phone or tablet · offline · no known trackers found · GPL-3.0-or-later · [source](https://github.com/shlomif/PySolFC)
- **[Simon Tatham's Puzzles](https://h5.2113.net/games/simon-tatham-puzzles.html)**: Forty small logic puzzles, from Sudoku-style Solo to Loopy, Bridges and Mines, each generating a new grid whenever you want one. Free, offline and without ads.  
  Android 5.0+ · no known trackers found · MIT · [source](https://github.com/chrisboyle/sgtpuzzles)
- **[SuperTux](https://h5.2113.net/games/supertux.html)**: Run, jump and stomp through snowy and forest worlds as Tux on his way to rescue Penny. A complete game made by volunteers, with no ads; this is the team’s own Android build.  
  Android 9+ · 64-bit ARM · no account · no known trackers found · GPL-3.0 · [source](https://github.com/SuperTux/supertux)
- **[Vector Pinball](https://h5.2113.net/games/vector-pinball.html)**: Pinball drawn with lines and circles, where the physics matter more than the graphics: nine tables, multiball, local high scores, and not a single permission requested.  
  Android 4.4+ · no known trackers found · GPL-3.0-only · [source](https://github.com/dozingcat/Vector-Pinball)

## Games: PC Emulators

- **[Limbo PC Emulator](https://h5.2113.net/games/limbo-pc-emulator.html)**: A QEMU-based emulator that runs a whole x86 PC inside your phone: boot FreeDOS, small Linux distributions or other systems from ISO and disk images you bring.  
  No root · Android 5.0+ · ARM phone · your own OS images · no known trackers found · GPL-2.0-or-later · [source](https://github.com/limboemu/limbo)
- **[Ruffle](https://h5.2113.net/games/ruffle.html)**: The Ruffle project’s own Android app: it plays games and animations made for Adobe Flash Player from a SWF file or a web address, with an on-screen keyboard for games that need keys.  
  No root · Android 8.0+ · 64-bit ARM · no known trackers found · MIT · [source](https://github.com/ruffle-rs/ruffle-android)
- **[Winlator](https://h5.2113.net/games/winlator.html)**: Runs Windows (x86-64) games and programs on an Android phone, using Wine to handle Windows and Box64 to translate the x86 code.  
  64-bit ARM phone · Android 8+ · no root · no known trackers found · LGPL-2.1 · [source](https://github.com/brunodev85/winlator)

## Games: Minecraft Launchers

- **[Amethyst Launcher](https://h5.2113.net/games/amethyst-launcher.html)**: Runs the PC (Java) edition of Minecraft on Android. It continues PojavLauncher and supports Forge and Fabric mods.  
  Android 5+ · Microsoft account with Minecraft Java · no known trackers found · LGPL-3.0 · [source](https://github.com/AngelAuraMC/Amethyst-Android)
- **[Fold Craft Launcher](https://h5.2113.net/games/fold-craft-launcher.html)**: A Minecraft Java Edition launcher for Android that combines HMCL’s version and mod management with the Amethyst engine.  
  Android 8.0+ · Minecraft: Java Edition, sold by Mojang · no known trackers found · GPL-3.0 · [source](https://github.com/FCL-Team/FoldCraftLauncher)
- **[MojoLauncher](https://h5.2113.net/games/mojolauncher.html)**: A Minecraft Java Edition launcher from one of PojavLauncher’s developers: install vanilla or modded versions, pick a graphics renderer for your phone, and play with touch controls or a gamepad.  
  No root · Android 5.0+ · Minecraft: Java Edition · no known trackers found · LGPL-3.0 · [source](https://github.com/MojoLauncher/MojoLauncher)
- **[Zalith Launcher 2](https://h5.2113.net/games/zalith-launcher-2.html)**: A newly designed Minecraft Java Edition launcher for Android. It uses the PojavLauncher engine under a modern Material Design 3 interface.  
  Android 8+ · Minecraft: Java Edition · no known trackers found · GPL-3.0 · [source](https://github.com/ZalithLauncher/ZalithLauncher2)

## Games: Console Emulators

- **[Dolphin Emulator](https://h5.2113.net/games/dolphin-emulator.html)**: The open-source GameCube and Wii emulator, on Android. It needs a 64-bit phone and a GPU with OpenGL ES 3.0 or Vulkan, and you bring your own games.  
  Your own games · 64-bit phone · Android 5.0+ · no known trackers found · GPL-2.0-or-later · [source](https://github.com/dolphin-emu/dolphin)
- **[Flycast](https://h5.2113.net/games/flycast.html)**: Play Dreamcast discs and Naomi and Atomiswave arcade games you own on Android, with upscaling, controller support and the online modes of some Dreamcast games. A Dreamcast BIOS is optional.  
  Your own games · Android 5.0+ · OpenGL ES 2.0 · no known trackers found · GPL-2.0 · [source](https://github.com/flyinghead/flycast)
- **[J2ME Loader](https://h5.2113.net/games/j2me-loader.html)**: Play the Java games of 2000s Nokia and Sony Ericsson phones on Android: J2ME Loader runs .jar games with a virtual keypad, per-game settings and scaling. You bring the games.  
  Android 4.0+ · your own .jar or .jad files · tracker code found: ACRA · Apache-2.0 · [source](https://github.com/nikita36078/J2ME-Loader)
- **[Lemuroid](https://h5.2113.net/games/lemuroid.html)**: One app for many retro consoles, built on libretro: it finds the games on your phone, saves your progress automatically and works with touch controls or a gamepad. Games are not included.  
  Your own games · Android 6.0+ · no known trackers found · GPL-3.0-or-later · [source](https://github.com/Swordfish90/Lemuroid)
- **[MAME4droid](https://h5.2113.net/games/mame4droid.html)**: The MAME arcade emulator on Android, kept up to date with MAME itself: thousands of arcade boards and old computers, touch or Bluetooth controls, and online play with a friend. No games included.  
  No root · Android 10+ · 64-bit ARM · your own ROM files · no known trackers found · GPL-2.0 · [source](https://github.com/seleuco/MAME4droid-Current)
- **[melonDS](https://h5.2113.net/games/melonds.html)**: An emulator for Nintendo DS and DSi games. DS games need no BIOS files, thanks to a built-in open-source replacement; the games themselves are not included.  
  Your own DS games · Android 7.0+ · no known trackers found · GPL-3.0 · [source](https://github.com/rafaelvcaetano/melonDS-android)
- **[Mupen64Plus AE](https://h5.2113.net/games/mupen64plus-ae.html)**: An N64 emulator that comes with every core and plugin it needs: choose a video plugin per game, play with touch controls or a gamepad, and bring your own game files.  
  No root · Android 5.0+ · your own game files · no known trackers found · GPL-3.0-or-later · [source](https://github.com/mupen64plus-ae/mupen64plus-ae)
- **[Play!](https://h5.2113.net/games/play-emulator.html)**: A PlayStation 2 emulator that doesn’t need a BIOS: it re-creates the console’s system software itself, so you only bring your own game discs as image files.  
  No root · Android 4.4+ · your own PS2 game images · no known trackers found · BSD-2-Clause · [source](https://github.com/jpd002/Play-)
- **[PPSSPP](https://h5.2113.net/games/ppsspp.html)**: A PSP emulator that needs no BIOS file, adds sharper graphics and save states, and works with touch controls, gamepads or a keyboard. Games are not included.  
  Your own PSP games · OpenGL ES 2.0 · Android 4.1+ · no known trackers found · GPL-2.0-or-later · [source](https://github.com/hrydgard/ppsspp)
- **[RetroArch](https://h5.2113.net/games/retroarch.html)**: One frontend for many emulators: RetroArch runs emulator cores for many consoles and computers under a single interface, with its core downloader built in. Games are not included.  
  Your own games and BIOS · Android 4.1+ · no known trackers found · GPL-3.0-only · [source](https://github.com/libretro/RetroArch)
- **[UniPatcher](https://h5.2113.net/games/unipatcher.html)**: Apply a fan translation or a ROM hack to a game you already own, on the phone: pick the ROM, the patch and where to save the result. It reads eleven patch formats and leaves the original alone.  
  No root · Android 7.0+ · tracker code found: ACRA · GPL-3.0-or-later · [source](https://github.com/btimofeev/UniPatcher)
- **[Vita3K](https://h5.2113.net/games/vita3k.html)**: An experimental PlayStation Vita emulator. It runs homebrew and many commercial Vita games that you dump from your own console.  
  64-bit phone · Android 9+ · your own games · no known trackers found · GPL-2.0 · [source](https://github.com/Vita3K/Vita3K)

## Games: Game Streaming

- **[Artemis](https://h5.2113.net/games/artemis.html)**: Stream games and your desktop from a Windows PC to your phone or tablet: a fork of Moonlight with dozens of extra options, made to pair with the Apollo host for virtual displays and clipboard sync.  
  No root · a PC running Apollo or Sunshine · Android 5.0+ · no known trackers found · GPL-3.0 · [source](https://github.com/ClassicOldSong/moonlight-android)
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
