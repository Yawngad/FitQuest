# FitQuest Android v2

Native Android starter project for FitQuest with a home-screen widget.

## Features
- Native app screens: Today, Week, Mobility, Progress
- Daily plan based on weekday
- Exercise checklists stored locally
- Session completion and streak counter
- Home-screen widget with today's session and streak
- Offline; no account or network required

## Build an APK
1. Install Android Studio on a computer.
2. Open this folder (`FitQuestAndroid`) as a project.
3. Let Android Studio sync Gradle.
4. Use **Build > Build APK(s)**.
5. Find the APK under `app/build/outputs/apk/debug/`.
6. Transfer it to your Android phone and install it. You may need to allow installation from the file manager for this APK.


## Add the widget
After installing, long-press your phone's home screen, choose **Widgets**, find FitQuest, and drag the widget onto your home screen.


## Notes / limitations
- This project source has not been compiled or tested on a device in this environment.
- The widget is set to request updates every 30 minutes, but Android launcher/battery policy can delay refreshes. Opening the app refreshes its data.
- The current version does not include scheduled notification reminders.
- Progress is stored on-device and is not backed up to an account.
