# 🏃 Athlete Performance Tracking System (APTS)

A full-stack web application designed to help athletes **record, monitor, and analyze training performance over time** through data-driven insights and analytics dashboards.

---

# Overview

The **Athlete Performance Tracking System (APTS)** enables athletes to digitally track training sessions and evaluate performance improvements using statistical analysis and visualization tools.

The platform focuses on:

* Structured training data recording
* Automated performance calculations
* Progress monitoring
* Analytical dashboards

This system follows a **modern scalable full-stack architecture** using REST APIs and modular backend design.

---

# Key Features

## ✅ Authentication & User Management

* Secure user registration and login
* JWT-based authentication
* Password hashing using bcrypt
* Profile management

---

## 🏋️ Training Session Management

Athletes can record detailed training sessions including:

* Start and end locations
* Distance covered (KM)
* Training duration
* Altitude information
* Environmental temperature
* Training notes
* Training date

### Automatic Calculations

* Average Speed
* Pace per Kilometer
* Historical performance comparison

---

## 📊 Performance Analytics

The system provides analytical insights such as:

* Per-kilometer split analysis
* Speed trends over time
* Fastest and slowest sessions
* Weekly performance totals
* Monthly summaries

Visualization includes:

* Distance progression
* Speed improvement trends
* Pace optimization charts

---

## 📈 Athlete Dashboard

The dashboard summarizes:

* Total distance covered
* Training session count
* Average speed
* Best pace achieved
* Weekly statistics
* Monthly progress overview

---

# 🏗 System Architecture

```
Client (Next.js Frontend)
            │
            ▼
REST API (Node.js + Express)
            │
            ▼
PostgreSQL Database
```

Architecture Principles:

* Separation of concerns
* RESTful API design
* Modular backend services
* Scalable database schema

---

# ⚙️ Technology Stack

## Frontend

* Next.js
* React
* CSS / Responsive UI

## Backend

* Node.js
* Express.js
* REST API

## Database

* PostgreSQL

## Security

* JWT Authentication
* bcrypt password hashing

---

# 🚀 Getting Started

## 1️⃣ Clone Repository

```bash
git clone https://github.com/Cheralia/AthletPerformanceFollowUp.git
cd AthletPerformanceFollowUp
```

---

## 2️⃣ Backend Setup

```bash
cd backend
npm install
npm run dev
```

---

## 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Application runs at:

```
http://localhost:3000
```

---

# 🔐 Environment Configuration

Create a `.env` file in the backend directory.

```
PORT=5000
DATABASE_URL=postgresql://user:password@localhost:5432/apts
JWT_SECRET=your_secret_key
```

---

# 📂 Project Structure

```
apts/
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   └── server.js
│
├── frontend/
│   ├── components/
│   ├── pages/
│   ├── services/
│   └── styles/
│
├── database/
│   └── schema.sql
│
└── README.md
```

---

# ⚡ Performance Requirements

* API response time < 2 seconds
* Support concurrent users
* Indexed database queries
* Optimized REST endpoints

---

# 🔒 Security Considerations

* Password hashing using bcrypt
* JWT protected endpoints
* Secure authentication middleware
* Input validation

---

# 🧭 Roadmap (Future Enhancements)

* GPS route visualization
* Wearable device integration
* Coach/Admin dashboard
* AI-based performance prediction
* Mobile application support

---



