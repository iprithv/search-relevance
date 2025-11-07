# CHANGELOG

Inspired from [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)

## [Unreleased]

### Breaking Changes

### Features
* Added APIs and components to implement running scheduled experiments ([#220](https://github.com/opensearch-project/search-relevance/pull/220))

### Enhancements
* Support for adding description in Search Configuration ([#293](https://github.com/opensearch-project/search-relevance/pull/293))

### Bug Fixes
* Fixed floating-point precision issues in Hybrid Optimizer weight generation by switching to step-based iteration and rounding, ensuring clean and consistent weight pairs. ([#308](https://github.com/opensearch-project/search-relevance/pull/308))

### Infrastructure

* Use a system property to control run integ test with security plugin. [#287](https://github.com/opensearch-project/search-relevance/pull/287)

### Documentation

### Maintenance

### Refactoring
