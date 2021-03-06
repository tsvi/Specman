# Specman syntax changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.3] - 2020-05-30
### Changed
- minor fix for struct member declaration
- removed module as keyword
- fixed struct/unit member decl.
- improved constraint matching

### Added
- matching of event declarations to member-declaration scope
- matching of sized-list decl.
- added curly braces to stray-bracket checks

## [1.0.2] - 2020-04-22
### Changed
- minor fixes for numeric literals
- fixes for preprocessor directives

### Added
- added numeric real literal
- added Specman.tmPreferences for toggle-comment feature

## [1.0.1] - 2019-12-12
### Changed
- minor fix to get correct scope for non-generatable attribute "!" in member-declaration
- minor improvements
### Added
- more keywords (built-in functions)

## [1.0.0] - 2019-10-23
### Changed
- Initial release
  Fork from Tsvi Mostovicz's version, major rework
