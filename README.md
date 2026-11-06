# Rana AI — Android starter app

This is a native Android Studio starter project for a Bengali/English personal assistant.

## Included
- Chat-style Android interface
- Bengali / English interface toggle
- Voice input using Android speech recognition
- Spoken replies using Android Text-to-Speech
- Basic offline demonstration responses

## Build
1. Install Android Studio (Ladybug or newer).
2. Open this `RanaAI` folder in Android Studio.
3. Allow Gradle sync to finish.
4. Connect an Android phone with USB debugging enabled, or start an emulator.
5. Press Run.

To create an APK: **Build → Build Bundle(s) / APK(s) → Build APK(s)**.

## Important limitation
This starter app is not yet connected to a cloud AI model, so it does not provide general intelligent answers or live web search. For a production AI assistant, connect the app to a secure backend server that holds the AI provider key. Do not place a private API key directly inside the Android app.

Voice recognition availability and Bengali recognition quality depend on the Android device and its installed speech services.

## Build APK from an Android phone using GitHub Actions

1. Create a GitHub account and a new **public or private** repository.
2. Upload the contents of this project ZIP into the repository (not the ZIP file itself).
3. Open the repository's **Actions** tab.
4. Choose **Build Rana AI APK** and tap **Run workflow** (or push to `main`).
5. When the run completes, open it and download the `RanaAI-debug-apk` artifact.
6. Extract the downloaded artifact ZIP and install `app-debug.apk` on your phone.

Note: The workflow requires GitHub Actions to be enabled for the repository. The generated debug APK is for testing and is not a Play Store release.
