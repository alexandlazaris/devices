# devices
A collection of device tools, cli commands, schematics and other things of that nature.

## datasheets0
* https://device.report/ - An extensive electronics database of over 500,000 products with certifications, type approvals, specifications, instructions, and datasheets

## adb
```
adb shell list packages (list package names)
adb shell list packages -r (list package name + path to apks)
adb shell list packages -3 (list third party package names)
adb shell list packages -s (list only system packages)
adb shell list packages -u (list package names + uninstalled)
adb shell dumpsys package packages (list info on all apps)
adb shell dump (list info on one package)
adb shell path (path to the apk file)
adb shell ip address (get android device mac address)
```
