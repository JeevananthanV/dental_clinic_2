# Dental Clinic Management System

## Project Overview
This project is a comprehensive Dental Clinic Management System consisting of a React/Vite frontend and a Node.js/Express backend. 

## Features
- Patient Management
- Appointment Scheduling
- Secure Admin Dashboard

## Technologies Used
- **Frontend**: React, Vite
- **Backend**: Node.js, Express
- **Database**: MongoDB

## Prerequisites
- Node.js installed
- MongoDB running locally or remotely

## Installation and Setup

### 1. Clone the repository and navigate into the directory
### 2. Setup Backend
```bash
cd backend
npm install
```
- Create a `.env` file in the `backend` directory based on `.env.example`:
  ```env
  PORT=5000
  MONGODB_URI=your_mongodb_connection_string
  JWT_SECRET=your_jwt_secret
  ADMIN_USERNAME=your_admin_username
  ADMIN_PASSWORD=your_admin_password
  ```
- Run the backend server:
```bash
npm run dev
# or node server.js
```

### 3. Setup Frontend
```bash
cd frontend
npm install
```
- Run the frontend development server:
```bash
npm run dev
```

## Additional Documentation
Refer to `Case_Study.md`, `Project_Report.md`, and `User_Manual.md` for more details about the design, architecture, and manual operations of the project.
