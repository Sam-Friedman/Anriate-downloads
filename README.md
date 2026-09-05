# Download Anriate

Anriate is a native desktop 3D editor for modeling, animation, rigging and rendering small scenes.

## Get Anriate 0.1.0 beta 1

**[Download installers from Releases](https://github.com/Sam-Friedman/Anriate-downloads/releases)**

Open a release and choose an installer from **Assets**. No Rust installation or source build is required.

| Your computer | Choose |
| --- | --- |
| Apple Silicon Mac (M1 or newer), macOS 14+ | [Download for Apple Silicon](https://github.com/Sam-Friedman/Anriate-downloads/releases/download/v0.1.0-beta.1/Anriate-0.1.0-beta.1-macos-arm64.dmg) |
| Intel Mac, macOS 14+ | [Download for Intel Mac](https://github.com/Sam-Friedman/Anriate-downloads/releases/download/v0.1.0-beta.1/Anriate-0.1.0-beta.1-macos-x86_64.dmg) |
| Windows 10/11, 64-bit | [Download Windows Setup](https://github.com/Sam-Friedman/Anriate-downloads/releases/download/v0.1.0-beta.1/Anriate-0.1.0-beta.1-windows-x64-setup.exe) |
| Ubuntu 22.04+ or compatible Debian-based Linux, 64-bit | [Download Debian/Ubuntu package](https://github.com/Sam-Friedman/Anriate-downloads/releases/download/v0.1.0-beta.1/Anriate-0.1.0-beta.1-linux-x64.deb) |
| Other compatible Linux, glibc 2.35+, 64-bit | [Download portable Linux archive](https://github.com/Sam-Friedman/Anriate-downloads/releases/download/v0.1.0-beta.1/Anriate-0.1.0-beta.1-linux-x64.tar.gz) |

[Installation instructions](INSTALL.md) explain installation, updates, runtime requirements, optional ffmpeg video export and checksums.

These beta builds are not Apple-notarized or Windows publisher-signed. Your operating system may show a first-launch warning. Follow the installation guide only for downloads you trust. The automatically generated **Source code** archives contain this download site's documentation, not the application; choose an installer instead.

## Start creating

Open **Examples → Bouncing ball** or **Skinned limb · IK study**. Use the timeline’s **End** field or **+24 frames** button to extend a shot. Save editable projects as `.riri`.

The beta includes UV editing and modifiers, graph animation, skin weights and IK, materials/environment lighting, background rendering, recovery and portable project collection. GLB supports hierarchy, sampled animation and skinning. Raster rendering, bounded mesh tools and explicit interchange limits keep the editor focused; this is not full Maya parity.

MP4/WebM output uses a separately installed ffmpeg. Still images and image sequences work without it.

This public repository contains installers and user-facing documentation only. Anriate’s source repository remains private.
