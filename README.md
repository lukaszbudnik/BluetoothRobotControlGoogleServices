# BluetoothRobotControlGoogleServices
A simple Android application written to control my Arduino robots.

A fork of [lukaszbudnik/BluetoothRobotControl](https://github.com/lukaszbudnik/BluetoothRobotControl) with lots of additional Google Services integrations.

# Setup
Before running the application you need to generate a new signing key:

```
keytool -genkey -v -keystore ~/.android/debug_demo.keystore -alias androiddebugkey -storepass android -keypass android
```

The `app/build.gradle` already contains reference to the above keystore (`"${System.env.HOME}/.android/debug_demo.keystore"`).
