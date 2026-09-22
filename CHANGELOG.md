# Changelog

All notable changes to this project will be documented here.

## [Unreleased]

### Changed

- Use capability checks for `AssistantMessageComponent` so compatible Pi minor releases do not require version allowlist updates.
- Added support for Pi 0.87.x.

## [0.1.0] - 2026-08-20

### Added

- `/raw`, `/raw on`, and `/raw off` commands.
- `Alt+R` shortcut for silent raw-mode toggling.
- User-configurable shortcut through `~/.pi/agent/pi-raw-mode.json`.
- Literal, unstyled, zero-added-padding assistant rendering.
- Streaming, restored-session, Unicode wrapping, and stop-notice handling.
- Guarded Pi renderer patch with clean fallback and reload-safe teardown.

[Unreleased]: https://github.com/fanzeyi/pi-raw-mode/compare/v0.1.0...HEAD
[0.1.0]: https://github.com/fanzeyi/pi-raw-mode/releases/tag/v0.1.0
