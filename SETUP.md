# Dental Clinic Management System (Edition 2) — Setup Guide

Welcome to the **Dental Clinic Management System (Edition 2)** setup guide. This system features a React + Vite frontend and an Express.js + MongoDB backend.

- **GitHub Repository**: [https://github.com/JeevananthanV/dental_clinic_2](https://github.com/JeevananthanV/dental_clinic_2)
- **Author**: Jeevananthan V

---

## 📋 System Prerequisites

- **Node.js**: v18.0.0 or higher
- **npm**: v9.0.0 or higher
- **MongoDB**: Local MongoDB instance or Atlas connection string

---

## 📥 1. Clone the Repository

```bash
git clone https://github.com/JeevananthanV/dental_clinic_2.git
cd dental_clinic_2
```

---

## ⚙️ 2. Environment Variables Configuration

### Backend Environment (`backend/.env`)

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=dental_clinic_edition2_jwt_secret
ADMIN_USERNAME=admin
ADMIN_PASSWORD=adminpassword
```

---

## 📦 3. Install Dependencies

```bash
# 1. Backend Dependencies
cd backend
npm install

# 2. Frontend Dependencies
cd ../frontend
npm install
cd ..
```

---

## 🚀 4. Running Locally

### Terminal 1: Backend Server (Port 5000)

```bash
cd backend
npm run dev
```

### Terminal 2: Frontend Client (Port 5173)

```bash
cd frontend
npm run dev
```
Open `http://localhost:5173` in your browser.
