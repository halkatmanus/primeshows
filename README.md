# Primeshows TV (WebView wrapper)

Build options:
1. Android Studio: File > Open this folder > Build > Build APK(s).
2. GitHub: push this folder to a repo, open the Actions tab, run "Build APK", download the artifact.
3. CLI (JDK 17 + Android SDK + Gradle 8.9): `gradle assembleDebug`
   -> app/build/outputs/apk/debug/app-debug.apk

Install: adb connect 192.168.0.235:5555 && adb install -r app-debug.apk
