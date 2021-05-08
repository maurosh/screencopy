# screencopy
Screen Copy GUI for android
A yad GUI for scrcpy (https://github.com/Genymobile/scrcpy)

Steps:

1.Install screencopy (will install also yad, adb and scrcpy as dependencies).

2.Enable USB debugging on Android device.

3.Connect your android device with a usb cable.

4.Authorize and keep authorization onh usb device. If cable connection is not possible copy or append your key (~/.android/adbkey.pub) on android device /data/misc/adb/adb_keys.

5.Execute screencopy app. No need to modify IP address for a cable connection. In order to connect via wireless connection next tine, check "Enable TCP/IP". This will send a command (adb tcpip 5555) to your device to enable network connections.

6.Connect and your android screen appears on your desktop.

7.Now you can connect wirelessly by typing your android device IP. 

Note: Some android devices are unable to keep TCP/IP settings if rebooted. In that case repeat step 5.
