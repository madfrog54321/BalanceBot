# BalanceBot
Balancing Lego Mindstorms Robot using an Android device

The goal of this project is to use an Android device to control a balancing Lego Mindstorms NXT robot.

The Android apps are Android APK version 17.

The NXT is using Lejos.


An Android device is used to gather the angle of the robot, and procces the corrent motor commands. 
The Android device then sends that information to the NXT brick using bluetooth.
The NXT brick uses the information from the Android device to drive the motors of the robot.
Another Android device can then be used to control the robot using a bluetooth connection to the main Android device.
