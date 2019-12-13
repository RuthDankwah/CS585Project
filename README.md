CS585Project

This document is tutorial on how to build an application using React Native, methods and application to test your application.

A.) STEPS TO BUILD A MOBIBLE APPLICATION USING REACT NATIVE

1. React Native provides a step by step tutorial to build an application. The website can be found below
https://facebook.github.io/react-native/docs/getting-started

-Because I have a windows computer, I produced an Android application that can be ran on both IOS and Android devices.

2. Download these applications: 
      *Node.js: Can be installed via Chocolatey https://chocolatey.org/
      *React Native command line interface
      *Python2: Can be installed via Chocolatey https://chocolatey.org/
      *JDK: Java SE Development Kit
      *Android Studio
      
3. Open a Command Prompt and select "Run as Administrator"
      Code needed:
      choco install -y nodejs.install python2 jdk8
      
4. Follow the steps to properply download Android Studio and SDK through the tutorial website provided

5. Create a new React Native project by using a built in command line interface. Name it what you want
      Code needed:npx react-native init YourProjectName
      
6. Testing your mobile application
      Phyiscal device: You can use a physical Android device. Plug this device into your computer using a USB. 
      Check to make sure your device is connected to the ADB (Andorid Debug Bridge)
      Code needed: $ adb devices
                   List of devices attached
                   emulator-5554 offline
                   14ed2fcc device
  
      Type code into command prompt
      Code needed: $ react-native run-android
      
      Phone emulator: 
      Use Android Studio to open ./YourProjectName/android
      Make sure you have created a new AVD that allows you to choose your virtual android device
      
7. How to run your application
      Run appliation inside your React Native project folder
      Code needed: cd YourProjectName
                   npx react-native run-android
                   
 8. How to modify your application
     Open App.js in any text editor (I used sublime)
     Press 'R' key twice or select Reload from the developer menu
     Press ctrl + M to see updates!
