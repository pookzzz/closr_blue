# closr_blue

The bluetooth pairing part of the Closr app prototype. 

Technology used:
---------------

*  Flutter
      + flutter_blue
*   Arduino
      + CurieBle.h
      
Flow 1 - New device and new account
-----------------------------------
1. Splash Screen
2. Check if new or existing user
3. Turn on Bluetooth notification
4. Scan for bluetooth device screen
5. Pairing 
6. Upon success load account creation screen

Flow 2 - Existing account, new device 
-
1. Splash screen
2. Check if new or existing user.
3. Check bluetooth status,
  a. turn on bluetooth notification
4. Login screen
5. Widget to activate

TODO
----
* https://engineersportal.com/blog/2017/9/20/hm-10-bluetooth-module?rq=hm%2010
