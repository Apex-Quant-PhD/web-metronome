# Changelog

All notable changes to **Web Metronome** will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] — 2026-04-25

### Added

- Web Audio API (WAA) look-ahead scheduler for jitter-free clicks.
- Visual beat indicator with animated dots.
- BPM slider and numeric input (range 20–300).
- Configurable time signature: beats per measure 2–12, beat value 4 or 8.
- Subdivision options: None, 8ths, Triplets, 16ths.
- Accent toggle for beat 1.
- Tap Tempo (button or `T` key).
- Tap-to-Set Time Signature (button or `G` key).
- Tap-Train Recorder: record, play back, and export rhythm patterns as JSON.
- Preset system: Save, Load, Delete — persisted in `localStorage`.
- Export / Import presets as `.json` files.
- Full keyboard shortcuts (Space, Up/Down, Shift+Up/Down, T, G, R, A).
- Responsive, dark-themed, mobile-friendly UI.
- Single-file architecture — zero dependencies.
- MIT License.
- README with features, shortcuts, quick-start, and GitHub Pages instructions.
- CONTRIBUTING.md with ground rules and PR workflow.
- SVG metronome icon and PNG favicons (32 px, 512 px).
