# VibeFinder 0.9.3 Beta

VibeFinder is a Windows audio workflow application for searching and previewing large sound libraries, processing sounds through a VST3 FX Rack, and transferring results to REAPER.

## Get VibeFinder

Visit the [VibeFinder Releases page](https://github.com/jeonhoon528/VibeFinder-Releases/releases) for the latest Windows x64 installer, release notes, and version details.


## Preview

[![VibeFinder Preview](https://img.youtube.com/vi/dGxa4dQWqgI/maxresdefault.jpg)](https://www.youtube.com/watch?v=dGxa4dQWqgI)

[Watch the VibeFinder preview on YouTube](https://www.youtube.com/watch?v=dGxa4dQWqgI)

## Features

- Fast audio sample library search and management
- Waveform selection and transient-region workflows
- VST3 FX Rack preview
- Nondestructive REAPER transfer and integration
- Tags, folders, notes, settings, and saved layouts
- VibeAnalyzer views for Windows audio output: Waveform, Oscilloscope, Spectrogram, Spectrum, Stereo, and Loudness

## What's New in 0.9.3 Beta

- **Update notifications:** VibeFinder checks GitHub Releases on the first launch of each local calendar day, including published Beta versions.
- **Title-bar update tag:** Click **NEW VERSION AVAILABLE** to open update settings. Customize its text, background, and border in **Preferences → Colors**; text and border default to yellow (`#FFFF00`).
- **Updates & Community:** See current and latest release versions side by side, check manually, and open GitHub Releases or Discord from Preferences.
- **Simplified settings:** Removed the Beta checkbox, release-note box, and Preferences footer Close button.

## Installation

1. Download `VibeFinder-0.9.3-Beta-Setup.exe` from the [Releases page](https://github.com/jeonhoon528/VibeFinder-Releases/releases).
2. Run the installer and follow the installation instructions.
3. Launch VibeFinder.

### Requirements and Notes

- Supports Windows 10/11, 64-bit.
- Commercial VST3 plug-ins and REAPER are not included.
- This beta is not code-signed. Windows may display an Unknown Publisher or SmartScreen warning.
- Back up important settings and library data before testing a beta release.

## VibeAnalyzer Quick Guide

<img width="1783" height="1122" alt="VibeAnalyzer interface" src="https://github.com/user-attachments/assets/31d199a7-9b61-4cdc-ac50-a37f40b39b39" />

VibeAnalyzer visualizes Windows audio output using loopback capture. Audio routed exclusively through ASIO or another exclusive device path may not be available to it.

### Controls

| Action | How to Use |
| --- | --- |
| Open or close | Toggle **VibeAnalyzer** from the sidebar. |
| Configure a section | **Right-click** a section to open its settings. Each section can be customized individually. |
| Move the window | **Left-click and drag** a section to move the window. |
| Reorder sections | **Click and hold, then drag** a section to change its position in the section order. |

## Download Integrity

SHA-256 for `VibeFinder-0.9.3-Beta-Setup.exe`:

```text
083e3a98cda0eb12bd1811531dc70c608a60d7f72075dc6263d790bc3fbd5e8a
```

Checksums for the installer and Qt source archives are available in `SHA256SUMS.txt` on the Releases page.

## License and Copyright

Copyright © 2026 JEONHOON. All rights reserved.

VibeFinder is proprietary software. The installer and application package include end-user terms and third-party license notices. Corresponding QtBase and QtSvg source archives are provided with the release for license compliance.
