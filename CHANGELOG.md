# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

### Notes Template
Each issue fixed should contain one bullet summarizing the work done.

```
* [CIO-###](https://github.com/jwu910/check-it-out/issues/###) Description of work done
```

<hr />

## [Unreleased]
* [CIO-207](https://github.com/jwu910/check-it-out/issues/207) Changed homepage url in package json.
* [CIO-194](https://github.com/jwu910/check-it-out/issues/194) Added [Danger](https://danger.systems) to CIO.
* [CIO-210](https://github.com/jwu910/check-it-out/issues/210) Added regex for Danger rules.
* [CIO-213](https://github.com/jwu910/check-it-out/issues/213) Set up build stages for [TravisCI](https://travis-ci.org).
* [CIO-102](https://github.com/jwu910/check-it-out/issues/102) Add configurable options for user.


## [[0.8.0]](https://github.com/jwu910/check-it-out/releases/tag/v0.8.0) - 2018-07-05
### Notes
This release *should* make CIO faster. We added loading text so when you're working on a pretty large project, you're not stuck there wondering if you pressed enter or not.

### Added
* [CIO-187](https://github.com/jwu910/check-it-out/issues/187) Added stale bot to CIO.

### Changed
* [CIO-196](https://github.com/jwu910/check-it-out/issues/196) Changed how remotes were being listed

### Removed
* [CIO-190](https://github.com/jwu910/check-it-out/issues/190) Removed redux dependency.

### Fixed
* [CIO-56](https://github.com/jwu910/check-it-out/issues/56) Fixed the the way we parsed branch names to account for grouped branch names. Grouped branch names now display correctly.
* [CIO-200](https://github.com/jwu910/check-it-out/issues/200) Fixed regression bug where pressing `[r]` did not refresh the branches and made sure loading text displays while CIO awaiting git response.
