# DONG Mobile

Native Android test branch for DONG, built with Kivy.

## Build from your phone

1. Download `DONG_Mobile_v0_1.zip` from the ChatGPT conversation.
2. In this repository, choose **Add file -> Upload files**.
3. Upload `DONG_Mobile_v0_1.zip` to the repository root and commit it to `main`.
4. Open the **Actions** tab.
5. Open **Build Android Debug APK**.
6. Tap **Run workflow** and run it on the `main` branch.
7. When the run finishes, open it and download the `DONG-Mobile-debug-apk` artifact.
8. Extract that artifact ZIP on Android, then tap the `.apk` inside to install it.

Android may ask you to allow installation from the browser or Files app you used to open the APK.

The workflow verifies the uploaded source ZIP before building so a damaged upload fails clearly instead of producing mystery garbage, a small mercy from software engineering.
