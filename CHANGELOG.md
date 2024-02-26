# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.2.1](https://github.com/alloy-rs/nybbles/releases/tag/v0.2.1) - 2024-02-26

### Documentation

- Add CHANGELOG.md and cliff.toml ([#10](https://github.com/alloy-rs/nybbles/issues/10))

### Features

- Import nybbles bench from reth
- Add SizeRange to proptest Arbitrary parameters

### Miscellaneous Tasks

- Add changelog script

## [0.2.0](https://github.com/alloy-rs/nybbles/releases/tag/v0.2.0) - 2024-02-26

### Bug Fixes

- Add an overflow check in unpack_heap ([#6](https://github.com/alloy-rs/nybbles/issues/6))
- Out-of-bound memory read on `Nibbles::get_byte` ([#4](https://github.com/alloy-rs/nybbles/issues/4))

### Features

- Make it clear when an invalid instance is created ([#8](https://github.com/alloy-rs/nybbles/issues/8))

### Miscellaneous Tasks

- Release 0.2.0
- Simplify slice implementation ([#7](https://github.com/alloy-rs/nybbles/issues/7))
- Update release.toml
- Update configs

### Other

- Add concurrency ([#9](https://github.com/alloy-rs/nybbles/issues/9))

### Performance

- Optimize usize::MAX check in get_byte ([#5](https://github.com/alloy-rs/nybbles/issues/5))

### Testing

- `arbitrary` feature separation ([#3](https://github.com/alloy-rs/nybbles/issues/3))

## [0.1.2](https://github.com/alloy-rs/nybbles/releases/tag/v0.1.2) - 2023-12-20

### Bug Fixes

- Assume macro

### Documentation

- Add logo

### Features

- More methods, examples

### Miscellaneous Tasks

- Release 0.1.2
- Rename macros

### Other

- Merge pull request [#1](https://github.com/alloy-rs/nybbles/issues/1) from dvush/pop-idx-mut
- Replace mut index with set_at
- Add mutable indexing, pop

## [0.1.1](https://github.com/alloy-rs/nybbles/releases/tag/v0.1.1) - 2023-12-15

### Features

- Implement Index

### Miscellaneous Tasks

- Release 0.1.1
- Add clippy.toml
- Add release.toml

### Other

- Master

## [0.1.0](https://github.com/alloy-rs/nybbles/releases/tag/v0.1.0) - 2023-12-15

### Documentation

- Add more examples
- Description

### Features

- Initial implementation

### Other

- Initial commit

### Performance

- Remove useless branch on smallvec heap init

<!-- generated by git-cliff -->