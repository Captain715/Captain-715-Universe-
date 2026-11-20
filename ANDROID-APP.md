# Captain 715 Universe Android app

The Android app is a lightweight WebView shell that opens the live GitHub Pages website:
https://captain715.github.io/Captain-715-Universe-/

Website changes appear in the app when the live site is updated and the app is online. The website's PWA service worker separately provides browser-side caching; native WebView offline behavior depends on its stored web cache and previously visited resources.

## Build the APK

Every push changing files under `android/` starts the GitHub Actions workflow **Build Captain 715 Android APK**.

1. Open the repository's Actions tab.
2. Select the latest successful **Build Captain 715 Android APK** run.
3. Under Artifacts, download **Captain-715-Universe-Android-APK**.
4. Extract the ZIP and install `app-debug.apk` on an Android device.

This is a debug-signed APK for direct testing and installation. It is not a Play Store release build. A separately managed signing key and a release build are required before Play Store distribution.

## App identity

- App name: Captain 715 Universe
- Application ID: com.captain715.universe
- Minimum Android: Android 6.0 (API 23)
- Website: GitHub Pages
