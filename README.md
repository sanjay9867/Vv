# VirtualCam (No-Root LSPatch Xposed Module)

## Option A: Build the APK in the Cloud (No PC / No Android Studio Needed)
1. Create a free repository on GitHub.
2. Upload the contents of the `VirtualCam/` folder (make sure `.github/workflows/build-apk.yml` is at the root of the repo).
3. Open the **Actions** tab -> select **Build VirtualCam APK** -> click **Run workflow**.
4. Wait ~2 minutes, open the finished run, and download **VirtualCam-debug-apk** (contains `app-debug.apk`).

## Option B: Build Locally with Android Studio
1. Extract the zip and open the `VirtualCam` folder in Android Studio.
2. Let Gradle sync finish.
3. Click **Build -> Build Bundle(s) / APK(s) -> Build APK(s)**.
4. Find the compiled APK at `app/build/outputs/apk/debug/app-debug.apk`.
