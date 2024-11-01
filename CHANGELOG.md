# Changelog for My Terraform Module

## [Unreleased]
### Added
- New variable for customizing instance size.

### Changed
- Updated provider version to support the latest features.

### Deprecated
- Deprecated the `old_variable` in favor of `new_variable`.

### Fixed
- Fixed an issue where the output value was incorrect.

---

## [1.2.0] - 2024-11-01
### Added
- Added support for multi-region deployments.
- Introduced a new output for the public IP address.

### Changed
- Improved documentation for usage examples.
- Refactored the main.tf for better readability.

### Fixed
- Fixed a bug that caused the module to fail on variable validation.

---

## [1.1.0] - 2024-10-15
### Added
- Added an input variable for enabling/disabling logging.

### Changed
- Updated default values for input variables.

### Fixed
- Resolved an issue with state file management.

---

## [1.0.0] - 2024-09-01
### Added
- Initial release of the module.
- Support for basic EC2 instance creation with configurable settings.
