## Push Frida Server on Android Genymotion



* **upload frida-server file into android genymotion**

  ```adb push frida-server-12.11.4-android-x86 /data/local/tmp/frida-server```



* **give permission for frida-server file**

  ```adb shell chmod 755 /data/local/tmp/frida-server```



* **running frida-server as background on android genymotion**

  ```adb shell /data/local/tmp/frida-server &``` 
