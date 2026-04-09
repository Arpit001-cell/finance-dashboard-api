# 💰 Finance Dashboard API

## 📌 Overview
This project is a backend system for managing financial records with role-based access control.  
It allows different types of users to interact with financial data based on their roles.

The system focuses on clean backend architecture, proper data handling, and secure access control.

---

## 🚀 Tech Stack
- Java (Spring Boot)
- MySQL / H2 Database
- REST APIs
- Postman (API Testing)

---

## ✨ Features
- ✔ User Management (Admin, Analyst, Viewer)
- ✔ Role-Based Access Control (RBAC)
- ✔ CRUD Operations for Financial Records
- ✔ Dashboard Summary APIs
- ✔ Filtering (date, type, category)
- ✔ Input Validation & Error Handling

---

## 🔐 Roles & Access Control
| Role    | Permissions |
|--------|------------|
| Admin  | Full access (Create, Update, Delete, Manage Users) |
| Analyst| View records + access insights |
| Viewer | Read-only access |

---

## 📡 API Endpoints

### 👤 User APIs
- `POST /users` → Create user  
- `GET /users` → Get all users  

### 💵 Financial Records APIs
- `POST /records` → Create record  
- `GET /records` → Get records  

### 📊 Dashboard APIs
- `GET /dashboard/summary` → Get financial summary  

---

## 🧪 Sample JSON (Create Record)
```json
{
  "amount": 5000,
  "type": "income",
  "category": "salary",
  "date": "2026-04-01",
  "notes": "Monthly salary"
}
