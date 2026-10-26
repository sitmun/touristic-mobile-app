# Changelog

## [Unreleased]

### Changed

- **Android**: Capacitor 8 targets API 36. HTTP calls use `CapacitorHttp`. SQLite uses `sqlcipher-android` 4.17.0 so native libraries align to 16 KB.

### Fixed

- **Near me / GPS**: Location reads call `Geolocation.requestPermissions`. Denied access opens Android Location settings (not only application details) so GPS can be enabled. `cap sync` registers the Geolocation plugin ([#5](https://github.com/sitmun/touristic-mobile-app/issues/5)).
- **Layout**: Tablet landscape menu icons no longer overlap; tree list titles wrap and descriptions stay visible; toolbar titles ellipsize beside the language select ([#3](https://github.com/sitmun/touristic-mobile-app/issues/3)).
