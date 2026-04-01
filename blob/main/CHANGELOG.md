# POS System Changelog

All notable changes to this project will be documented in this file.

---

## [1.2.0] - 2026-04-01

### Added
- Update system improvements for old POS build.
- Safer update flow with better startup handling.
- Changelog support through GitHub page instead of Dropbox HTML.

### Fixed
- Fixed updater not starting correctly in the old POS build.
- Fixed XML parsing issue caused by raw `&` characters in Dropbox links.
- Fixed update detection flow so the app can properly read the update file.
- Fixed changelog display issue where Dropbox HTML opened as code/source.
- Improved updater stability for release build usage.

### Changed
- Installer download link now uses Dropbox direct download format.
- Changelog link moved to GitHub for cleaner display.
- Update XML format cleaned and corrected for AutoUpdater compatibility.

### Notes
- This release is focused on repairing and stabilizing the updater in the old POS version.
- Future releases will continue improving reliability, maintenance, and update safety.

---

## [1.1.0] - Previous Release

### Notes
- Previous stable version before updater fixes.
- Used as the base version for comparison in the update system.
