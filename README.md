<p align="center">
  <img src="logo.svg" width="100" alt="Aion Logo" />
</p>

<h1 align="center">Aion</h1>

<p align="center">
  <strong>Understand Your Time.</strong>
</p>

<p align="center">
  A privacy-first, cross-platform desktop app for daily time tracking.<br/>
  Runs locally. No cloud. No telemetry. All data stays on your machine.
</p>

<p align="center">
  <a href="https://github.com/minakolta/aion-releases/releases/latest">
    <img src="https://img.shields.io/github/v/release/minakolta/aion-releases?style=flat-square&color=0d9488&label=latest" alt="Latest Release" />
  </a>
  <img src="https://img.shields.io/badge/platform-macOS%20%7C%20Windows%20%7C%20Linux-0d9488?style=flat-square" alt="Platform" />
  <a href="https://github.com/minakolta/aion">
    <img src="https://img.shields.io/badge/source-GitHub-0d9488?style=flat-square&logo=github" alt="Source" />
  </a>
</p>

---

## Download

Download the latest version for your platform:

| Platform | Architecture | Download |
|:---------|:-------------|:---------|
| **macOS** | Apple Silicon (M1/M2/M3/M4) | [**.dmg**](https://github.com/minakolta/aion-releases/releases/latest/download/aion-0.4.0-mac-arm64.dmg) |
| **macOS** | Intel | [**.dmg**](https://github.com/minakolta/aion-releases/releases/latest/download/aion-0.4.0-mac-x64.dmg) |
| **Windows** | x64 | [**.exe**](https://github.com/minakolta/aion-releases/releases/latest/download/aion-0.4.0-win-x64-setup.exe) |
| **Windows** | ARM64 | [**.exe**](https://github.com/minakolta/aion-releases/releases/latest/download/aion-0.4.0-win-arm64-setup.exe) |
| **Linux** | x64 | [**.AppImage**](https://github.com/minakolta/aion-releases/releases/latest/download/aion-0.4.0-linux-x86_64.AppImage) / [**.deb**](https://github.com/minakolta/aion-releases/releases/latest/download/aion-0.4.0-linux-amd64.deb) |
| **Linux** | ARM64 | [**.AppImage**](https://github.com/minakolta/aion-releases/releases/latest/download/aion-0.4.0-linux-arm64.AppImage) / [**.deb**](https://github.com/minakolta/aion-releases/releases/latest/download/aion-0.4.0-linux-arm64.deb) |

> All previous releases are available on the [Releases page](https://github.com/minakolta/aion-releases/releases).

---

## What is Aion?

Aion passively tracks which app and window is active on your machine, then shows you clear daily and weekly summaries of where your time goes.

**Key features:**
- Automatic window tracking (app name + window title)
- Daily, weekly, and monthly time summaries
- App categorization and focus detection
- Distraction tracking
- Data export (CSV/JSON)
- Teamwork.com integration for time logging
- In-app auto-updates

**Privacy guarantees:**
- All data stored locally in SQLite — never leaves your machine
- No keylogging, no screenshots, no content inspection
- No cloud, no telemetry, no analytics
- No account required

---

## Installation

### macOS

1. Download the `.dmg` for your architecture
2. Open the DMG and drag Aion to Applications
3. On first launch, grant **Accessibility** and **Screen Recording** permissions when prompted
4. Aion will appear in your menu bar tray

> **Note:** The app is not code-signed yet. You may need to right-click and select "Open" on first launch, or allow it in System Settings > Privacy & Security.

### Windows

1. Download the `.exe` installer
2. Run the installer and follow the prompts
3. Aion will appear in your system tray

### Linux

**AppImage:**
1. Download the `.AppImage`
2. Make it executable: `chmod +x aion-*.AppImage`
3. Run it: `./aion-*.AppImage`

**Debian/Ubuntu:**
1. Download the `.deb` package
2. Install: `sudo dpkg -i aion-*.deb`

---

## Auto-Updates

Aion checks for updates automatically. When a new version is available, you'll see it in **Settings > Updates** with options to download and install.

---

## Source Code

Aion is developed at [github.com/minakolta/aion](https://github.com/minakolta/aion). This repository serves as the public release distribution channel.

---

<p align="center">
  <sub>Made with care by <a href="https://github.com/minakolta">Mina Kolta</a></sub>
</p>
