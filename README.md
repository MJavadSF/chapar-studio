<p align="center"><img src="assets/icon.png" width="112" alt="Chapar"></p>

<h1 align="center">chapar://</h1>

<p align="center">A fast, modern API client for the desktop.<br>
<a href="https://github.com/MJavadSF/chapar-studio/releases/latest"><b>Download the latest version</b></a></p>

---

This repository hosts Chapar's installers and update files. Every release is listed under
[**Releases**](https://github.com/MJavadSF/chapar-studio/releases), with its notes.

## Download

| System | File |
| --- | --- |
| Windows 10 / 11 | `Chapar-x.y.z-win-x64.exe` |
| macOS, Apple Silicon (M1 and later) | `Chapar-x.y.z-mac-arm64.dmg` |
| macOS, Intel | `Chapar-x.y.z-mac-x64.dmg` |
| Linux, any distribution | `Chapar-x.y.z-linux-x86_64.AppImage` |
| Linux, Debian / Ubuntu | `chapar_x.y.z_amd64.deb` |

## Install

**Windows** — run the installer. If SmartScreen warns (the installer is not code-signed yet), choose
**More info → Run anyway**.

**macOS** — open the `.dmg` and drag Chapar to Applications. The first time, macOS asks because the app has no
Apple Developer ID yet: open **System Settings → Privacy & Security** and click **Open Anyway**, or run
`xattr -dr com.apple.quarantine /Applications/Chapar.app`.

**Linux** — AppImage: `chmod +x Chapar-*.AppImage` and run it. Debian / Ubuntu: `sudo apt install ./chapar_*.deb`.

## Updates

Chapar checks this repository for new versions and shows a notice in the app. On Windows and Linux it downloads
only the parts that changed and installs on restart; on macOS the notice links to the new download.
Nothing is installed without your click.

## Privacy

Your collections, environments and history stay on your computer. Chapar contacts GitHub only to check for
updates, and you can turn that off in **Settings → About**.
