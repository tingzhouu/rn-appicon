# RN-AppIcon

A quick documentation of how to setup app icons on a React Native app.

There is no need to open `XCode` or `Android Studio` to do this.

### Demo for iOS (left) and Android (right)
<img src="https://drive.google.com/uc?export=view&id=1Kc-qg4q6yudD9DhaLWNVe3vF-k9FyEJY" width="360">
<img src="https://drive.google.com/uc?export=view&id=1yh8mlTkxwZZEp9jMUmA5msHxca6XfUNp" width="360">

### Getting Image Files

1. Find an image that you want to use.
2. Go to [appicon.co](https://appicon.co/) and generate the icon image for iPhone and Android.
3. You should have downloaded a zip file that conatains 2 folders: `android` and `Assets.xcassets`

### Adding Image Files for iOS

1. In your current project, open the folder `/ios/PROJECT_NAME/Image.xcassets/AppIcon.appiconset`.
2. In the zip file downloaded from `Step 3` of `Getting Image Files`, open the folder `Assets.xcassets`. You will find a folder with the name `AppIcon.appiconset`.
3. Replace the folder in `Step 1` with the folder in `Step 2`.
4. Run `react-native run-ios` to check if you have successfully added the icons for iOS.

### Adding Image Files for Android

1. In your current project, open the folder `/android/app/src/main/res`. You will find a few folders with the name starting with `mipmap`.
2. In the zip file downloaded from `Step 3` of `Getting Image Files`, open the folder `android`. You will find a few folders with the name starting with `mipmap`.
3. Replace the folders in `Step 1` with the folders in `Step 2`.
4. Run `react-native run-android` to check if you have successfully added the icons for Android.
