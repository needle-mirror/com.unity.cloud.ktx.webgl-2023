# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0-pre.1] - 2023-08-30

## Changed
- Version bump to go out of experimental.

## [0.4.0] - 2023-08-23

### Changed
- Remove etcdec from the binaries

### Fixed
- Incorrect package name occurrences

## [0.3.0] - 2023-07-21

### Added
- Trademarks notice to documentation

### Changed
- Package name prefix to "KTX for Unity WebGL..."

## [0.2.0] - 2023-05-31

### Added
- Third party notice
- Full Apache 2.0 license text

### Changed
- When the main package is missing a warning is logged (instead of self-removal)
- Assembly definition names now include the version to avoid conflicts when multiple sub-packages are installed
- Unexposed `KtxUnity.Webgl.Editor.Tests.WebglEditorTests`
- Specified exact minimum required Unity version 2023.2.0a17

## [0.1.0] - 2023-05-26
Initial sub package publication
