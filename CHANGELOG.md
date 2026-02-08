# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [6.0.0] - 2026-02-08

### Added
- **New Syntax**: Introduced cleaner, human-readable syntax for loops and conditionals.
- **Dictionaries**: Full support for key-value `Dictionary` type with methods (`.get`, `.keys`, `.values`).
- **Lists**: Enhanced list operations (`.append`, `.pop`, `.sort`).
- **Math Module**: Added `solve` for algebraic equations and `plot` for graphing (via matplotlib).
- **ZPM**: Integrated Zyntax Package Manager for dependency management.
- **Standard Library**: Expanded file I/O `file read/create` and string manipulation `split/replace`.

### Changed
- **Performance**: Significant optimization in the interpreter core (removed legacy parsing overhead).
- **Error Handling**: Improved stack traces and `try/catch` error objects.
- **CLI**: Redesigned command-line interface with colorful output.

### Fixed
- Resolved memory leak in recursive function calls.
- Fixed variable scoping issues within nested loops.

## [5.0.0] - 2025-08-15
- Legacy release. See archive for details.
