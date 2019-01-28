# OculusGo_Setup
Unity build on Oculus Go and uninstall.

### Steup Android On Unity
1. Install Android SDK, Need API level 19
2. Download Oculus App, and app turn on Develope Mode.
3. Android Debug Bridge (ADB) (Location android_sdk/platform-tools/)  
  15 seconds ADB Installer v1.4.3 ->   
    https://forum.xda-developers.com/showthread.php?t=2588979 or  
    https://github.com/shinn716/OculusGo-Setup/blob/master/15_Second_ADB_Installer_v1.4.3.zip  
    https://developer.oculus.com/downloads/package/oculus-go-adb-drivers/  
    
4. XR/VR Setting open Virtual Reality Supported, and Add Oculus to the first in SDK.  
5. Install Oculus App on your mobile phone(Download from Google Play), and turn on "Develop Mode".  
    
### Detect Devices  
<img src="https://github.com/shinn716/OculusGo_Setup/blob/master/adb01.png" /></a>  
  
### Install APK(File name)  
<img src="https://github.com/shinn716/OculusGo_Setup/blob/master/adb02.png" /></a>   
adb -s "<deviceIDfromlist>" install "<path-to-apk>" & adb -s "<deviceIDfromlist>" install "<path-to-apk>" ...   
  
### Uninstall APK(Package Name)  
<img src="https://github.com/shinn716/OculusGo_Setup/blob/master/adb03.png" /></a>  
  
Reference  
---
 - Oculus Official  
 https://developer.oculus.com/documentation/mobilesdk/latest/concepts/mobile-device-setup-go/  
 - Build app with Unity  
 https://medium.com/inborn-experience/how-to-build-an-app-for-the-oculus-go-from-start-to-finish-with-unity-cb72d931ddae  

ADB
---
 - ADB build with wifi  
http://j796160836.pixnet.net/blog/post/29108155-%5Bandroid%5D-debug%E4%B8%8D%E7%94%A8%E7%B7%9A%EF%BC%8C%E7%94%A8adb%E9%80%A3%E6%8E%A53g-wifi%E6%89%8B%E6%A9%9F  
 - Error: more than one device/emulator  
 http://andy02172001.blogspot.com/2017/10/androidadb-error-more-than-one.html  
 - Install apk file if more then one devices.  
 https://stackoverflow.com/questions/7186215/is-it-possible-to-install-apk-file-if-more-then-one-emulators-devices-are-connec  
