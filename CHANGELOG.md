# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) and this project adheres to 
[Semantic Versioning](http://semver.org/).

## 1.0.1

### Added

- make the service more resilient by setting `Restart=always`

### Fixed

- fix issue with service failure after reboot by adding dependency to varnish

## 1.0.0

### Added

- Everything. This is the initial release.
