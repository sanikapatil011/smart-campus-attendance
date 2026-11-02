# Smart Campus Attendance — No Python Version

This is a front-end demo made with HTML, CSS and JavaScript. It does not require Python, Node.js, or MySQL.

## Run on your computer
1. Extract the ZIP.
2. Open the `Smart_Campus_No_Python` folder in VS Code.
3. Install the VS Code extension **Live Server** (by Ritwick Dey).
4. Right-click `index.html` and choose **Open with Live Server**.
5. The app opens in your browser.

You can also open `index.html` directly, but camera QR scanning generally needs HTTPS or localhost.

## Features
- Dashboard summary
- Add/delete students
- Generate QR codes for students
- Scan QR codes using the device camera
- Manual attendance option
- Attendance records and CSV export
- Basic department report
- Browser localStorage persistence

## Important limitations
- This is a learning/demo project, not a secure production attendance system.
- Data is stored only in the current browser on the current device. Clearing browser data can remove it; it is not shared with other devices.
- The demo has no real secure login and no central database.
- QR values contain the student's roll number; do not use this QR scheme for official or sensitive attendance.
- QR code generation/scanning libraries load from a CDN, so internet access is needed for those features.
- For a real multi-user college system, connect a secure backend/database (for example Firebase) and implement proper authentication and authorization.
