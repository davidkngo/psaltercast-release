<p align="center"><img src="assets/psaltercast.png" width="96" alt="Psaltercast icon"></p>

# Psaltercast

Easy-to-use church service software for macOS, Windows and Linux. Put songs, scripture, presentations and media on screen, and run it all from your phone.

**Download:** https://davidkngo.github.io/psaltercast-release/ or the [latest release](https://github.com/davidkngo/psaltercast-release/releases/latest).

| Platform | File |
|---|---|
| macOS 13 or newer, Apple Silicon or Intel | `Psaltercast-<version>-macos.pkg` |
| Windows 10/11, 64-bit | `Psaltercast-<version>-windows-x64-setup.exe` |
| Linux, x86-64 | `Psaltercast-<version>-linux-x86_64.AppImage` |

## Installing

Open the installer and follow its steps. Psaltercast isn't signed by Apple or Microsoft yet, so the first time your computer asks you to confirm.

- **macOS:** open the `.pkg`. If macOS says it can't check it for malicious software, click **Done**, then go to **System Settings → Privacy & Security**, click **Open Anyway** next to Psaltercast, and confirm. Click **Continue** and **Install**. Psaltercast is now in Applications.
- **Windows:** open the `-setup.exe`. If SmartScreen appears, choose **More info → Run anyway**. Click **Install**. Psaltercast is now in the Start menu. No administrator password needed; remove it under **Settings → Apps**.
- **Linux:** make the AppImage executable (`chmod +x Psaltercast-*.AppImage`, or **Properties → Permissions**) and open it. It offers to add itself to your applications menu. Some distributions need `libfuse2`.

After that, Psaltercast keeps itself up to date: when a new version is out, it tells you what's new and installs it with one click.

Versions up to 0.0.5 come as a disk image (`.dmg`, drag Psaltercast into Applications) or a `.zip` (unzip and run `psaltercast.exe`). Versions up to 0.0.4 use the old name, Lucerna, and their macOS build is Apple Silicon only.

## About this repository

This repository only hosts releases and the download page (`index.html`, served by GitHub Pages). The builds are made and published here automatically. To report a problem, [open an issue](https://github.com/davidkngo/psaltercast-release/issues).
