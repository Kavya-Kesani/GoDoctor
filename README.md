# GoDoctor - Healthcare & Appointment Management System

## Overview

GoDoctor is a full-stack MERN healthcare management system designed to simplify doctor appointment booking, prescription management, patient monitoring, and support management through a centralized digital platform.

The system provides separate modules for:
- Patients
- Doctors
- Support Staff
- Administrators

GoDoctor helps users efficiently manage healthcare services online with secure authentication, appointment scheduling, digital prescriptions, notifications, and support ticket management.

---

# Tech Stack

## Frontend
- React.js
- JavaScript
- HTML5
- CSS3
- Axios
- React Router DOM
- Tailwind CSS

## Backend
- Node.js
- Express.js

## Database
- MongoDB
- Mongoose

## Authentication & Security
- JWT Authentication
- bcrypt Password Hashing

---

# Project Structure

```bash
GODOCTOR
│
├── backend
│   ├── config
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── scripts
│   ├── server.js
│   └── package.json
│
├── frontend
│   ├── public
│   ├── src
│   ├── package.json
│   └── tailwind.config.js
│
├── .gitignore
└── README.md
```

---

# Features

## Patient Module
- User Registration & Login
- Book Appointments
- View Prescriptions
- Medical History
- Profile Management
- Support Ticket System

## Doctor Module
- Manage Appointments
- Patient Records
- Prescription Management
- Availability Scheduling
- Profile Management

## Support Module
- Ticket Management
- User Issue Resolution
- Support Dashboard

## Admin Module
- User Management
- Doctor Management
- Appointment Monitoring
- System Dashboard

---

# Authentication & Security

- JWT-based Authentication
- Protected Routes
- Password Hashing using bcrypt
- Role-Based Access Control
- Secure MongoDB Connection

---

# Installation & Setup

## Prerequisites

Install the following software before running the project:

- Node.js (v16 or above)
- MongoDB
- npm

---

# Clone Repository

```bash
git clone https://github.com/yourusername/GoDoctor.git
```

Move into project folder:

```bash
cd GoDoctor
```

---

# Backend Setup

Move into backend folder:

```bash
cd backend
```

Install backend dependencies:

```bash
npm install
```

---

# Create .env File

Inside backend folder create a file named:

```bash
.env
```

Add the following environment variables:

```env
PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/godoctor
JWT_SECRET=godoctor123
```

Example using MongoDB Atlas:

```env
PORT=5000
MONGO_URI=your_mongodb_atlas_connection_string
JWT_SECRET=your_secret_key
```

---

# Start Backend Server

```bash
npm run dev
```

Backend server will run on:

```bash
http://localhost:5000
```

---

# Frontend Setup

Open new terminal and move into frontend folder:

```bash
cd frontend
```

Install frontend dependencies:

```bash
npm install
```

---

# Start Frontend Server

```bash
npm start
```

Frontend application will run on:

```bash
http://localhost:3000
```

---

# Installing Node Modules

The `node_modules` folders are not included in GitHub because they are ignored using `.gitignore`.

After cloning the repository, install dependencies manually using:

## Backend

```bash
cd backend
npm install
```

## Frontend

```bash
cd frontend
npm install
```

This command will automatically install all required packages from `package.json`.

---

# API Structure

The backend follows RESTful API architecture.

## Main API Modules

- Authentication APIs
- Doctor APIs
- Patient APIs
- Appointment APIs
- Prescription APIs
- Notification APIs
- Support Ticket APIs
- Admin APIs

---

# MVC Architecture

GoDoctor follows the MVC (Model View Controller) architecture.

## Model
Handles MongoDB schemas and database operations.

## View
Frontend React.js components and UI.

## Controller
Handles business logic and API processing.

---

# Database

MongoDB is used as the primary database.

Collections include:
- Users
- Doctors
- Patients
- Appointments
- Prescriptions
- Notifications
- Support Tickets

---
# CODE EXPLANATION VIDEO

https://drive.google.com/file/d/1kkL06tgKvIupk0tOQXkRaX_uMUVcMu3y/view?usp=sharing

---

# PROJECT OVERVIEW VIDEO

https://drive.google.com/file/d/1LtMGW64gkcqIi3r0RWr986Dxvj9TlxhV/view?usp=drivesdk

---

# Future Enhancements

- Video Consultation
- Online Payment Gateway
- AI Health Recommendations
- Real-time Chat
- Email & SMS Notifications
- Mobile Application

---

# Author

K.Kavya

# License

This project is developed for educational and academic purposes.
