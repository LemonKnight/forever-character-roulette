# Changelog

## [1.1.2] – 2026-11-01

### Improved
- Added version-based cache busting for the JavaScript bundle to ensure new releases fetch updated application code.
- Display the current application version in a subtle footer.


## [1.1.1] – 2026-11-01

### Added
- Highlight empty filter categories with a red outline.
- Show an outline on the filter header when collapsed and a category is empty.

### Fixed
- Removed redundant requests for nonexistent specialization icons (`icons/specs/warrior-0.jpg`, etc.).
- Load specialization icons directly using their actual filenames.
- Retained the existing validation error message for invalid or empty selections.

## [1.1.0] – 2026-11-01

### Added
- English localization with automatic browser-language detection.
- Language selector (Auto / Deutsch / English), persisted in localStorage.
- Independent English surname pools.

### Improved
- Bidirectional class and specialization filter synchronization.
- German compound surname corrections.
- Language switching preserves current character and filter settings.
- GitHub Pages compatibility.

### Removed
- Obsolete `STARTEN.txt`.
