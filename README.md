# ChargeMe Mobile Application Simulation

## Getting Started with React Native Application Development

1. Run this command to locally package, serve, and publish projects with expo (does not matter if you run this command in the project directory): 
```
$ npm install expo-cli --global
```
2. Run this command to install all of the elements of React Native
```
$ npm install react-native-elements --save
```
3. Run series of commands:
```
$ npm install
$ npm install react-native-elements --save
$ npm install react-navigation@2.6.2
```
Install native-base using command:
```
$ npm i native-base@2.8.2  
```
```
$ npm uninstall react-native-vector-icons --save
$ npm install react-native-vector-icons --save
```
4. Install expo on your iOS/Android device or use an Android emulator like GenyMotion or iOS Simulator in Xcode
-   if in Xcode:
- right click the Xcode icon
- hover over "Open Developer Tool"
- left click "Simulator"
- allow iOS simulator to boot up
5. cd into the project directory and run the following command in the folder:
```
$ expo run
```
6. Go back to the simulator and allow Expo to be installed on the emulator
7. The appliction will open and you may navigate through the pages
- [iOS Simulator Gestures](https://www.dummies.com/web-design-development/mobile-apps/how-to-make-gestures-on-the-ios-simulator/)
- [Android Emulator Gestures](https://docs.genymotion.com/latest/Content/03_Virtual_Devices/Interacting_with_virtual_devices/Multi_touch_simulation.htm)

[Expo Documentation](https://docs.expo.io/versions/latest/introduction/installation/)

#### Emulate on iOS 
8. cd into the project directory and run the following command in the folder:
```
$ expo run
```
9. make sure you have the Expo Client App
10. Make sure the QR code is on Tunnel or LAN 
-   Tunnel seems to run faster for some iOS devices
11. Scan QR code through QR code scanner or iOS camera
12. Open application through Expo Client

## Troubleshooting
### Error Running (OSX):
```
$ expo start
```
#### Error Message: 
> Error installing or running app. Error: Command failed: osascript -e tell app "System Events" to count processes whose name is "Simulator"
> execution error: Not authorized to send Apple events to System Events

Go to:
> Settings -> Security & Privacy -> Privacy -> Automation -> Privacy tab 
check the "System Events" checkbox
