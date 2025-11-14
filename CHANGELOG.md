# CHANGELOG

Inspired from [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)

## [Unreleased]

### Breaking Changes

### Features
* Added APIs and components to implement running scheduled experiments ([#220](https://github.com/opensearch-project/search-relevance/pull/220))

### Enhancements

### Bug Fixes

### Infrastructure

* Use a system property to control run integ test with security plugin. [#287](https://github.com/opensearch-project/search-relevance/pull/287)

### Documentation

### Maintenance
* Fixed duplicate JDWP configuration in the `integTest` Gradle task that caused `Cannot load this JVM TI agent twice` errors when running with `-Dtest.debug=1`. ([#296](https://github.com/opensearch-project/search-relevance/pull/296))

### Refactoring
