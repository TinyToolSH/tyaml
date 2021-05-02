# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

### Fixed

### Changed

### Removed

## [0.1.0] - 2021-05-02

### Added

* This CHANGELOG file to hopefully serve as an evolving example of a 
standardized open source project CHANGELOG.
* Added quotes to variables
* Added templates to repository
* Added makefile to tyaml
* Added licence file to tyaml
* Added xargs to remove space from values
* Added remove_value function on get_keys
* Added tyaml script to repository
* Added get keys and get values functions
* added licensing disclaimer + testing code snippet on README
* added option to get values by especifing path [tsearch] implemeted yaml config file
* added comments and personal listing

### Fixed

- Fixed sed error when trying to read a file with spaces in his filename.
* Fixed the empty line bug

### Changed

* improved params checking 
* abstracted awk command as functions, for the sake of sanity reading and maintenance
* prints keys without repetition
* made sure to print keys with no duplicates
* made able to get the first key name of yaml tree by just executing tyaml FILE -k
* implemented function do get keys in a specific node of yaml file, for real this time
* tweaks on yaml parser
* incorporated external yaml parser

### Removed

* Removed unnecessary files from tyaml folder.

[unreleased]: https://github.com/TinyToolSH/tyaml/compare/0.1.0...HEAD
[0.1.0]: https://github.com/TinyToolSH/tyaml/releases/tag/0.1.0

