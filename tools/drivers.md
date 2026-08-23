# List of drivers needed to flash custom ROMs

## For windows
carefully follow installing steps in the repository
1. [Google USB driver](https://developer.android.com/studio/run/win-usb)
2. [adb and fastboot driver](https://github.com/fawazahmed0/Latest-adb-fastboot-installer-for-windows/)

## For Linux
Linux does not require external drivers to be installed

---
Check if the drivers are installed correctly
```shell
adb devices
adb reboot bootloader
```
```shell
fastboot devices
```