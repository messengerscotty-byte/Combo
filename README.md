# Combo Forge Android

This is the Android wrapper for the Combo Forge Yu-Gi-Oh! deck and combo builder.

## Build in Android Studio

1. Open this folder in Android Studio.
2. Let Gradle sync.
3. Select **Build > Build APK(s)**.
4. Find the APK in `app/build/outputs/apk/debug/app-debug.apk`.

## Build automatically with GitHub

Push this folder to a GitHub repository. The included workflow builds a debug APK and places it in the workflow's **Artifacts** section.

## Android behavior

- App data and autosaves remain stored locally on the phone.
- Live card search and card images require internet access.
- Exported combo and deck PNGs save to `Pictures/Combo Forge`.
- Minimum Android version: Android 10.
