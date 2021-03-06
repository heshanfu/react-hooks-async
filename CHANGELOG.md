# Change Log

## [Unreleased]

## [1.2.0] - 2019-02-23
### Changed
- Rename useMemoSafe to useMemoPrev
  - Although this is technically a breaking change, we release it as a minor update.

## [1.1.0] - 2019-02-18
### Changed
- Improve useRef usage for concurrent mode

## [1.0.0] - 2019-02-10
### Changed
- Remove shallowequal dependency
- Remove helper hooks from index (breaking change)

## [0.8.0] - 2019-02-05
### Changed
- Do not use useMemo/useCallback as a semantic guarantee
- A naive useMemoSafe for axios config
- Fix null types
- short-hand hooks: useFetch, useAxios

## [0.7.0] - 2019-01-22
### Added
- useAsyncTaskWasm and useWasm

## [0.6.0] - 2019-01-15
### Changed
- Split type definition files in the src directory

## [0.5.0] - 2018-12-19
### Changed
- Aborts running tasks on unmount

## [0.4.0] - 2018-12-18
### Changed
- Make useAsyncTaskAxios optional (see examples/05_axios)

## [0.3.0] - 2018-12-16
### Added
- useAsyncCombineRace
### Changed
- Fix combine return type
- Fix useAsyncCombineAll

## [0.2.0] - 2018-12-14
### Added
- Add useAsyncTaskDelay
- Add useAsyncTaskAxios

## [0.1.0] - 2018-12-11
### Added
- Initial release
