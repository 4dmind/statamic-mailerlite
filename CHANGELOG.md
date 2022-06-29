# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.0] - 2020-05-02
### Added
- Entirely re-factored codebase from our earlier MailerLite for Statamic v2 addon

## [0.1.1] - 2020-05-03
### Security
- Minor security update to fix composer advisories, added requirement for composer 2.2 or higher

## [0.1.2] - 2020-06-27
### Removed
- Dedicated Marketing Permissions field was removed
- 
### Fixed
- Check added for if subscriber group exists to avoid error when one is deleted on MailerLite that is saved locally

## [1.0.0] - 2020-06-28
### Changed
- Updated Forma to use v1.2

### Fixed
- Issue on checking for deleted subscriber groups resolved
