# Changelog

## [Unreleased]

### Fixed

- **Near me / GPS**: Location reads call `Geolocation.requestPermissions`. Denied access opens Android Location settings (not only application details) so GPS can be enabled. `cap sync` registers the Geolocation plugin ([#5](https://github.com/sitmun/touristic-mobile-app/issues/5)).
