<p align="center"><img src="assets/psaltercast.png" width="96" alt="Psaltercast icon"></p>

# Psaltercast

Easy-to-use church service software for macOS, Windows and Linux. Put songs, scripture, presentations and media on screen, and run it all from your phone.

**Download:** https://davidkngo.github.io/lucerna-release/ or the [latest release](https://github.com/davidkngo/lucerna-release/releases/latest).

| Platform | File |
|---|---|
| macOS 13 or newer, Apple Silicon (M1 or newer) | `Psaltercast-<version>-macos.dmg` |
| Windows 10/11, 64-bit | `Psaltercast-<version>-windows-x64.zip` |
| Linux, x86-64 | `Psaltercast-<version>-linux-x86_64.AppImage` |

## Installing

Psaltercast isn't signed by Apple or Microsoft yet, so your computer asks once before opening it.

Psaltercast used to be called Lucerna: versions up to 0.0.4 still use that name for their files.

- **macOS:** open the `.dmg` and drag Psaltercast into Applications. The first time, right-click it and choose **Open**. If macOS says the app is damaged, run `xattr -dr com.apple.quarantine /Applications/Psaltercast.app` once.
- **Windows:** unzip, then run `psaltercast.exe`. If SmartScreen appears, choose **More info → Run anyway**.
- **Linux:** `chmod +x Psaltercast-*.AppImage`, then run it. Some distributions need `libfuse2`.

## About this repository

This repository only hosts releases and the download page (`index.html`, served by GitHub Pages). The builds are made and published here automatically. To report a problem, [open an issue](https://github.com/davidkngo/lucerna-release/issues).
