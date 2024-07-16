# Changelog

All notable changes to `vibrant-abyss` crate will be documented in this file.

The format is based on [Keep a Changelog], and this project adheres to
[Semantic Versioning].

## [0.2.1]

## Fixed

- Remove extra character from line start in `README.md`

## [0.2.0]

## Changed

- Add `assets/screenshots` to `.vscodeignore`

## Fixed

- Reduce extension size by loading screenshots as raw images from repository in `README.md`

## [0.1.8]

## Added

- Add new customization for `Suggest Widget`
  - Set background and border colors to `#000000`
  - Set highlight foreground color to `#4EC1FB`
  - Set selected background color to transparent (`#00000000`)

## Changed

- Set `Suggest Widget` focus highlight foreground color to `"#9CDCFE"` from `#2996DE70`

## [0.1.7]

### Fixed

- Include screenshots in extension package

## [0.1.6]

### Added

- Change foreground color of an item to `#2996DE70` when selected in `Suggest Widget`

### Changed

- Update `.gitignore`
- Load images through repository URL in `.md` files

### Fixed

- Reduce extension size by `~160%` with `.vscodeignore`

## [0.1.5]

### Added

- List `Command Center` installation method in `Installation` section of
  `README.md`
- Specify schema type for `deploy.yml` in `settings.json`

### Changed

- Correct headings in `MANUAL.md`
- Format `MANUAL.md`
- Include `.md` in `.editorconfig`
- Reduced extension size by increasing compression of `.png` asset files
- Replace `rust.png` and `rust-debug.png` with better screenshots
- Use strings with double instead of single quotes in `deploy.yml`

## [0.1.4]

### Changed

- Replace `C#` debug screenshot with new one that does not show the taskbar

### Fixed

- Correct break between normal and debug screenshots

## [0.1.3]

### Added

- New screenshots of `C#` code in themed editor
- Missing `Table of contents` heading after badges in `README.md`

### Changed

- Display screenshots under correct subsections in `README.md`
- Update and rename `Installation methods` section to `Installation` in
  `README.md`
- Update last section name in `MANUAL.md`

### Fixed

- Correct headings in `README.md`
- Use installation command with correct file name in `MANUAL.md`
- Use github links for `LICENSE` and `MANUAL` in `README.md`

## [0.1.2]

### Changed

- Add missing space before extension install command in `MANUAL.md`
- Rename change label of marketplace badge to `Version` from
  `Visual Studio Marketplace`

### Fixed

- Correct path to `icon.png` in `MANUAL.md`

### Removed

- Remove unnecessary line of text under `License` section

## [0.1.1]

### Changed

- Update downloads badge in `README.md` to display installs

## [0.1.0]

- Initial release

<!-- Links -->

[Keep a Changelog]: https://keepachangelog.com/en/1.0.0/
[Semantic Versioning]: https://semver.org/spec/v2.0.0.html

<!-- Versions -->

[0.2.0]: https://github.com/noelhorvath/vibrant-abyss/releases/tag/v0.2.1
[0.2.0]: https://github.com/noelhorvath/vibrant-abyss/releases/tag/v0.2.0
[0.1.8]: https://github.com/noelhorvath/vibrant-abyss/releases/tag/v0.1.8
[0.1.7]: https://github.com/noelhorvath/vibrant-abyss/releases/tag/v0.1.7
[0.1.6]: https://github.com/noelhorvath/vibrant-abyss/releases/tag/v0.1.6
[0.1.5]: https://github.com/noelhorvath/vibrant-abyss/releases/tag/v0.1.5
[0.1.3]: https://github.com/noelhorvath/vibrant-abyss/releases/tag/v0.1.3
[0.1.2]: https://github.com/noelhorvath/vibrant-abyss/releases/tag/v0.1.2
[0.1.1]: https://github.com/noelhorvath/vibrant-abyss/releases/tag/v0.1.1
[0.1.0]: https://github.com/noelhorvath/vibrant-abyss/releases/tag/v0.1.0
