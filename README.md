# ONotes (Organized Notes)

A simple notes app for Android, written in **Java**. Notes are organized in categories, one level deep: a main screen with sub-pages of notes.

**[⬇ Download the latest APK](https://github.com/AlexanderStubMichelsen/ONotes/releases/latest/download/ONotes.apk)**

## Features

- A main screen (`first_layer`) leading to separate note pages (`second_layer`)
- Add and delete notes on each page
- Notes are stored **only on the device** (SharedPreferences): no account, no internet
- [Privacy policy](https://machinemal.eu/privacyPolicyOrganizedNotes)

## Install

1. Open the download link above on your Android phone or tablet.
2. Open `ONotes.apk` and allow **"Install unknown apps"** for your browser when Android asks.

The app was previously on Google Play. It's now distributed directly as a signed APK.

## Tech

Java · Android SDK (min 23, target 35) · XML layouts · SharedPreferences

## Build

Open the project in Android Studio, or:

```bash
./gradlew assembleDebug        # app/build/outputs/apk/debug/
```

## Releases

Every push to `main` builds a signed release APK and publishes it as a [GitHub Release](https://github.com/AlexanderStubMichelsen/ONotes/releases) ([release-apk.yml](.github/workflows/release-apk.yml)). Bump `versionCode`/`versionName` in `app/build.gradle` for a new version.

My first Android app, from 2022.
