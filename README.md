# VU Meter Plugin for the DeaDBeef audio player

![AUR Version](https://img.shields.io/aur/version/deadbeef-plugin-vu-meter-git)

This fork merges couple of pull requests from original repository to simplify publishing the plugin on AUR.

## How to build
1. Clone the repo or download as zip and extract
2. Change to the cloned/extracted directory
3. Issue `make`
4. Plugin .so files for GTK2 and GTK3 will be found in their respective directories

## Installation
You can run the `userinstall.sh` script or simply copy the gtk2/gtk3 .so file to `${HOME}/.local/lib/deadbeef`, create the folder if it does not exist.

AUR package ([deadbeef-plugin-vu-meter-git](https://aur.archlinux.org/packages/deadbeef-plugin-vu-meter-git)) also available for Arch Linux and derivatives users.

## Screenshots

### VU Bars
![vu meter in bars mode](https://github.com/jwty/ddb_vu_meter/raw/master/screenshots/VU.png "VU meter in bars mode")

### Retro VU meter
![vu meter in retro mode](https://github.com/jwty/ddb_vu_meter/raw/master/screenshots/retroVU.png "VU meter in retro mode")

## Contributors
* [Pull request #2](https://github.com/cboxdoerfer/ddb_vu_meter/pull/2) by [MarcRdC](https://github.com/MarcRdC)
* [Pull request #4](https://github.com/cboxdoerfer/ddb_vu_meter/pull/4) by [macearl](https://github.com/macearl)
* [Pull request #10](https://github.com/cboxdoerfer/ddb_vu_meter/pull/10) by [fallcom](https://github.com/fallcom)
