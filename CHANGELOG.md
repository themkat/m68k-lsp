# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.6.1] - 2022-05-13

### Fixed

- Replace bad wasm build

## 0.6.0 - 2022-15-12

### Added

- VASM diagnostics

### Changed

- Incremental tree-sitter updates not working correctly in neovim - disabled for now.
- Better merging of config with defaults
- Upgade tree-sitter-m68k

## [0.5.0] - 2022-05-08

### Added

- `autoExpand` option for alignment formatter. This allows automatic adjustment of component positions to allow for
  elements which exceed the available space.
- Operand spacing formatter. Add or remove space between operands as allowed in VASM with `-spaces` option.

### Changed

- Defaults for alignment now use spaces. This is more reliable as tab alignment can easily break if editor tab width
  doesn't match config.

### Fixed

- Handle string operands with spaces [@dansalvato](https://github.com/dansalvato).
