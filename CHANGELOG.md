# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/).

## [Unreleased]

## [1.6] - 2017-08-03
### Added
- Added gzip support
- Added chunking support for queries
- Added possibility to configure  connect, read, and write timeouts
### Changed
- Update to Spring Boot `1.5.3.RELEASE`
- Updated to latest `influxdb-java` version

## [1.5] - 2017-01-18
### Added
- Added Docker Compose configuration to launch a InfluxDB test environment
### Changed
- Updated to latest `influxdb-java` version

## [1.4] - 2016-07-06
### Added
- Added `DefaultInfluxDBTemplate` implementation to simply handle `Point` objects from `influxdb-java`

## [1.3] - 2016-07-06
### Added
- Example application
### Changed
- Refactoring to use a "better" conversion strategy

## [1.2] - 2016-06-14
### Changed
- Fixed typos

## [1.1] - 2016-04-04
### Added
- Documentation and examples
### Changed
- Refactoring and improvements to use the template and its converters

## 1.0 - 2016-04-02
### Added
- Basic Spring Data integration with the official `influxdb-java` library
- Generic template (`InfluxDBTemplate`) to interact with InfluxDB

[Unreleased]: https://github.com/miwurster/spring-data-influxdb/compare/spring-data-influxdb-1.6...HEAD
[1.6]: https://github.com/miwurster/spring-data-influxdb/compare/spring-data-influxdb-1.5...spring-data-influxdb-1.6
[1.5]: https://github.com/miwurster/spring-data-influxdb/compare/spring-data-influxdb-1.4...spring-data-influxdb-1.5
[1.4]: https://github.com/miwurster/spring-data-influxdb/compare/spring-data-influxdb-1.3...spring-data-influxdb-1.4
[1.3]: https://github.com/miwurster/spring-data-influxdb/compare/spring-data-influxdb-1.2...spring-data-influxdb-1.3
[1.2]: https://github.com/miwurster/spring-data-influxdb/compare/spring-data-influxdb-1.1...spring-data-influxdb-1.2
[1.1]: https://github.com/miwurster/spring-data-influxdb/compare/spring-data-influxdb-1.0...spring-data-influxdb-1.1
