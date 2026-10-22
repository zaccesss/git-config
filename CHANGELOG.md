# Changelog

All notable changes to this project are recorded here.

Format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).
Versioning follows [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [Unreleased]

## [0.0.1] - 2026-10-22

### Added

- `fetch.prune` and `pull.ff = only` in every platform config
- Initial release: gitconfig for macOS, Linux and Windows with SSH signing, credential helpers
  and hook wiring
- Setup and reference guides
- CI that validates every file parses

### Changed

- Tidied code comments and the contributor guide.

### Fixed

- Windows config points Git at the Windows OpenSSH client, so Git over SSH uses the same agent as
  `ssh`
