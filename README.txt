SPIN — Android Studio project

This is the Android app project for your uploaded Spin vinyl music player.

BUILD THE APK
1. Install Android Studio on a computer.
2. Extract this ZIP file.
3. In Android Studio choose Open, then select the extracted "SpinAndroid" folder.
4. Allow Android Studio to install the required Android Gradle plugin / SDK if prompted.
5. Choose Build > Build Bundle(s) / APK(s) > Build APK(s).
6. When the build finishes, click "locate" in the notification.
   The APK is usually at: app/build/outputs/apk/debug/app-debug.apk

The app wraps your supplied HTML in Android WebView. It supports selecting audio and
image files using Android's file picker. Internet permission is included for the
Google Fonts stylesheet used by the page; the player itself loads locally.

Package name: com.spin.vinyl
Minimum Android version: Android 6.0 (API 23)


BUILD WITHOUT A PC (GitHub Actions)
1. Create a GitHub repository and upload the contents of the SpinAndroid folder.
2. Open the repository's Actions tab.
3. Select "Build Spin APK" and press "Run workflow".
4. When the run finishes, open it and download the "Spin-debug-apk" artifact.
5. Extract the downloaded artifact ZIP to get app-debug.apk, then open it on your Android phone to install.

This workflow builds the debug APK in GitHub's cloud using Java 17 and Gradle 8.9.
