<p align="center"><img src="assets/lucerna.png" width="96" alt="Lucerna icon"></p>

# Lucerna

Easy-to-use church service software for macOS, Windows and Linux. Put songs, scripture, presentations and media on screen, and run it all from your phone.

**Download:** https://davidkngo.github.io/lucerna-release/ or the [latest release](https://github.com/davidkngo/lucerna-release/releases/latest).

| Platform | File |
|---|---|
| macOS 13 or newer, Apple Silicon (M1 or newer) | `Lucerna-<version>-macos.dmg` |
| Windows 10/11, 64-bit | `Lucerna-<version>-windows-x64.zip` |
| Linux, x86-64 | `Lucerna-<version>-linux-x86_64.AppImage` |

## Installing

Lucerna isn't signed by Apple or Microsoft yet, so your computer asks once before opening it.

- **macOS:** open the `.dmg` and drag Lucerna into Applications. The first time, right-click it and choose **Open**. If macOS says the app is damaged, run `xattr -dr com.apple.quarantine /Applications/Lucerna.app` once.
- **Windows:** unzip, then run `lucerna.exe`. If SmartScreen appears, choose **More info → Run anyway**.
- **Linux:** `chmod +x Lucerna-*.AppImage`, then run it. Some distributions need `libfuse2`.

## About this repository

This repository only hosts releases and the download page (`index.html`, served by GitHub Pages). The builds are made and published here automatically. To report a problem, [open an issue](https://github.com/davidkngo/lucerna-release/issues).
