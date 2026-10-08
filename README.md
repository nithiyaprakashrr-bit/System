# The System (Android app)

Build the APK for free in the cloud, no Android Studio needed:

1. On a computer, create a free GitHub account and a new repository (branch name: main).
2. Upload everything in this folder, including the hidden .github folder.
3. Open the repo's Actions tab, choose "Build APK", and wait about 5 minutes (it also runs on every push).
4. Open the finished run, download the "the-system-apk" file, and unzip it to get app-debug.apk.
5. Copy the APK to your phone and open it. Allow "install unknown apps" when asked.

First launch: tap "Enable notifications" and allow them. Reminders are scheduled on the phone itself,
for the next 14 days, and refresh every time you open the app.

OPPO Reno 10 (ColorOS) settings so alarms are not killed:
- Settings > Apps > App management > The System > Battery usage: allow background activity and auto-launch.
- Settings > Apps > Special app access > Alarms & reminders: allow The System.
- In the recent apps screen, lock The System (pull the card down or tap the lock icon).
