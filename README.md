# DONG Mobile

Native Android test branch for DONG, built with Kivy.

Current mobile source: **v0.2**, based on desktop **DONG v0.45**.

## Build v0.2 from your phone

1. Download `DONG_Mobile_v0_2.zip` from the ChatGPT conversation.
2. In this repository, choose **Add file -> Upload files**.
3. Upload `DONG_Mobile_v0_2.zip` to the repository root and commit it to `main`.
4. Open the **Actions** tab.
5. Open **Build Android Debug APK**.
6. Tap **Run workflow** and run it on the `main` branch.
7. When the run finishes, open it and download the `DONG-Mobile-v0.2-debug-apk` artifact.
8. Extract that artifact ZIP on Android, then tap the `.apk` inside to install it.

Android may ask you to allow installation from the browser or Files app you used to open the APK.

v0.2 is the major desktop-parity pass: property interiors/structures, farm animals, vehicles, Fighting Pits, crime/evidence/jail, deeper relationships/family, and fuller location actions are now exposed in the mobile UI.

The workflow verifies the uploaded source ZIP before building so a damaged upload fails clearly instead of producing mystery garbage, a small mercy from software engineering.
