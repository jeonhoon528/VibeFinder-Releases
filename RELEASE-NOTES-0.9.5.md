# VibeFinder 0.9.5 Beta

## What's New

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

The installer remains unsigned; Windows security software may still display a warning. Recovery covers program files, not database schema rollback. A power failure or forced termination of the updater may require manual recovery from the retained backup folder.
