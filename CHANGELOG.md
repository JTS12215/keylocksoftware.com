# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [26.02.5] - 2026-02-16

### Added
- **Keyboard Shortcuts:**
  - Added `Enter` / `Return` key support to open/edit selected records in the main table.
  - Added `Ctrl + G` as a global shortcut to launch the password generator.
  - Added `Ctrl + L` as a dedicated shortcut to immediately lock the database and display the login screen.
  - Added `Ctrl + Q` as a global shortcut to safely exit the application.
  - Added `Ctrl + R` as a global shortcut to launch the recycle bin.
  - Added `Ctrl + U` as a global shortcut to check for updates.
  - Added `F1` support to launch the online documentation.
- **Help & Support System:**
  - Added "Report a Bug" menu item with automatic OS and Version detection for GitHub Issues.
  - Added "Suggest a Feature" menu item linking to GitHub enhancements.
  - Added "Check for updates menu item.
- **UI & Branding:**
  - Updated "About" dialog with high-resolution logo and clickable links to the official website and GPL v3 license.
  - Integrated live web-links for the User Manual and Support pages.

### Changed
- **Navigation Logic:** Unified the table interaction logic; `activated` signal now handles both double-clicks and keyboard navigation to prevent duplicate window instances.
- **Exit Logic:** Connected all exit paths to `closeEvent` to ensure window geometry and database state are saved regardless of how the app is closed.
- **Documentation:** Migrated local PDF help references to the new online documentation hub at `keylocksoftware.com`.

### Fixed
- Fixed an issue where double-clicking a record would occasionally open two instances of the Entry Form.
- Corrected a `TypeError` when using keyboard navigation to select table items.
- Fixed outdated copyright strings to reflect "KeyLock Password Manager" branding.
