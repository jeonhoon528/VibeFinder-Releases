# VibeFinder 0.9.1 Beta

VibeFinder is a Windows audio workflow application for searching and previewing large sound libraries, processing sounds through a VST3 FX Rack, and transferring results to REAPER.

## Download

Open the repository's **Releases** section to find the Windows x64 download and its release notes. Executable files are provided as release assets.

## Preview

[![VibeFinder Preview](https://img.youtube.com/vi/dGxa4dQWqgI/maxresdefault.jpg)](https://www.youtube.com/watch?v=dGxa4dQWqgI)

[Watch the VibeFinder preview on YouTube](https://www.youtube.com/watch?v=dGxa4dQWqgI)

## What's new: VibeAnalyzer

VibeAnalyzer captures the Windows output stream and visualizes audio playing from browsers, VibeFinder, media players, and DAWs routed through the Windows output device.

- Waveform with scrolling/synchronized views, channel modes, and multiband color
- Oscilloscope with cycle, pitch, gain, and channel controls
- Spectrogram with FFT size, scale, detail, speed, range, contrast, low-frequency boost, and palette settings
- Spectrum with FFT line, level-colored bars, Both mode, logarithmic frequency grids, smoothing, and line-width controls
- Stereo with Imager, Lissajous, and X-Y views plus multiband point colors
- Loudness with LUFS Short-Term and separate left/right peak meters
- Resizable, reorderable, and detachable analyzer sections
- Frameless independent window, monitor-edge snapping, and docking above or below VibeFinder
- Startup restoration and VibeFinder layout-slot storage for visibility, geometry, docking, settings, theme, and detached sections

ASIO-exclusive or other device-exclusive audio paths may not be available to Windows loopback capture.

## Other features

- Fast audio sample library search and management
- Waveform selection and transient-region workflows
- VST3 FX Rack preview
- Nondestructive REAPER transfer and integration
- Tags, folders, notes, settings, and saved layouts

## Installation

1. Open **Releases** and download the Windows x64 setup or portable ZIP asset.
2. For the setup, run the installer and follow its instructions.
3. Launch VibeFinder.

Alternatively, extract the complete portable ZIP into a new folder and run `VibeFinder.exe`.

- Supported systems: Windows 10/11, 64-bit
- Commercial VST3 plug-ins and REAPER are not included and must be installed separately when needed.
- This Beta is not code-signed, so Windows may show an Unknown Publisher or SmartScreen warning.
- Back up important settings and library data before testing a Beta release.

## Integrity

Installer SHA-256:

```text
09D1F0660BE813CAF2185CE8FA51DA37E9E2A57B665C7E5622BEB142BC4E1153
```

Hashes for every release asset are included in `SHA256SUMS.txt`.

## License and copyright

Copyright © 2026 JEONHOON. All rights reserved.

VibeFinder is proprietary software. The installer and application package include the end-user terms and third-party license notices. Corresponding QtBase and QtSvg source archives are supplied with the release for license compliance.
