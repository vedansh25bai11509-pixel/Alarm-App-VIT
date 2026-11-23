CAMPUS PLANNER - FINAL ANDROID PROJECT
Builds an installable APK for free on GitHub. No Android Studio needed.

WHAT YOU NEED: a free GitHub account and a computer (or a phone using
"Desktop site" in the browser). About 10 minutes.

1. Unzip this file. Go to github.com > New repository (name it campus-planner,
   Public or Private both work) > Create repository.
2. Click "uploading an existing file". Drag in EVERYTHING inside the
   unzipped folder: the folders www, resources, .github and the files
   package.json, capacitor.config.json. Then click Commit changes.
   Check that .github/workflows/build.yml is in the repository. If the
   hidden .github folder did not upload, click Add file > Create new file,
   type  .github/workflows/build.yml  as the name and paste the contents
   of that file.
3. Open the Actions tab. "Build APK" starts by itself (5-8 minutes). Wait for
   the green tick. If it shows a red cross, open it and send me the error.
4. Open the finished run. Under Artifacts, download CampusPlanner-apk and
   unzip it to get CampusPlanner.apk.
5. Send CampusPlanner.apk to your phone (USB, WhatsApp to yourself, Drive).
   Tap it and allow "Install unknown apps" when asked.

FIRST LAUNCH
- Allow notifications. Allow "Alarms & reminders" when asked.
- Settings > Apps > Campus Planner > Battery > Unrestricted, so reminders
  are not delayed by battery saving.
- Keep phone volume up and Do Not Disturb off for alarms.

NOTES
- Works fully offline. Your data stays on your phone.
- Alarms send 8 loud, vibrating notifications, one per minute, until you
  open the app. Photo timetable scan works only in the web version.
