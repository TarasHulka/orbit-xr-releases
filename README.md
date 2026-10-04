<p align="center">
  <img src="assets/icon.png" width="128" alt="Orbit XR icon">
</p>

<h1 align="center">Orbit XR</h1>

<p align="center">
  A fast, lightweight desktop app for working with PICO and Meta Quest headsets.<br>
  <sub>by <a href="https://hulkalabs.com">Hulka Labs</a></sub>
</p>

<p align="center">
  <a href="https://github.com/TarasHulka/orbit-xr-releases/releases/latest/download/Orbit-XR-mac-arm64.dmg"><b>Download for macOS</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/TarasHulka/orbit-xr-releases/releases/latest/download/Orbit-XR-win-x64.exe"><b>Download for Windows</b></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/TarasHulka/orbit-xr-releases/releases/latest">All releases and changes</a>
  &nbsp;·&nbsp;
  <a href="https://hulkalabs.com/orbit-xr/">Website</a>
</p>

---

## What it does

- **Files** — browse the headset, pull files to your computer, push by drag and drop, preview them.
- **Apps** — every app on the headset in one table: versions, status, launch, stop, restart, clear data, uninstall; pin your own apps to the sidebar.
- **Screenshots and recordings** — take them from your computer, browse them as a grid with thumbnails, filter by app.
- **Unity logs** — filters, collapsible stack traces, crashes, a separate log window.
- **Screen casting** — a live one-eye view in a separate window.
- **APK install** — drag an APK into the window, with version check and clear error messages.
- **Wi-Fi** — connect once over USB, then switch to Wi-Fi and unplug the cable.

## Supported devices

| Device | Status |
|---|---|
| PICO 4 Ultra Enterprise | Tested |
| Meta Quest 2 | Tested |
| Meta Quest 3 | Not tested yet |
| Other Android devices | Basic support |

## Requirements

| | macOS | Windows |
|---|---|---|
| System | macOS 13 Ventura or newer, Apple Silicon (M1 or newer) | Windows 10 or 11, 64-bit (x64) |
| adb | `brew install --cask android-platform-tools` | `winget install Google.PlatformTools` |
| USB driver | not needed | Meta Quest: Meta Quest ADB driver · PICO: usually automatic, otherwise Google USB Driver |

Developer mode must be enabled on the headset.

## Install

**macOS**
1. Open the `.dmg` and drag **Orbit XR** to **Applications**.
2. The app is not signed by Apple yet: open it once, then go to **System Settings → Privacy & Security** and click **Open Anyway**.

**Windows**
1. Run `Orbit-XR-win-x64.exe` — it installs and starts Orbit XR.
2. The app is not signed by Microsoft yet: when SmartScreen appears, click **More info → Run anyway**.

Then connect the headset with a USB-C data cable, put it on and allow USB debugging.

Step-by-step guide for both systems: [Installation Guide (PDF)](assets/Orbit-XR-Installation-Guide.pdf)

## Feedback

Found a bug or missing something? Contact the author. Please include the version (**About Orbit XR**), your operating system, the headset model and what happened.

---

<sub>© 2026 Hulka Labs. Orbit XR is provided “as is”, without warranty of any kind. PICO is a trademark of ByteDance. Meta Quest is a trademark of Meta Platforms, Inc. Windows is a trademark of Microsoft Corporation; macOS is a trademark of Apple Inc. Orbit XR is an independent tool and is not affiliated with or endorsed by them.</sub>
