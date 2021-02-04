# Changelog

## v0.3.2

- 🚀 The app store finally arrives in this fork!
- 🔧 We completely rebased this project so it has the full history of pi-gen and the history of Umbrel OS.
- 👨‍💻 We made some small improvements for code readabilty behind the scenes.
- 💾 UAS issues with more drives have been resolved in this release.

## v0.2.15-4

- This release fixes a bug that caused Umbrel not to be installed.

## v0.2.15-3

- This release fixes a bug that prevented GitHub actions from building images for the previous two releases.

## v0.2.15-2

- This release fixes one of the bugs that prevented GitHub actions from building images for the previous release.

## v0.2.15-1

There are now three types of images.
    - **Default**: The default Umbrel OS, based on RPi OS arm64 lite, but with all packages from RPi OS except python2 and all improvements in this fork that aren't in Umbrel (yet).
    - **Desktop**: The same as RPi OS arm64, but without Python 2. It contains all improvements of this fork.
    - **Full**: The same as RPi OS arm64 full (RPi OS with a few additional packages), but without Python 2. It contains all improvements of this fork.

## v0.2.15

- Update to Umbrel v0.2.15
- Update preinstalled beginners guide
- Remove most parts of python2 to reduce image size
- Improved code readability
- Merge changes from latest pi-gen

## v0.2.14.2

- Improved configuration otions for SSH
- Only disable WiFi if WPA_COUNTRY is not set
- Fix build failure on AWS M6g instances
- Add printing support
- Fix permissions of the SSH folder if using a `GITHUB_USERNAME`

Most of these changes were cherry-picked from [pi-gen](https://github.com/RPi-Distro/pi-gen) and only modified to work in this repository.

## v0.2.14.1

- Minor improvements in the autobuilds

## v0.2.14

- First version, default Umbrel OS with desktop