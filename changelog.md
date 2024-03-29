# Changelog
All notable changes to `cnj-tracing-resources` will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [2.0.1] - 2023-11-14
### Fixed
- solved issue with postgres secret which must only be created once and never be changed afterwards

## [2.0.0] - 2023-11-13
### Changed
- completely reworked management of helm charts

## [1.3.0] - 2023-06-09
### Changed 
- consolidated with other showcases

## [1.2.1] - 2023-05-22
### Fixed
- fixed broken configuration of postgres secret values in buildspec.yml

## [1.2.0] - 2022-11-14
### Added
### Changed
- upgraded to Bitnami PostgreSQL chart version 12.1.2
- fixed broken configuration of Helm chart resulting in duplicate postgres secrets in Kubernetes

## [2.0.0] - 2022-03-04
### Added
### Changed
- first re-release after repository split
