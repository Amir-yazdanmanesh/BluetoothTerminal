# bluetoothTerminal
[![](https://jitpack.io/v/Amir-yazdanmanesh/bluetoothTerminal.svg)](https://jitpack.io/#Amir-yazdanmanesh/bluetoothTerminal) [![android Status](https://img.shields.io/badge/platform-Android-yellow.svg)](https://www.android.com/)


This Android app provides a line-oriented terminal / console for classic Bluetooth (2.x) devices implementing the Bluetooth Serial Port Profile (SPP)

For an overview on Android Bluetooth communication see [Android Bluetooth Overview](https://developer.android.com/guide/topics/connectivity/bluetooth).

This App implements RFCOMM connection to the well-known SPP UUID 00001101-0000-1000-8000-00805F9B34FB

This app includes UUIDs for widely used serial profiles:


- Filtering, scanning, linking, reading, writing, notification subscription and cancellation in a simple way.
- Support custom scan rules
- Support configuration timeout for conncet or operation
- 
## Requirements
- A device's location services can use Bluetooth to detect Bluetooth beacons and provide a more accurate location
- From Android 12, the BLUETOOTH_SCAN, BLUETOOTH_ADVERTISE, and BLUETOOTH_CONNECT permissions can allow apps to scan for nearby devices without needing to request the location permission. For more information, see [New Bluetooth permissions in Android 12](https://developer.android.com/about/versions/12/features/bluetooth-permissions).
- My BLE library work on Android 5.0+ (API level 21+) .
# Install
### Step 1 :
Add it in your root build.gradle at the end of repositories:

```
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```
### Step 2 :
Add the dependency


```
dependencies {
	        implementation 'com.github.Amir-yazdanmanesh:bluetoothTerminal:1.0.1'
	}

```
## Preview
![](https://s23.picofile.com/file/8448095584/ezgif_com_gif_maker.gif) 


