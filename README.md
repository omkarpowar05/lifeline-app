# Lifeline APK (Capacitor)
1. Create a free GitHub repo and upload everything in this folder (keep `.github/workflows`).
2. Open the repo's **Actions** tab -> **Build Lifeline APK** -> **Run workflow** (it also runs on every push).
3. After ~5 minutes open the finished run and download **Lifeline-APK** (a zip containing app-debug.apk).
4. Send app-debug.apk to your phone, allow "Install unknown apps", and install.

Local build alternative (needs Node 20, JDK 17, Android SDK):
npm install && npx cap add android && npx cap sync android && cd android && ./gradlew assembleDebug
