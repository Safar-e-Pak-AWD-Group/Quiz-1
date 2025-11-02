# Read-Me
Backend For the Safar-e-Pak web project

# Quiz 1 – Advanced Web Development

## 🎯 Task Overview
This project covers complete **Validation and Authentication** for a Registration and Login system using the MERN stack.

## ✅ Features Implemented

1. **Client-Side Validation (React)**
   - Registration Form validation (email, password, confirm password)
   - Login Form validation
   - Redirection after successful signup and login

2. **Server-Side Validation (Express + MongoDB)**
   - Input sanitization and validation (`middlewares/validation.js`)
   - Secure password handling with bcrypt
   - JWT Token generation for authentication

3. **Database Integration**
   - User registration data stored in MongoDB
   - Login checks user credentials from DB

4. **Dashboard Page**
   - Shows logged-in user info
   - Logout functionality implemented

5. **Technologies Used**
   - **Frontend:** React + Vite + Custom CSS
   - **Backend:** Node.js, Express.js, MongoDB, JWT
   - **Validation:** Validator.js, custom sanitize middleware

## 🧪 How to Run
```bash
# Backend
cd backend
npm install
nodemon index.js

# Frontend
cd frontend
npm install
npm run dev
