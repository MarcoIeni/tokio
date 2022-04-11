# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.4.3] - 2022-04-11

### Other
- increase MSRV to 1.49. (#4457)
- update year in LICENSE files (#4429)
- fix version requirement of tokio-stream (#4376)
- remove doc URL from Cargo.toml (#4251)
- upgrade to new nightly (#4268)
- bump MSRV to 1.46 (#4254)
- document performance considerations (#3920)
- fix typos (#3907)
# 0.4.2 (May 14, 2021)

- test: add `assert_elapsed!` macro ([#3728])

[#3728]: https://github.com/tokio-rs/tokio/pull/3728

# 0.4.1 (March 10, 2021)

- Fix `io::Mock` to be `Send` and `Sync` ([#3594])

[#3594]: https://github.com/tokio-rs/tokio/pull/3594

# 0.4.0 (December 23, 2020)

- Track `tokio` 1.0 release.

# 0.3.0 (October 15, 2020)

- Track `tokio` 0.3 release.

# 0.2.1 (April 17, 2020)

- Add `Future` and `Stream` implementations for `task::Spawn<T>`.

# 0.2.0 (November 25, 2019)

- Initial release
