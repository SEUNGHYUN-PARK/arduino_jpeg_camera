
    
  snapshot folder is android code!
  taketomobile folder is arduino sketch!

  Takes jpeg pictures and then send them to android phone via bluetooth 2.0 (bypass SD card).

  Camera module is VC0706 jpeg camera module(TTL/TxRx interface)
  Arduino UNO & Android mobile

  Youtube: https://youtu.be/qEVXqOJz-GY  

  Usage: 

  Arduino side :
  1. download VC0706 library (https://github.com/adafruit/Adafruit-VC0706-Serial-Camera-Library)
  2. unzip it and copy to arduino/libraries
  3. compile sketch and download to Arduino board

  Android sie:
  1. modify DEVICE_ADDRESS = "00:13:03:13:85:55" to your device address of bluetooth in snapshot.java
  

