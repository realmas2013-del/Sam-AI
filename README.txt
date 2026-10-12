VOICE AI - ANDROID APP (Capacitor)

Install once on your PC:
  - Node.js (LTS)        https://nodejs.org
  - Android Studio       https://developer.android.com/studio

In a terminal inside this folder:
  npm install @capacitor/core @capacitor/cli @capacitor/android @capacitor-community/speech-recognition @capacitor-community/text-to-speech
  npx cap add android
  (edit the manifest, see AndroidManifest-additions.txt)
  npx cap sync
  npx cap open android

In Android Studio:
  - Wait for the Gradle sync to finish.
  - Phone connected with USB debugging on: press the green Run button.
  - Or: Build > Build Bundle(s) / APK(s) > Build APK(s), then copy
    android/app/build/outputs/apk/debug/app-debug.apk to the phone and install it.

After you edit www/index.html later:
  npx cap sync
  then press Run again in Android Studio.
