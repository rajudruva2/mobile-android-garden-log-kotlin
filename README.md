# Garden Log — Android Kotlin Demo

A small native Android starter app written in Kotlin. It displays sample cards for **track plants and watering tasks**.

## Features
- Native Android Activity and programmatic UI
- Kotlin source code
- Sample data embedded in the app (no backend or API keys required)
- GitHub Actions workflow to build a debug APK and upload it as an artifact

## Build with GitHub Actions
1. Create a separate GitHub repository for this folder.
2. Push the files to the repository's `main` branch.
3. Open **Actions** and select **Android Kotlin Build**.
4. Download `android-kotlin-debug-apk` from the successful workflow run.

## Local build
Install JDK 17, Android SDK, and Gradle 8.9, then run:

```bash
gradle assembleDebug
```

APK output: `app/build/outputs/apk/debug/app-debug.apk`.

## Notes
This is a learning/demo project. It uses local sample data and does not include persistence, networking, or automated UI tests.
