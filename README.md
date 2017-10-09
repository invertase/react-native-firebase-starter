## React Native Firebase Starter

A basic react native app with [`react-native-firebase`](https://github.com/invertase/react-native-firebase) pre-integrated so you can get started quickly.

### Getting Started

If you're only developing for one platform you can ignore the steps below that are tagged with the platform you don't require.

#### 1) Clone & Install Dependencies

- 1.1) `git clone https://github.com/invertase/react-native-firebase-starter.git`
- 1.2) `cd react-native-firebase-starter` - cd into your newly created project directory.
- 1.3) Install NPM packages with your package manager of choice - i.e run `yarn` or `npm install`
- 1.4) **[iOS]** `cd ios` and run `pod install` - if you don't have CocoaPods you can follow [these install instructions](https://guides.cocoapods.org/using/getting-started.html#getting-started)
- 1.5) **[Android]** No additional steps for android here.

#### 2) Add `Google Services` files (plist & JSON)

- 2.1) **[iOS]** Follow the `add firebase to your app` instructions [here](https://firebase.google.com/docs/ios/setup#add_firebase_to_your_app) to generate your `GoogleService-Info.plist` file if you haven't done so already. Place this file in the `ios/` directory of your project.
- 2.2) **[Android]** Follow the `manually add firebase` to your app instructions [here](https://firebase.google.com/docs/android/setup#manually_add_firebase) to generate your `google-services.json` file if you haven't done so already. Place this file in the `android/app/` directory of your project.
  - The current package name is set to `com.rnfirebasestarter`
  
#### 3) Start your app

- 3.1) Start the react native packager, run `yarn run start` or `npm run start` from the root of your project.
- 3.2) **[iOS]** Build and run the iOS app, run `react-native run-ios` from the root of your project. The first build will take some time. This will automatically start up a simulator also for you on a successful build if one wasn't already started.
- 3.3) **[Android]** If you haven't already got an android device attached/emulator running then you'll need to get one running (make sure the emulator is with Google Play / APIs). When ready run `react-native run-android` from the root of your project.

If all has gone well you'll see an initial screen like the one below.
  
## Screenshots

![preview](https://i.imgur.com/4lG4HuS.png)
