# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.0.1](https://github.com/KristjanESPERANTO/MMM-SystemTemperature/compare/v2.0.0...v2.0.1) - 2025-09-10

- chore: update devDependencies
- docs: add Code of Conduct and contributing guidelines to README.md
- docs: improve module description in README.md

## [2.0.0](https://github.com/KristjanESPERANTO/MMM-SystemTemperature/compare/v1.0.0...v2.0.0) - First Release from Kristjan ESPERANTO - 2025-08-31

### Added

- chore: add ESLint and prettier setup
- docs: add CHANGELOG.md
- docs: add screenshot

### Changed

- chore: rename module to `MMM-SystemTemperature`
- refactor: use `systeminformation` library instead of external commands - with that we are **platform-independent**.
- refactor: replace lodash with custom JavaScript throttle
- refactor: cleaner, more maintainable codebase with async/await
- docs: updated and formatted README

## [1.0.0](https://github.com/KristjanESPERANTO/MMM-SystemTemperature/releases/tag/v1.0.0) - Last Release from MichMich - 2023-10-31

- Basic temperature monitoring for Raspberry Pi
- Warning and critical temperature alerts
- Shutdown capability via MMM-Remote-Control
- Celsius, Fahrenheit, and Kelvin support
- Basic lodash-based throttling
