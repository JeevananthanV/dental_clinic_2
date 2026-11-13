# Dental Clinic Management System — Edition 2

[![Repository](https://img.shields.io/badge/GitHub-JeevananthanV%2Fdental__clinic__2-blue?logo=github)](https://github.com/JeevananthanV/dental_clinic_2)
[![Frontend](https://img.shields.io/badge/Frontend-React%20%2B%20Vite-61DAFB?logo=react&logoColor=white)](https://react.dev)
[![Backend](https://img.shields.io/badge/Backend-Node.js%20%2B%20Express-339933?logo=nodedotjs&logoColor=white)](https://nodejs.org)
[![Database](https://img.shields.io/badge/Database-MongoDB-47A248?logo=mongodb&logoColor=white)](https://www.mongodb.com)

A comprehensive Dental Clinic Management System featuring patient records, real-time appointment scheduling, and a secure administration command center.

---

## 🔗 Repository Links

| Detail | Link |
|---|---|
| **GitHub Repository** | [https://github.com/JeevananthanV/dental_clinic_2](https://github.com/JeevananthanV/dental_clinic_2) |
| **Author** | [Jeevananthan V](https://github.com/JeevananthanV) |
| **Frontend Dev Server** | `http://localhost:5173` |
| **Backend API** | `http://localhost:5000` |

---

## ✨ Features

- **Patient Management**: Full demographic records, medical history, and contact logging.
- **Appointment Scheduling**: Real-time slot management, status tracking, and doctor allocations.
- **Secure Admin Dashboard**: Role-based access control, analytics charts, and operational tools.

---

## 📁 Repository Structure

```
Dental_Clinic_2/
├── backend/                  # Node.js + Express API
│   ├── config/               # Database connection
│   ├── controllers/          # Business logic handlers
│   ├── models/               # MongoDB Mongoose schemas
│   ├── routes/               # Express REST endpoints
│   └── server.js             # API entry point
│
├── frontend/                 # React + Vite application
│   ├── src/                  # React components, pages, and hooks
│   ├── package.json
│   └── vite.config.js
│
├── Case_Study.md             # In-depth clinical case study
├── Project_Report.md         # Architecture & engineering report
└── User_Manual.md            # Operator and patient instruction guide
```

---

## 🚀 Installation and Setup

### Clone Repository

```bash
git clone https://github.com/JeevananthanV/dental_clinic_2.git
cd dental_clinic_2
```

### 1. Setup Backend

```bash
cd backend
npm install
```

Create a `.env` file in `backend/`:
```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
ADMIN_USERNAME=your_admin_username
ADMIN_PASSWORD=your_admin_password
```

Start the backend:
```bash
npm run dev
```

### 2. Setup Frontend

```bash
cd ../frontend
npm install
npm run dev
```

The frontend will run on `http://localhost:5173`.

---

## 👨‍💻 Author

**Jeevananthan V** — [@JeevananthanV](https://github.com/JeevananthanV)

## License

MIT
