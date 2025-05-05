🎓 College Management System
A modern, responsive web application built to streamline college administration tasks. This system enables efficient management of teachers, students, fees, courses, and departments using Firebase for real-time data and Bootstrap 5 for a sleek UI. 📊

🚀 Features
🔐 User Authentication
Secure login/logout using Firebase Authentication.

📊 Dashboard
Visual stats of students, teachers, fees, and departments. Includes bar chart showing student distribution by department using Chart.js.

👨‍🏫 Teacher Management
Add, update, delete, and search teachers with:

Department filtering

CSV export functionality

🎓 Student Management
Full student records with:

Fees tracking

Due fees list

Filter, search, and export options

💰 Fees Management

Track fee payments

Calculate remaining fees

Export payment history

📚 Course Management
Add, update, delete, search, and export courses.

🏢 Department Overview
Static list: Civil, CS, Electronics

📱 Responsive Design

Mobile-friendly layout

Collapsible sidebar

🌙 Dark mode toggle

🔔 Notifications & Activity Logs
Real-time logs and action notifications.

🙍‍♂️ Profile Management

Update display name

Profile modal

🛠 Tech Stack
Frontend: HTML, CSS (Bootstrap 5), JavaScript

Backend: Firebase (Firestore & Authentication)

Libraries: Chart.js, Font Awesome

Styling: Custom CSS with gradient theme and dark mode

📦 Installation
bash
Copy
Edit
git clone https://github.com/yourusername/college-management-system.git
Open login.html in your browser to authenticate.

On success, you'll be redirected to index.html.

Make sure you have an active internet connection for Firebase & CDN resources.

🔧 Firebase Setup
Go to Firebase Console

Create a new project.

Enable:

Authentication (Email/Password)

Firestore Database

Replace your Firebase configuration inside firebaseConfig in both index.html and login.html.

📚 Usage
Log in using login.html

Navigate through the sidebar:

👨‍🏫 Manage Teachers

🎓 Manage Students

💰 Manage Fees

📚 Manage Courses

🏢 View Departments

Use search, filters, and CSV export options

Switch between 🌞 light and 🌙 dark modes

Update profile from the top-right header icon

🔮 Future Enhancements
🧑‍💼 Role-based access (Admin vs User)

📈 Advanced analytics (fees, performance)

📅 Event scheduling with calendar

🖼 Student photo uploads

🤝 Contributing
Contributions are welcome!
Please:

Fork the repo

Create a new branch

Submit a pull request ✅

Ensure your code:

Follows the current style

Is well-documented

📄 License
MIT License – feel free to use, modify, and distribute this project! 🎉
