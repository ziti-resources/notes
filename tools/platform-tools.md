# Guide to install platform tools

## Windows
1. Download [sdk-platform-tools](https://developer.android.com/tools/releases/platform-tools) for windows
2. Extract zip
3. Launch command prompt or terminal in the extracted folder

## Linux

### Ubuntu / Debian
```shell
sudo apt install adb fastboot
```
### Arch
```shell
sudo pacman -S android-tools
```
### Fedora
```shell
sudo dnf install android-tools
```

---
Check if they are working as intended
```shell
adb devices
adb reboot bootloader
```
```shell
fastboot devices
```