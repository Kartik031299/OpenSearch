# CHANGELOG
All notable changes to this project are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html). See the [CONTRIBUTING guide](./CONTRIBUTING.md#Changelog) for instructions on how to add changelog entries.

## [Unreleased 3.3.x]
### Added
- Add getWrappedScorer method to ProfileScorer for plugin access to wrapped scorers ([#20548](https://github.com/opensearch-project/OpenSearch/issues/20548))
- Support expected cluster name with validation in CCS Sniff mode ([#20532](https://github.com/opensearch-project/OpenSearch/pull/20532))
- Choose the best performing node when writing with append-only index ([#20065](https://github.com/opensearch-project/OpenSearch/pull/20065))
- Add security policy to allow `accessUnixDomainSocket` in `transport-grpc` module ([#20463](https://github.com/opensearch-project/OpenSearch/pull/20463))
- Add range validations in query builder and field mapper ([#20497](https://github.com/opensearch-project/OpenSearch/issues/20497))
- [Workload Management] Enhance Scroll API support for autotagging ([#20151](https://github.com/opensearch-project/OpenSearch/pull/20151))
- Add indices to search request slowlog ([#20588](https://github.com/opensearch-project/OpenSearch/pull/20588))
- Added support of WarmerRefreshListener in NRTReplicationEngine to trigger warmer after replication on replica shards ([#20650](https://github.com/opensearch-project/OpenSearch/pull/20650))

### Changed

### Fixed

### Dependencies

### Deprecated

### Removed

### Security

[Unreleased 3.3.x]: https://github.com/opensearch-project/OpenSearch/compare/e972d15...3.3
