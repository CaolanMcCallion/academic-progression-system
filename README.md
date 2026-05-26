# Academic Progression Monitoring System

## Overview

A full-stack web application designed to help students and administrators monitor academic progression, manage grades and modules, and communicate through an integrated messaging system.

The application supports role-based authentication, student performance tracking, administrative management tools, and CSV data uploads.

Built using Node.js, Express.js, MySQL, and EJS.

---

## Features

### Student Features
- Secure login system
- View and edit personal profile
- Track grades and academic progression
- Monitor credits and module performance
- Send and receive messages

### Admin Features
- Add, edit, and delete student records
- Manage modules and grades
- Upload students via CSV
- View academic progression data
- Send messages to students

---

## Technologies Used

### Backend
- Node.js
- Express.js
- MySQL
- Multer
- Express Sessions

### Frontend
- EJS
- Bootstrap
- HTML
- CSS
- JavaScript

---

## Key Concepts Demonstrated

- Full-stack web development
- CRUD functionality
- Authentication & session handling
- Role-based access control
- SQL database design
- CSV upload handling
- Dynamic server-side rendering

---

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/academic-progression-monitoring-system.git
```

Navigate into the project directory:

```bash
cd academic-progression-monitoring-system
```

Install dependencies:

```bash
npm install
```

---

## Database Setup

Create a MySQL database and import the provided SQL file:

```bash
mysql -u root -p < database.sql
```

---

## Environment Variables

Create a `.env` file in the root directory:

```env
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=academic_progression_db
```

---

## Running the Application

Start the application:

```bash
npm start
```

Or with nodemon:

```bash
npx nodemon index.js
```

The application will run on:

```text
http://localhost:3000
```

---

## Demo Credentials

### Admin Account
- Username: tester
- Password: ThisIsATest123

### Student Account
- Username: RyanAdams123
- Password: RyanPassword123

---

## Future Improvements

- Cloud deployment
- Improved analytics dashboard
- Enhanced authentication/security
- Mobile responsive UI improvements
- Email notifications
- Automated testing

---

## Author

Caolan McCallion

MSc Software Development Graduate — Queen’s University Belfast
