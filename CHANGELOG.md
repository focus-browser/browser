# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 1.0.0-a.84

### Added

- Note regarding maintenance to ReadMe

### Changed

- Updated to Firefox `120.0`
- Updated uBlock to `1.54.0`

## 1.0.0-a.84

### Changed

- Updated to Firefox `119.0`

## 1.0.0-a.83

### Changed

- Firefox updated to `118.0.1`
- Sidebar tabs no longer persist state on new profiles (can be reenabled in prefs)
- Assorted URLs now point to more correct / relevant locations

### Fixed

- Fix fetching new language packs (bug [#287](https://github.com/pulse-browser/browser/issues/287))
- Sidebar starts up on the correct side of the browser (bug [#277](https://github.com/pulse-browser/browser/issues/277))

## 1.0.0-a.82

### Changed

- Update uBlock to `1.52.2`

### Fixed

- Vertical tabs will correctly follow fullscreen state

## 1.0.0-a.81

### Changed

- Update Betterfox to `117.0`

### Fixed

- Improve contrast on pulse light and dark themes
- Assorted UI inconsistencies for vertical tabs
- Make vertical tabs visible in fullscreen (tested in sway)

## 1.0.0-a.80

### Changed

- Updated Gecko to `117.0.1`

## 1.0.0-a.79

### Changed

- Updated gecko to `117.0`
- Updated betterfox `116.1`

## 1.0.0-a.78

### Changed

- Updated gecko to `116.0.2` and all it causes

## 1.0.0-a.77

### Added

- Vertical tabs: Open new tab w/ clipboard contents on space middle click
- The new tab & close tab buttons can now be hidden

### Changed

- Vertical tabs: New tab button no longer has text
- Partial `:has` support is enabled (this is intended for userchrome use only)

### Fixed

- Pinned vertical tabs are no longer positioned. Sorta defeats their purpose, but it stops a semi-major bug
- Sidebar sites now appear on new windows
- Vertical tabs: New tab icon is now centered

## 1.0.0-a.75

### Changed

- Clean up vertical tab styles

### Fixed

- Fix tab movement

## 1.0.0-a.74

### Changed

- Update Firefox to `115.0.1`
- Update Betterfox

## 1.0.0-a.67 through 1.0.0-a.73

Fight with CI.

## 1.0.0-a.66

### Changed

- Update Firefox to `114.0.1`

## 1.0.0-a.65

### Changed

- Update Firefox to `113.0.1`

## 1.0.0-a.64

### Fixed

- Add branding prefs back (#242)

## 1.0.0-a.63

### Fixed

- uBlock now works in sidebars (#238)

### Changed

- Updated Firefox to `112.0` (#237)
- Updated uBlock to `1.48.8` (#237)
- Update BetterFox (#237)

## 1.0.0-a.62

### Fixed

- Specified wayland app name (#231)
- Migration for disabling sidebar animations (#234)
- New tab button no longer follows OS style (#233, @surapunoyousei)
- Fix vertical tab borders on windows (#232, @surapunoyousei)
- Download URL points to Pulse site (#235)

## 1.0.0-a.61

### Added

- The user can reposition the sideber (#222)

### Changed

- Updated Firefox to `111.0` (#227)
- Updated uBlock to `1.47.4` (#227)
- Update BetterFox (#227)
- Distroid is now `com.fushra.browser.alpha` (#227)

## 1.0.0-a.60

### Fixed

- Forget functionality would forget all cookies (#215, [Bug 1816279](https://bugzilla.mozilla.org/show_bug.cgi?id=1816279))

### Changed

- Updated Firefox to `110.0.1` (#219)
- Updated Better-Fox (#218)
- Enable VA-API by default (#216)

## 1.0.0-a.58

### Changed

- Updated Firefox to 110.0 (#209)
- Updated UBlock to 1.47.0 (#209)

## 1.0.0-a.57

### Fixed

- Reenable firefox sync (#208)

## 1.0.0-a.56

### Fixed

- Fix our Better-Fox implementation

## 1.0.0-a.55

### Fixed

- Vertical tab scrolling is less horrible

## 1.0.0-a.54

### Added

- Vertical tab resizing (#199)

### Changed

- Welcome screeen will ask if you want to enable vertical tabs (#198)
- Pulse Theme for vertical tabs has been cleaned up (#201)

## 1.0.0-a.53

### Added

- Vivaldi & Opera importers (#200, Upstream)

### Changed

- Updated Firefox to `109.0` (#200)
- Update uBlock Origin to `1.46.0` (#200)

### Fixed

- Vertical tabs no-longer display in fullscreen (#197, @Jacob-Tsekrekos)
- Remove gap above toolbar w/ vertical tabs on Windows (#197, @Jacob-Tsekrekos)
