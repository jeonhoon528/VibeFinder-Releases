# VibeFinder 0.9.2 Beta

VibeFinder is a Windows audio workflow application for searching and previewing large sound libraries, processing sounds through a VST3 FX Rack, and transferring results to REAPER.

## Download

Open the repository's **Releases** section to find the Windows x64 installer, portable ZIP, and release notes. Executable files are provided as release assets.

## Preview

[![VibeFinder Preview](https://img.youtube.com/vi/dGxa4dQWqgI/maxresdefault.jpg)](https://www.youtube.com/watch?v=dGxa4dQWqgI)

[Watch the VibeFinder preview on YouTube](https://www.youtube.com/watch?v=dGxa4dQWqgI)

## What's new in 0.9.2 Beta

- Drop a local library folder anywhere in the VibeFinder window to register it in Library and start scanning. Multiple folders are queued and scanned in order.
- Scan preparation no longer checks every previously indexed file before starting a new folder. Library refresh and context menu work are kept responsive during scans.
- Configure shortcuts to show or hide the Library, Folders, Tags, Related Tags, Sample Information, and Audio File Metadata sections. These shortcuts are unassigned by default; set them in **Preferences → Shortcuts → Sections**.

## Features

- Fast audio sample library search and management
- Waveform selection and transient-region workflows
- VST3 FX Rack preview
- Nondestructive REAPER transfer and integration
- Tags, folders, notes, settings, and saved layouts
- VibeAnalyzer views for Windows output: Waveform, Oscilloscope, Spectrogram, Spectrum, Stereo, and Loudness

VibeAnalyzer uses Windows loopback capture. Audio routed only through ASIO or another exclusive device path may not be available to it.

## Installation

1. Download `VibeFinder-0.9.2-Beta-Setup.exe` or `VibeFinder-0.9.2-Windows-x64.zip` from **Releases**.
2. Run the installer, or extract the complete portable ZIP into a new folder.
3. Launch `VibeFinder.exe`.

- Supported systems: Windows 10/11, 64-bit.
- Commercial VST3 plug-ins and REAPER are not included.
- This Beta is not code-signed, so Windows may show an Unknown Publisher or SmartScreen warning.
- Back up important settings and library data before testing a Beta release.

## Integrity

Installer SHA-256:

```text
1268EAA74CB31972AF5F1995FAA3D196224D9ABE1D1989FE403BE61DF5316CD6
```

SHA-256 hashes for every release asset are provided in `SHA256SUMS.txt` alongside the download files.

## License and copyright

Copyright © 2026 JEONHOON. All rights reserved.

VibeFinder is proprietary software. The installer and application package include end-user terms and third-party license notices. Corresponding QtBase and QtSvg source archives are provided with the release for license compliance.
