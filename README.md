# Namma Ward 23

Android civic app with Firebase Authentication and Supabase backend.

## Build APK in GitHub Actions

Open **Actions** → **Build Android APK** and run the workflow. The debug APK is uploaded as a workflow artifact named `namma-ward-23-debug-apk`.

## Firebase

The Android package is `com.aistudio.nammaward23.skpkm`. `app/google-services.json` is included for this Firebase project.

## Supabase

Use the publishable client key only in the Android app. Never commit a Supabase secret/service-role key.
