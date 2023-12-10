# Teacher Attendance App

This is a simple Google Apps Script for tracking teacher attendance. The associated MIT App Inventor project allows teachers to input attendance information, and the data is stored in a Google Sheet.

## Files

1. **TeacherAttendance.gs**
   - This is the Google Apps Script file responsible for handling the backend logic and storing data in the Google Sheet.

2. **AttendanceAppForTeachers.aia**
   - This file is the MIT App Inventor project. It provides the user interface and communicates with the Google Apps Script to record attendance.

## How to Use

### Google Apps Script

1. Open the [Google Apps Script Editor](https://script.google.com/).
2. Create a new project and copy-paste the content of `TeacherAttendance.gs` into the script editor.
3. Save the project and deploy it as a web app. Make sure to set the appropriate permissions.

### MIT App Inventor

1. Import the `AttendanceAppForTeachers.aia` file into MIT App Inventor.
2. Set up your app's UI and logic as needed.
3. Replace the placeholder URLs in the app with the deployed web app URL from the Google Apps Script.

## Dependencies

- [MIT App Inventor](https://appinventor.mit.edu/): Used for creating the mobile app interface.
- [Google Apps Script](https://script.google.com/): Used for server-side scripting and handling data storage.

## Contributing

Feel free to contribute to the project by opening issues or creating pull requests. Your feedback and improvements are highly appreciated!

If you're looking for a simpler version of this attendance app, check out [Attendance App](https://github.com/Sudhanshu-Ambastha/Attendance-app).
