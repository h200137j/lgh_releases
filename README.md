# Little Guest House — releases

Built installers only. No source code lives here.

The app's auto-updater polls this repo's latest release. Releases are published by
`lgh_app`'s `release.yml` workflow when a `vX.Y.Z` tag is pushed. Don't upload or edit
releases by hand.

| Platform | Asset | First install |
|----------|-------|---------------|
| Android | `lgh_app-vX.Y.Z-android.apk` | Open the APK, allow "Install unknown apps" once |
| Windows | `lgh_app-vX.Y.Z-windows-setup.exe` | Run it (no admin needed) |
| Linux | `lgh_app-vX.Y.Z-linux-x64.tar.gz` | `tar -xzf … && ./lgh_app/install.sh` |
| macOS | `lgh_app-vX.Y.Z-macos.zip` | Unzip to Applications, right-click > Open the first time |

After the first install, updates install themselves when the device is idle.
