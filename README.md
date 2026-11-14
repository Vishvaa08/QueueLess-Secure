QueueLess Secure

A secure, web-based clinic queue management system developed as part of the Secure Application Development and Implementation assignment.

QueueLess Secure helps clinics manage patient queues digitally while providing separate access levels for administrators, staff and patients.

Features

Patient

* Patient registration and login.
* Secure authentication.
* Patient dashboard.

Staff

* Staff login.
* Add patients to the queue.
* Call the next patient.
* Mark patient visits as completed.

Administrator

* Administrator login.
* Admin dashboard.
* Create and manage staff accounts.
* View security event logs.
* Monitor registered patients and staff.

Security Features

* Firebase Authentication.
* Role-Based Access Control (RBAC).
* Firestore Security Rules.
* Input validation.
* Cross-Site Scripting (XSS) protection.
* Security event logging.
* HTTPS through Firebase Hosting.
* Access restrictions for protected pages.

Technologies Used

Technology	Purpose
HTML5	Web page structure
CSS3	Styling and responsive interface
JavaScript	Application functionality
Firebase Authentication	User authentication
Cloud Firestore	Database
Firebase Security Rules	Database access control
Firebase Hosting	Application deployment

System Architecture

QueueLess Secure uses a Firebase-based architecture.

* Frontend: HTML, CSS and JavaScript.
* Authentication: Firebase Authentication.
* Database: Cloud Firestore.
* Security: Firestore Security Rules and application-level role checks.
* Hosting: Firebase Hosting with HTTPS.

Live Application

Open QueueLess Secure

Project Structure

QueueLess-Secure/
│
├── index.html
├── login.html
├── patient-register.html
├── patient-dashboard.html
├── staff-dashboard.html
├── admin-dashboard.html
├── staff-management.html
├── security-logs.html
├── 404.html
│
├── firebase.json
├── .firebaserc
├── .gitignore
└── skills-lock.json

Installation and Setup

To run the project locally:

1. Clone the repository:

git clone https://github.com/Vishvaa08/QueueLess-Secure.git

2. Open the project folder in Visual Studio Code.
3. Start the application using the Live Server extension.
4. Ensure the Firebase project configuration is correctly configured to connect to the intended Firebase project.

Project Information

* Project: QueueLess Secure
* Project Type: Academic Security Application
* Development Approach: Agile
* Deployment: Firebase Hosting

Project Firebase Hosting Link
https://queueless-c563d.web.app
