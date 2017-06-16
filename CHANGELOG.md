# Change Log

## [1.0.0] - 2017-06-16
### Added
- Added `normalize` option to `mpeInstrument`.
- Added `pitch` option to `mpeInstrument`.
- Added `pitchBendRange` option to `mpeInstrument`.
- Added `clear` method to `mpeInstrument`.

### Changed
- `mpeInstrument` is now the default output of the module, rather than a named
export.
- `normalize` option is set to `true` by default – named properties are now
scaled rather than raw 14-bit integers.
- Extended documentation.

### Removed
- Removed `recorder` class.

[1.0.0]: https://github.com/WeAreRoli/mpejs/compare/v0.1.8...v1.0.0