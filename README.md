# 64gram-desktop-bin
Template file for 64gram for Void Linux distribution. Binary version.

## Installation steps.
1. Download this repo as a zip.
2. Extract the content.
3. Rename the folder ```64gram-desktop-bin-main``` to ```64gram-desktop-bin```.
4. Move the folder to ```void-packages/srcpkgs```.
5. Execute ```./xbps-src pkg -j$(nproc) 64gram-desktop-bin```. # remember to stay in the void-packages directory.
6. Install the package by executing ```xi 64gram-desktop-bin```. # remember to have installed "xtools" package for "xi" command.


## Credits.
- [64gram-desktop](https://github.com/TDesktop-x64/tdesktop)
- [64gram-desktop-bin - AUR](https://aur.archlinux.org/packages/64gram-desktop-bin)
- [xbps-src](https://github.com/void-linux/void-packages)
