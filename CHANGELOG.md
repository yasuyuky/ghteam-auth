# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog][keep a changelog] and this project adheres to [Semantic Versioning][semantic versioning].

## [Unreleased]

### Changed

- tokio 1.0

---

## [Released]

## [0.3.1] - 2020-08-12

### Changed

- Tweak PAM settings
- Update depnedencies

### Fixed

- Use the abusolute path for conffiles

## [0.3.0] - 2020-06-16

### Added

- Notify Systemd

### Changed

- Update the rust version
- Handle the send-back error
- Update default AuthorizedKeysCommand style
- Update depnedencies

## [0.2.0] - 2020.05.30

### Added

- Enhance rate limit information

### Fixed

- Rewrite all hyper-related methods to asynchronous ones

### Changed

- Make http client reusable
- Update some depnedencies

## [0.1.0] - 2020.05.16

### Added

- Initial release

---

<!-- Links -->

[keep a changelog]: https://keepachangelog.com/
[semantic versioning]: https://semver.org/

<!-- Versions -->

[unreleased]: https://github.com/yasuyuky/sectora/compare/v0.3.0...HEAD
[released]: https://github.com/yasuyuky/sectora/releases
[0.3.0]: https://github.com/yasuyuky/sectora/compare/v0.3.0...v0.3.1
[0.3.0]: https://github.com/yasuyuky/sectora/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/yasuyuky/sectora/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/yasuyuky/sectora/releases/v0.1.0
