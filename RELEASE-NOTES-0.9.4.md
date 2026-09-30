# VibeFinder 0.9.4 Beta

## What's New

- **Faster library rescans:** compare the current file list with a bulk snapshot of saved records before reading metadata, then process only added, changed, or incomplete entries.
- **Targeted scanning:** scan a selected subfolder without rescanning the rest of the library, or force a full metadata refresh when needed.
- **Safer change detection:** track more precise modification times, preserve user data, and protect records when scanning is canceled or a drive becomes unavailable.
- **Clearer scan progress:** show added, update, unchanged, and missing-candidate counts; retry the same scope and scan mode.
- **Language consistency:** improved Korean and English descriptions, tooltips, and messages according to the selected language. Feature names remain in English. Restart the app after changing the language.

## Library Scanning

| Action | How to Use |
| --- | --- |
| Update a library | **Right-click a library → Rescan Library** to refresh added or changed files while skipping unchanged files. |
| Update a folder | **Right-click a library subfolder → Rescan Folder** to check changes only within that folder. |
| Scan a new subfolder | **Right-click a library → Scan Subfolder…**, then select a folder inside that library. |
| Rebuild file metadata | **Right-click a library or subfolder → Force Rescan** to reread all audio files in that scope, even if unchanged. |
| View progress | The scan window shows added files, files to update, unchanged files, and missing candidates. |

Rescanning still checks the file list in the selected scope. Missing files are marked unavailable only after a completed scan; inaccessible folders and interrupted scans are protected from incorrect missing-file updates. Your notes, tags, and favorites are preserved.
