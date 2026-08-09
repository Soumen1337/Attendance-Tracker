# IILM Attendance

Native Android app for tracking B.Tech Sem 5 A attendance from the uploaded IILM timetable.

## Timetable assumptions

- Timetable starts from 06-08-2026.
- Group 2 is used for Introduction to Machine Learning Lab, Web Development Frameworks Lab, and Data Communication and Networks Lab.
- Applied Machine Learning Lab uses Group 1, so it is assigned on Friday 14:00-16:10 in Lab 6-A-06.

## Features

- Date-wise class list with Present, Absent, Cancelled, and Clear actions.
- Subject-wise attendance percentage.
- Add new subjects with weekly day and time.
- Edit subject details.
- Add or edit manual attendance records for any date.
- Share one subject, added subjects, or the full timetable through Android share sheet.
- Import shared subjects from pasted text, clipboard, or Android's text share intent.

## Open in Android Studio

1. Open Android Studio.
2. Choose `Open`.
3. Select the `IILMAttendance` folder.
4. Let Android Studio sync Gradle and install Android SDK 35 if prompted.
5. Run the `app` configuration on an emulator or phone.

This project uses only standard Android SDK APIs, Java, and `SharedPreferences`.
