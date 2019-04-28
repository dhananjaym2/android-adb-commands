

adb devices

adb tcpip 5556

adb connect 192.168.0.185:5556

adb kill-server

adb start-server

adb shell

adb install app-debug.apk

adb shell pm uninstall com.app.package.name

adb shell reboot

adb logcat

Use the switch -s to specify a device, in case there are multiple devices/emulators available.
