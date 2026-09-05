# Install Anriate

Download the installer for your computer from the release's **Assets** list. You do not need Rust or a development environment. GitHub's automatically generated “Source code” archives in the downloads repository contain documentation, not the application; choose an Anriate installer instead.

## macOS

Requires macOS 14 or newer. Choose **macos-arm64.dmg** for an Apple Silicon Mac (M1 or newer) or **macos-x86_64.dmg** for an Intel Mac. Find your chip in Apple menu → About This Mac.

1. Open the downloaded `.dmg`.
2. Drag **Anriate.app** onto **Applications**.
3. Eject the disk image and open Anriate from Applications.

For releases marked **Developer ID signed and notarized**, open the app normally. macOS may show the standard confirmation that the app was downloaded from the internet. The notarization ticket is attached to both the app and disk image for offline verification.

The original **0.1.0-beta.1** release was ad-hoc signed and was not notarized. It may require Apple's **System Settings → Privacy & Security → Open Anyway** procedure: https://support.apple.com/en-gb/102445. Prefer a newer notarized release when available. Do not disable Gatekeeper globally.

To update, quit Anriate and replace its copy in Applications. To uninstall, remove Anriate.app. Your `.riri` projects and recovery copies are separate and remain intact.

## Windows

Requires 64-bit Windows 10 or 11 and a compatible graphics driver. Run **windows-x64-setup.exe**. The installer installs for your current user, adds a Start menu shortcut and provides an uninstaller in Windows Settings → Apps. Administrator access is not required.

The beta installer does not have a Windows publisher certificate. Windows may display an unknown-publisher warning. Only install files you trust from the intended release page. Quit the editor before installing an update.

## Linux

The `.deb` targets 64-bit Ubuntu 22.04 or newer and compatible Debian-based distributions. Install it through your package manager, or run:

```sh
sudo apt install ./Anriate-*-linux-x64.deb
```

The portable **linux-x64.tar.gz** also works on compatible distributions with glibc 2.35 or newer. Extract it and run `./anriate`. A graphical X11/Wayland session, Vulkan driver, libxkbcommon/X11 libraries and an XDG desktop portal are required. The `.deb` declares runtime dependencies; other distributions must provide their equivalents. Software Vulkan is suitable for testing rather than a performance target.

## First launch

Try **Examples → Bouncing ball** or **Skinned limb · IK study**. Save editable projects as `.riri`. Extend a shot with the timeline's **End** field or **+24 frames** button (the button follows the scene FPS).

PNG/TIFF stills and image sequences work without extra software. MP4/WebM export additionally requires **ffmpeg**. Install it separately and choose its executable under **Inspector → Output → Video encoder**, or add it to PATH. It is not bundled with these installers.

The native project format preserves exact authoring data. GLB transfers the supported geometry, animation and skinning subset. See the [downloads page](https://github.com/Sam-Friedman/Anriate-downloads) for the beta's scope and limitations.

## Download integrity

Every release includes `SHA256SUMS.txt`. Compare a downloaded asset with its listed SHA-256 digest using `shasum -a 256` on macOS, `sha256sum` on Linux, or `Get-FileHash -Algorithm SHA256` in PowerShell. Checksums detect a damaged or mismatched download; they are not a publisher signature.
