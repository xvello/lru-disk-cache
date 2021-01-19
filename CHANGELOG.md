# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

The 0.5 version will bring a bunch of breaking changes to sanitize the API
and pave the way towards a stable 1.0.

### Removed
- The `lru_cache` module is not exported anymore, to allow swapping the
internal LRU logic in a future release
