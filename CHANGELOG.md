# Changelog
All notable changes to this project will be documented in this file.

## [0.57.0] - 2018-06-08
### Changed
- Improve matching of synonyms
- Improve caching strategy for builtin entity parsing
- Improve intent classification
- Bump model version to `0.15.0`
- Bump `snips-nlu-ontology` to `0.57.0`

## [0.56.1] - 2018-05-18
### Changed
- Improve calibration of intent classification probabilities
- Update the `IntentParser` API and keep only `parse` method, while removing `get_intent` and `get_slots`
- DeterministicIntentParser: Replace tokenized out characters with whitespaces to improve matching

### Fixed
- DeterministicIntentParser: Fix issue with ranges of custom slots appearing after builtin slots

## [0.56.0] - 2018-05-03
### Changed
- Change ffi signatures
- Update swift project to Xcode 9.3
- Bump snips-nlu-ontology to `0.55.0`

## [0.55.2] - 2018-04-20
### Changed
- Make configurations and pipeline objects public
- Bump snips-nlu-ontology to `0.54.3`

### Fixed
- Bug with prefix and suffix features

## [0.55.1] - 2018-04-10
### Added
- Add support for the `length` feature function in slot filling feature extractrion

### Changed
- Bump ontology from `0.54.1` to `0.54.2`

## [0.55.0] - 2018-04-05
### Added
- Add ability to create an NLU engine directly from a file

### Fixed
- Fix issue with builtin entities during slot filling

### Changed
- Bump model version from `0.13.0` to `0.14.0`
- Improve intent classification by leveraging builtin entities
- Improve support for japanese
- Rename python package to `snips_nlu_rust`


[0.57.0]: https://github.com/snipsco/snips-nlu-rs/compare/0.56.1...0.57.0
[0.56.1]: https://github.com/snipsco/snips-nlu-rs/compare/0.56.0...0.56.1
[0.56.0]: https://github.com/snipsco/snips-nlu-rs/compare/0.55.2...0.56.0
[0.55.2]: https://github.com/snipsco/snips-nlu-rs/compare/0.55.1...0.55.2
[0.55.1]: https://github.com/snipsco/snips-nlu-rs/compare/0.55.0...0.55.1
[0.55.0]: https://github.com/snipsco/snips-nlu-rs/compare/0.54.0...0.55.0
