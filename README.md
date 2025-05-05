🎓 College Management System
College Management System is a modern, responsive web application designed to streamline college administration tasks. Built using HTML, CSS (Bootstrap 5), and JavaScript for the frontend, and Firebase for backend services like Firestore and Authentication, this system allows seamless management of teachers, students, fees, courses, and departments. It features a clean UI, real-time data handling, and insightful visual analytics using Chart.js.

🚀 Features
User Authentication: Secure login and logout functionality powered by Firebase Authentication.

Dashboard: A real-time dashboard showcasing statistics on students, teachers, fees, and departments, including a bar chart representing student distribution by department using Chart.js.

Teacher Management: Easily add, update, delete, and search teacher records. Includes filtering by department and CSV export capability.

Student Management: Manage detailed student records, including fee tracking, due fees listing, and search/filter options with CSV export support.

Fees Management: Track student fee payments, compute remaining balances, and export complete payment history.

Course Management: Add, update, and delete course records with built-in search and export functionalities.

Department Overview: Static listing of core departments such as Civil, Computer Science, and Electronics.

Responsive Design: Fully mobile-friendly interface featuring a collapsible sidebar and optional dark mode toggle for user comfort.

Notifications & Activity Logs: Real-time feedback and tracking of all user actions across the platform.

Profile Management: Users can update their display name via a dedicated profile modal.

🛠 Tech Stack
Frontend: HTML, CSS (Bootstrap 5), JavaScript

Backend: Firebase (Firestore Database, Firebase Authentication)

Libraries: Chart.js (for charts), Font Awesome (for icons)

Styling: Custom CSS with a modern gradient theme and full dark mode support

📦 Installation
bash
Copy
Edit
git clone https://github.com/yourusername/college-management-system.git
Open login.html in your browser to authenticate using Firebase credentials.

Upon successful login, you’ll be redirected to index.html to access the application.

Ensure a stable internet connection for Firebase services and CDN dependencies to function correctly.

🔧 Firebase Setup
Create a project in the Firebase Console.

Enable Email/Password Authentication and Firestore Database in the project settings.

Copy your Firebase configuration and replace the existing firebaseConfig object in both login.html and index.html.

📚 Usage Guide
After logging in via login.html, users can navigate the app through the sidebar to manage teachers, students, fees, courses, or departments. The system provides advanced search and filter options, CSV export capability for data backup, dark mode toggling, and profile customization. All actions are logged and reflected in real-time across the dashboard and logs.

🔮 Future Enhancements
Role-based access control (Admin vs Standard Users)

Advanced analytics for fee tracking and student academic performance

Calendar integration for scheduling events and announcements

Support for uploading student profile photos and documents

🤝 Contributing
We welcome contributions from the community. To contribute:

Fork the repository

Create a feature branch

Submit a pull request with your changes

Please ensure your code follows existing conventions and includes clear, concise comments.

📄 License
This project is licensed under the MIT License, allowing you to use, modify, and distribute it freely for both personal and commercial use.

