# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [v1.4.1] - 25-07-2020
### Fixed
- Array index out of bounds exception caused by [empty API response](https://github.com/crazzyghost/alphavantage-java/issues/9) 

## [v1.4.0] - 13-06-2020
### Added
- Support for Sector Performances


## [v1.3.2] - 21-05-2020
### Fixed
- Maven build [issue](https://github.com/crazzyghost/alphavantage-java/issues/6)

## [v1.3.1] - 21-05-2020
### Fixed
- Multiple async requests for enpoint [bug](https://github.com/crazzyghost/alphavantage-java/issues/8)

## [v1.3.0] - 09-05-2020
### Added
- Support for Quote Endpoint
- Tests for TimeSeries
### Changed
- RequestHelper to RequestProxy for TimeSeries
### Fixed
- Time Series IntradayRequest interval bug
 

## [v1.2.1] - 07-05-2020
### Added
- Tests for Forex
### Changed
- RequestHelper to RequestProxy for Forex
### Fixed
- Forex IntradayRequest interval bug
### Removed
- Static builder methods
## [v1.2.0] - 05-05-2020
### Added
- Support for crypto currency Health Index
## [v1.1.1] - 04-05-2020
### Added
- Bid Rates and Ask Rates for Exchange Rates
### Fixed
- Exchange Rates response data access

## [v1.1.0] - 04-05-2020
### Added
- Support for Technical Indicators

## [v1.0.2] - 24-04-2020
### Fixed
- API url parameter [bug](https://github.com/crazzyghost/alphavantage-java/issues/4)

## [v1.0.1] - 17-04-2020
### Added
- CHANGELOG to keep track of releases
### Fixed
- [Incorrect mapping]((https://github.com/crazzyghost/alphavantage-java/issues/1)) of time series data
- Getters for Crypto and Forex Units
### Changed
- Rename crypto subpackages

## [v1.0.0] - 23-10-2019 (Unreleased)
### Added
- Support for Time Series Data
- Support for Forex Data
- Support for Crypto Currencies
- Support for Exchange Rates 
- Tests for Time Series
- README 

[1.4.0]: https://github.com/crazzyghost/alphavantage-java/releases/tag/1.4.0
[1.3.1]: https://github.com/crazzyghost/alphavantage-java/releases/tag/1.3.1
[1.3.2]: https://github.com/crazzyghost/alphavantage-java/releases/tag/1.3.2
[1.3.0]: https://github.com/crazzyghost/alphavantage-java/releases/tag/1.3.0
[1.2.1]: https://github.com/crazzyghost/alphavantage-java/releases/tag/1.2.1
[1.2.0]: https://github.com/crazzyghost/alphavantage-java/releases/tag/1.2.0
[1.1.1]: https://github.com/crazzyghost/alphavantage-java/releases/tag/1.1.1
[1.1.0]: https://github.com/crazzyghost/alphavantage-java/releases/tag/1.1.0
[1.0.2]: https://github.com/crazzyghost/alphavantage-java/releases/tag/1.0.2
[1.0.1]: https://github.com/crazzyghost/alphavantage-java/releases/tag/1.0.1
[1.0.0]: https://github.com/crazzyghost/alphavantage-java/tree/9d1cbca8a48899398513494ae6717bec0fa93cfb
[ajt001]: https://github.com/ajt001