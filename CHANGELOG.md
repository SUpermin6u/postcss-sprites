# Change Log

## [3.2.0] - 2016-07-18
### Changed
- Use ``Result.warn`` API instead of ``console.warn``
- Publish the original source to npm

## [3.1.2] - 2016-04-11
### Fixed
- Typescript support

## [3.1.1] - 2016-03-23
### Fixed
- NaN paddings in retina sprites

## [3.1.0] - 2016-02-04
### Added
- Tests for examples
- Info logs

### Changed
- 'Usage' example

### Fixed
- Typos in examples

## [3.0.3] - 2016-01-20
### Fixed
- Fix "Fix: Broken CommonJS export"

### Changed
- Add note in README how to require properly the module

## [3.0.2] - 2016-01-20
### Fixed
- Broken CommonJS export

## [3.0.1] - 2016-01-19
### Fixed
- Typos in README
- Typos in plugin output

### Removed
- Unused code for responsive sprites

## [3.0.0] - 2016-01-18
### Added
- ``basePath`` option
- ``relativeTo`` option
- ``hooks`` option

### Changed
- Move spritesmith options in their own object called ``spritesmith``

### Removed
- ``skipPrefix`` option - see [Skip Prefix](examples/skip-prefix.md)
- ``outputDimensions`` option - see [Output Dimensions](examples/output-dimensions.md)
- ``verbose`` option

## [2.0.3] - 2016-01-06
### Changed
- Revert ``styleFilePath`` behaviour

### Fixed
- Scan regex

## [2.0.2] - 2015-10-30
### Changed
- Make ``styleFilePath`` relative to specific file

## [2.0.1] - 2015-09-23
### Changed
- Use ``Node.remove`` instead of ``Node.removeSelf``

## [2.0.0] - 2015-08-28
### Added
- Support for PostCSS@5

## [1.0.9] - 2015-07-20
### Added
- `outputDimensions` option
- `skipPrefix` option

## [1.0.8] - 2015-07-08
### Fixed
- Bug with paths in CSS output

## [1.0.7] - 2015-06-29
### Fixed
- Bug with multiple background-size properties

## [1.0.6] - 2015-06-09
### Added
- `stylesheetPath` option

### Changed
- ``spritePath`` option

### Removed
- ``externalStylesheet`` option
- ``baseUrl`` option
- ``spriteName`` option

## [1.0.5] - 2015-06-08
### Added
- Support for JPEG/JPG sprites

### Fixed
- Typos in README

## [1.0.4] - 2015-06-05
### Fixed
- Bug with background declarations inside ``AtRule`` nodes

## [1.0.3] - 2015-06-01
### Added
- Support for rgb & rgba colors

### Changed
- Date format in CHANGELOG

## [1.0.2] - 2015-06-01
### Added
- Tests
- Travis CI integration
- `baseUrl` option

### Fixed
- Bug with unused tokens
- Bug with groupBy & filterBy functions with gulp
- CSS properties order in output stylesheet

## [1.0.1] - 2015-05-28
### Fixed
- ``verbose`` option
- Confusing parts in README
- Bug with spriteRef


## [1.0.0] - 2015-05-27
### Added
- Initial version
