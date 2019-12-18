# TaxiApps
 
# React Native Monorepo
## 100% code sharing between apps for iOS and Android

This is the source code [Follwoing this tutorial](https://dev.to/brunolemos/tutorial-100-code-sharing-between-ios-android--web-using-react-native-web-andmonorepo-4pej).

![article-cover](https://user-images.githubusercontent.com/619186/64933790-1fc27680-d81d-11e9-8077-64a1066b7c17.png)


### How to run

_Requirements: [React Native](https://facebook.github.io/react-native/docs/getting-started.html#native) (last tested on react-native@0.61.5)_

  - `$ git clone {this repo}`
  - `$ cd TaxiApps`
  - `$ yarn`
  - `$ cd packages/fmstaxiclientapp/ios and cd packages/fmstaxidriverapp/ios` 
  - `$ pod install`
  - `$ cd -`
  - `$ yarn workspace fmstaxiclientapp start`
  - `$ yarn workspace fmstaxidriverapp start`
  - Run the project
    - [iOS] Via Xcode
      - `yarn xcode` (open the project on Xcode)
      - Press the Run button
    - [Android] Via Android Studio
      - `yarn studio` (open the project on Android Studio)
      - Press the Run button
    - Via CLI
      - _You may need to launch your device emulator before the next command_
      - `$ yarn android` or  `$ yarn ios`
