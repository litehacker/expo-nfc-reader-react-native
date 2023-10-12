# Boilerplate for NFC functionality in React native

## Limitations

Since we can not execute [react-native-nfc-manager](https://www.npmjs.com/package/react-native-nfc-manager) in Expo Go, to try on both platforms the code using just `npm start`, we have to add prebuilt version of the react native app. At least we have a lib that can run on RN, without Expo, so it's worth trying. The only option it's possible, is to run the prebuilts on devices themlselves.

## Execution of native module on local device

1. `npx expo prebuild --clean` 
2. Only on MacOS/Linux `npx expo run:ios` on Windows `npx expo run:android`.
