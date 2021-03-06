# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

### Changed
- Clean up projects file
- Define the endpoint signatures in the backend API
- Abstract file access behind a FileStorage provider
- Use exact versions for SPM dependencies
- Schedule the EN background task to run max 6 times a day to prevent it being run excessively by the system
- Suppress any errors encountered while updating the municipality list in the background task

### Added
- REST API tests
- Improved BatchRepository test coverage
- Proper TEK generation in MockExposureManager
- Git commit hash to version information in Settings view
- Show the change log in Xcode workspace

## 1.0.1

### Added
- Prefilling authorization code from SMS in case Koronavilkku is not running in background

### Fixed
- Fixed typos in Swedish localizations

### Changed
- Dummy code generation uses
