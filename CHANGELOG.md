# Changelog

All notable changes are documented here.
Format follows keepachangelog.com, versions are semver-ish.

## [0.2.8] - 2026-07-17

### Fixed
- crash on paths containing spaces
- edge case when the input list is empty

### Changed
- progress output now goes to stderr

## [0.1.0] - 2026-04-08

### Added
- real rate limiting: sliding windows on requests/min and tokens/min
