# VibeFinder 0.9.5 Beta

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

## What's New in 0.9.5 Beta

- **In-app updates:** download a compatible release from Preferences → Updates & Community, then choose **Restart and update**. Downloads are checked against the size and SHA-256 digest supplied by GitHub before installation.
- **Per-user installation:** installs under your Windows account and includes the required Microsoft runtime DLLs beside the app, avoiding an elevated runtime installer during normal updates.
- **Release notes after updating:** opens the installed version's release page once after a successful in-app update. **Current version release notes** opens it again at any time.
- **Recovery:** if installation or the new application's startup fails, the updater attempts to restore the previous program files, registration, and shortcuts. Existing library data and settings are retained.

## Upgrading from 0.9.4 or earlier

Install `VibeFinder-0.9.5-Beta-User-Setup.exe` once to receive the new updater. Future compatible releases can be installed from within VibeFinder. An older all-users installation is retained until removed separately.

| Action | How to Use |
| --- | --- |
| Download an update | Open **Preferences → Updates & Community** and select **Download update** when a compatible newer release is available. |
| Apply an update | Select **Restart and update** after the download has been verified. |
| Cancel a download | Select **Cancel download** while the update is being downloaded. |
| Read release notes | Select **Current version release notes**. After an in-app update, this page opens automatically once. |


## Library Scanning

| Action | How to Use |
| --- | --- |
| Update a library | **Right-click a library → Rescan Library** to refresh added or changed files while skipping unchanged files. |
| Update a folder | **Right-click a library subfolder → Rescan Folder** to check changes only within that folder. |
| Scan a new subfolder | **Right-click a library → Scan Subfolder…**, then select a folder inside that library. |
| Rebuild file metadata | **Right-click a library or subfolder → Force Rescan** to reread all audio files in that scope, even if unchanged. |
| View progress | The scan window shows added files, files to update, unchanged files, and missing candidates. |

Rescanning still checks the file list in the selected scope. Missing files are marked unavailable only after a completed scan; inaccessible folders and interrupted scans are protected from incorrect missing-file updates. Your notes, tags, and favorites are preserved.

## Installation

1. Download `VibeFinder-0.9.5-Beta-User-Setup.exe` from the [Releases page](https://github.com/jeonhoon528/VibeFinder-Releases/releases).
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

SHA-256 for `VibeFinder-0.9.5-Beta-User-Setup.exe`:

```text
cc29e32a4c9c4a403e9d0abb223684aed0ea89d6c60c958db885521031e5ca5b
```

Checksums for the installer and Qt source archives are available in `SHA256SUMS.txt` on the Releases page.

## License and Copyright

Copyright © 2026 JEONHOON. All rights reserved.

VibeFinder is proprietary software. The installer and application package include end-user terms and third-party license notices. Corresponding QtBase and QtSvg source archives are provided with the release for license compliance.
