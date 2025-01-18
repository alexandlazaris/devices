# devices
A collection of device tools, cli commands, schematics and other things of that nature.

## datasheets

* https://device.report/ -> Search for products across a massive database of specifications, instructions, and datasheets. 

## Android

### adb
-  list packages: `adb shell list packages`
-  list package name + path to apks: `adb shell list packages -r`
-  list third party package names: `adb shell list packages -3`
-  list only system packages: `adb shell list packages -s`
- list package names + uninstalled: `adb shell list packages -u`
- list info on all apps: `adb shell dumpsys package packages`
- list info on one package: `adb shell dump`
- path to the apk file: `adb shell path`
- get android device mac address: `adb shell ip address`
- control device  power, wifi, bluetooth, usb: `adb shell svc`

## all-in-one tools

- https://github.com/AzeemIdrisi/PhoneSploit-Pro -> connect device over wifi or usb to extract all kinds of data, run apps & perform device actions
- https://github.com/MobSF/Mobile-Security-Framework-MobSF -> pen testing suite for iOS and Android
- https://github.com/AggressiveUser/noxer -> Android pen testing created in Python