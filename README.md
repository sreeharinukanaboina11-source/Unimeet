# Unimeet
# Student-Faculty Appointment Management System

## About the Project

Managing appointments between students and faculty members can often be time-consuming and confusing, especially when handled manually. This project was developed to make the entire process simple, organized, and efficient.

The **Student-Faculty Appointment Management System** is a full-stack web application that allows students to book appointments with faculty members based on their availability. Faculty members can manage their schedules, accept or reject appointment requests, while administrators have complete control over users and appointments. The application aims to reduce scheduling conflicts, improve communication, and provide a smooth experience for everyone involved.



## Features

###  For Students

* Create an account and log in securely.
* Browse available faculty members.
* Book appointments based on available time slots.
* View upcoming and previous appointments.
* Cancel or reschedule appointments when necessary.

###  For Faculty

* Manage available time slots.
* View appointment requests.
* Accept or reject appointments.
* Keep track of scheduled meetings.

###  For Administrators

* Manage student and faculty accounts.
* Monitor all appointments.
* Maintain overall system records.
* Ensure smooth functioning of the application.



## Technologies Used

### Frontend

* React.js
* Vite
* Tailwind CSS
* React Router
* Axios

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* Express Validator
* Nodemailer

---

## Why This Project?

The goal of this project is to replace the traditional manual appointment booking process with a secure and user-friendly digital solution. By providing separate dashboards for students, faculty, and administrators, the system makes appointment management faster, more transparent, and easier to use.

---

## Getting Started

Clone the repository:

```bash
git clone https://github.com/your-username/student-faculty-appointment-management.git
```

### Backend

```bash
cd backend
npm install
npm run dev
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```


## Environment Variables

Create a `.env` file in the backend folder and add the following:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
EMAIL_USER=your_email
EMAIL_PASS=your_email_password
```


## Future Improvements

Although the current version provides all the essential features for appointment management, there is always room for improvement. Some future enhancements include:

* Email and SMS notifications
* Google Calendar integration
* Video meeting support
* AI-based appointment recommendations
* Mobile application
* Analytics and reporting dashboard



## Acknowledgements

This project was developed as part of my learning journey in full-stack web development. It helped me gain practical experience in building scalable web applications using the MERN stack, implementing authentication, managing databases, and designing role-based systems.



## Author

**Sreehari Nukanaboina**

B.Tech – Computer Science and Engineering
SRM University AP

---

## License

This project is intended for educational purposes and is open for learning, modification, and future enhancements.
