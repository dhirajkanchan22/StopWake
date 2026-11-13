# StopWake — Smart Commute & Location Alarm App

A minimalist, neutral-themed native Android app built with Kotlin & Jetpack Compose (Material 3) that wakes commuters before they reach their transit stop.

## How to Generate the Installable `.apk` File

### Option 1: Using Android Studio (Recommended for Local Testing)
1. Extract this ZIP folder and open it in **Android Studio**.
2. Wait for Gradle Sync to finish automatically.
3. *(Optional)* Replace `YOUR_GOOGLE_MAPS_API_KEY` inside `app/src/main/AndroidManifest.xml` with your Google Maps SDK key.
4. Click **Build > Build Bundle(s) / APK(s) > Build APK(s)** from the top menu.
5. Click **Locate** in the notification pop-up to grab `app-debug.apk` and transfer it to your phone.

### Option 2: Free Cloud APK Build via GitHub (No Android Studio Needed)
1. Create a free repository on GitHub and upload the contents of this ZIP folder.
2. Click the **Actions** tab in your GitHub repository.
3. The included `.github/workflows/build-apk.yml` workflow will automatically compile the project and output **`StopWake-debug-apk`** under the workflow's **Artifacts** section for immediate download.
