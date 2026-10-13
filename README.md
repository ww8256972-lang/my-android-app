# My Android App

This repository contains a minimal Android project skeleton and a GitHub Actions workflow to build a debug APK.

## Project structure
- `app/` — Android app module
- `.github/workflows/android.yml` — CI pipeline for APK build

## Build locally
1. Install Android Studio / Android SDK
2. Open this folder in Android Studio
3. Sync Gradle and run the app

## GitHub Actions secrets
For release APK signing, add these repository secrets:
- `KEYSTORE_BASE64`
- `KEYSTORE_PASSWORD`
- `KEY_ALIAS`
- `KEY_PASSWORD`

Do not commit keystore files or private passwords.
