# PilotCut for Windows

<p align="center">
  <a href="https://pilotcut.com">
    <img src="https://pilotcut.com/logo.png" alt="PilotCut Logo" width="80" height="80" />
  </a>
</p>

<p align="center">
  <b>The Video Editor That Does the Editing — Local-First AI Video Editor for Windows</b>
</p>

<p align="center">
  <a href="README.zh-TW.md">繁體中文</a> | <b>English</b>
</p>

<p align="center">
  <a href="https://github.com/pilotcut/pilotcut-windows-releases/releases/latest"><img src="https://img.shields.io/github/v/release/pilotcut/pilotcut-windows-releases?style=flat-square&color=blue" alt="Latest Release"></a>
  <a href="https://github.com/pilotcut/pilotcut-windows-releases/releases"><img src="https://img.shields.io/github/downloads/pilotcut/pilotcut-windows-releases/total?style=flat-square&color=green" alt="Total Downloads"></a>
  <a href="https://pilotcut.com"><img src="https://img.shields.io/badge/website-pilotcut.com-orange?style=flat-square" alt="Official Website"></a>
</p>

---

## Overview

**PilotCut** is the native, local-first video editor built for AI agents. Tell Claude Code, OpenAI Codex, Gemini CLI, or custom agents the video you want. PilotCut maps every request into concrete, reviewable timeline operations — making cuts, collapsing dead air, removing filler words, and placing B-roll, all while your footage never leaves your machine.

This repository hosts official Windows releases, installers, changelogs, and release assets for PilotCut on Windows.

---

## Key Features

- **Agent-in-the-Loop Workflow**: Connect Claude Code, Codex, Gemini CLI, or custom local agents via MCP (40+ tools) and command-line interfaces. Your agent proposes edits; you review and approve every change.
- **AI Filler-Word Removal**: Detect and cut "um", "uh", repeated phrases, and false starts in a single automated pass.
- **Intelligent Silence Collapse**: Tighten pauses and dead air without disturbing natural pacing or speech rhythm.
- **Automated B-Roll Placement**: Automatically match and insert screen recordings, product demos, and contextual media to narration beats.
- **100% Local-First & Private**: Your originals, proxy files, and render exports stay securely on your Windows PC. No cloud footage uploads, no credit meters.
- **Native Timeline & Named Operations**: Fast, hardware-accelerated playback and editing. Every change is an undoable, reviewable operation with a clear name.
- **Native Windows Performance**: High-performance multi-threaded video rendering and GPU hardware encoding acceleration (DirectX 12 / NVENC / QuickSync / AMF).

---

## Download & Installation

### Option 1: Direct Download (Recommended)

1. Go to the [**Latest Releases Page**](https://github.com/pilotcut/pilotcut-windows-releases/releases/latest).
2. Download the installer:
   - **`PilotCut-Setup-x64.exe`** (Standard Windows Installer - 64-bit)
   - *(Optional)* Portable zip package if available.
3. Run the installer and follow the setup wizard.
4. Launch PilotCut from your Start menu or Desktop shortcut.

### Option 2: Command Line / Package Managers *(Coming Soon)*

```powershell
# Winget (coming soon)
winget install PilotCut.PilotCut
```

---

## System Requirements

| Component | Minimum | Recommended |
| :--- | :--- | :--- |
| **OS** | Windows 10 64-bit (Build 19041+) | Windows 11 64-bit (Latest version) |
| **Processor** | Intel Core i5 (8th Gen+) or AMD Ryzen 5 | Intel Core i7 / i9 (11th Gen+) or AMD Ryzen 7 / 9 |
| **Memory (RAM)** | 8 GB RAM | 16 GB+ RAM |
| **Graphics (GPU)** | Intel UHD Graphics 630 / Dedicated GPU | NVIDIA GeForce GTX 1660 / RTX Series or AMD Radeon RX 5000+ |
| **Storage** | 1 GB available space for app | SSD with 10 GB+ free space for project cache and exports |

---

## Updates

PilotCut includes automatic update checks. When a new version is released:
- You will receive an in-app update notification.
- You can also manually download the latest version from the [Releases Page](https://github.com/pilotcut/pilotcut-windows-releases/releases).

---

## Community & Support

This repository hosts installers and releases only. It is not a product issue tracker.

- **Official Website**: [https://pilotcut.com](https://pilotcut.com)
- **Support & Feedback**: [support@pilotcut.com](mailto:support@pilotcut.com)
- **Twitter / X**: [@PilotCutCom](https://x.com/PilotCutCom)

---

## License

PilotCut for Windows is proprietary software. Please refer to the End User License Agreement (EULA) included in the installer for licensing terms.

---

<p align="center">Made by the <a href="https://pilotcut.com">PilotCut Team</a></p>
