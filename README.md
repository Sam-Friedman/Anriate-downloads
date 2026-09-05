# Download Anriate

Anriate is a native desktop 3D editor for modeling, animation, rigging and rendering small scenes.

## Get Anriate

**[Download installers from Releases](https://github.com/Sam-Friedman/Anriate-downloads/releases)**

Open the current release and choose an installer from **Assets**. No Rust installation or source build is required.

| Your computer | Asset to choose |
| --- | --- |
| Apple Silicon Mac (M1 or newer), macOS 14+ | `macos-arm64.dmg` |
| Intel Mac, macOS 14+ | `macos-x86_64.dmg` |
| Windows 10/11, 64-bit | `windows-x64-setup.exe` |
| Ubuntu 22.04+ or compatible Debian-based Linux, 64-bit | `linux-x64.deb` |
| Other compatible Linux, glibc 2.35+, 64-bit | `linux-x64.tar.gz` |

[Installation instructions](INSTALL.md) explain installation, updates, runtime requirements, optional ffmpeg video export and checksums.

The Mac installers are Developer ID signed and notarized by Apple. Open the app normally after copying it to Applications; macOS may show its standard downloaded-app confirmation. Windows Setup is not yet publisher-signed and may show an unknown-publisher warning. The automatically generated **Source code** archives contain this download site's documentation, not the application; choose an installer instead.

## Start creating

Open **Examples → Bouncing ball** or **Skinned limb · IK study**. Use the timeline’s **End** field or **+24 frames** button to extend a shot. Save editable projects as `.riri`.

The beta includes UV editing and modifiers, graph animation, skin weights and IK, materials/environment lighting, background rendering, recovery and portable project collection. GLB supports hierarchy, sampled animation and skinning. Raster rendering, bounded mesh tools and explicit interchange limits keep the editor focused; this is not full Maya parity.

MP4/WebM output uses a separately installed ffmpeg. Still images and image sequences work without it.

This public repository contains installers and user-facing documentation only. Anriate’s source repository remains private.
