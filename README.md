<p align="center">
  <img src="assets/icon.png" width="128" alt="Orbit XR icon">
</p>

<h1 align="center">Orbit XR</h1>

<p align="center">
  A fast, lightweight desktop app for working with PICO and Meta Quest headsets.
</p>

<p align="center">
  <a href="https://github.com/OWNER/orbit-xr-releases/releases/latest/download/Orbit-XR-mac-arm64.dmg"><b>Download for macOS</b></a>
  &nbsp;·&nbsp;
  Windows — coming soon
  &nbsp;·&nbsp;
  <a href="https://github.com/OWNER/orbit-xr-releases/releases/latest">All releases and changes</a>
</p>

---

## What it does

- **Files** — browse the headset, pull files to your Mac, push by drag and drop, preview with Quick Look.
- **Apps and favorites** — pin your apps, see installed versions, jump to app data in one click, save any folder as a favorite.
- **Screenshots and recordings** — take them from your Mac, browse them as a grid with thumbnails, filter by app.
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

- macOS 13 Ventura or newer, Apple Silicon Mac (M1 or newer)
- `adb` from Android Platform Tools: `brew install --cask android-platform-tools`
- Developer mode enabled on the headset

## Install

1. Download the `.dmg` and drag **Orbit XR** to **Applications**.
2. The app is not signed by Apple yet, so macOS blocks it on first launch: open it once, then go to **System Settings → Privacy & Security** and click **Open Anyway**.
3. Connect the headset with a USB-C data cable, put it on and allow USB debugging.

Step-by-step guide: [Installation Guide (PDF)](assets/Orbit-XR-Installation-Guide.pdf)

## Feedback

Found a bug or missing something? Contact the author, Taras Hulka. Please include the version (**Orbit XR → About Orbit XR**), the headset model and what happened.

---

<sub>© 2026 Taras Hulka. Orbit XR is provided “as is”, without warranty of any kind. PICO is a trademark of ByteDance. Meta Quest is a trademark of Meta Platforms, Inc. Orbit XR is an independent tool and is not affiliated with or endorsed by them.</sub>
