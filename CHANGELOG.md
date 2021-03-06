# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.3.0] - 2019-04-14
### Changed
- **BREAKING**: States are now stored in a provider component. Every component that wants to use connected reducers has to be an ancestor of this `ConnectedProvider`. This provides an easy way to debug connected states via React Dev Tools.
- **BREAKING**: Namespaces are not allowed to be an array anymore, but have to be strings.

## [0.2.0] - 2019-03-25
### Changed
- Internal refactoring that leads to less memory usage and better performance

## [0.1.1] - 2019-03-24
### Added
- `useConnectedReducer` – A React Hook to share state between components

[Unreleased]: https://github.com/pmk1c/react-connected-reducers/compare/v0.3.0...HEAD
[0.3.0]: https://github.com/pmk1c/react-connected-reducers/releases/tag/v0.3.0
[0.2.0]: https://github.com/pmk1c/react-connected-reducers/releases/tag/v0.2.0
[0.1.1]: https://github.com/pmk1c/react-connected-reducers/releases/tag/v0.1.1
