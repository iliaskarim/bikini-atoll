# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.1] - 2026-10-11

### Fixed

- Flattened TextMate and semantic token colors to `#dadada` so identifier scopes (e.g. function names) stay monochrome instead of inheriting Dark+ hues.
- Neutralized unused-code fade via `editorUnnecessaryCode.opacity` / `border` so unused symbols are not dimmed relative to other text.
- Set `editorBracketMatch.border` transparent so matching braces use a subtle background wash only (no outline box).
- Raised cursor contrast (`editorCursor.foreground` / `background`) for a visible block caret on `#181818`.
- Flattened `symbolIcon.*` and breadcrumb foregrounds to `#dadada` so outline/breadcrumb chrome does not tint symbol names.

### Added

- Marketplace README screenshot showing Bikini Atoll in the editor with the terminal open.

## [1.0.0] - 2024-01-01

### Added

- Initial release: Bikini Atoll dark theme based on Cursor Dark with no syntax highlighting.
