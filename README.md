# DONG Mobile

Native Android test branch for DONG, built with Kivy.

Current mobile source: **v0.3**, based on desktop **DONG v0.45**.

## Build v0.3 from your phone

1. Download `DONG_Mobile_v0_3.zip` from the ChatGPT conversation.
2. In this repository, choose **Add file -> Upload files**.
3. Upload `DONG_Mobile_v0_3.zip` to the repository root and commit it to `main`.
4. Open the **Actions** tab.
5. Open **Build Android Debug APK**.
6. Tap **Run workflow** and run it on the `main` branch.
7. The workflow automatically selects the newest `DONG_Mobile_v*.zip` file and uploads a matching debug APK artifact.
8. Extract the artifact ZIP on Android, then tap the `.apk` inside to install it.

Android may ask you to allow installation from the browser or Files app you used to open the APK.

v0.3 keeps the v0.2 desktop-parity systems and cleans up the phone interface: the permanent bottom navigation bar is gone and replaced by a slide-out side drawer opened from a slim left-edge tab. Home, Character, Inventory, Jobs, Map, Forge, Phone, Crime, Jail, Save Game and Main Menu now live in that drawer.

The workflow verifies the uploaded source ZIP before building so a damaged upload fails clearly instead of producing mystery garbage, a small mercy from software engineering.
