# wako for Android TV

APK builds of [wako](https://wako.app) for Android TV (Fire TV, Nvidia Shield, Google TV, generic Android TV boxes).

If Google Play is available on your device, install from there — it auto-updates. This repo exists for devices where Google Play is out of reach.

## Install

1. Go to [Releases](https://github.com/wako-app/wako-tv/releases/latest)
2. Pick the APK matching your device CPU:
   - `app-arm64-v8a-release.apk` — most modern TV boxes (Nvidia Shield, recent Fire TV)
   - `app-armeabi-v7a-release.apk` — older 32-bit ARM devices
   - `app-x86_64-release.apk` — Chromebooks, emulators, x86 boxes
3. Side-load the APK on your TV (via a file manager, `adb install`, or a side-load app).

If unsure which one to pick, try `arm64-v8a` first.
