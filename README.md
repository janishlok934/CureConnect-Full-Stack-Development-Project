🩺 CureConnect – Full Stack Doctor Appointment Booking System

A complete end-to-end medical appointment booking system built using React (Frontend + Admin Panel) and Node.js/Express (Backend) with secure authentication, doctor management, patient dashboard, schedule booking, online payments, cloud image storage, and more.

Designed as a Full Stack Development (FSD) project using modern web technologies like Vite, Tailwind CSS, MongoDB, JWT, Cloudinary, Multer, Razorpay/Stripe, and React Router.

🚀 Project Highlights
🔹 Three-module system
Frontend (Patient Portal)
Browse doctors & specialization-wise filtering
Book appointments with available time slots
Online payments (Razorpay/Stripe)
Profile management
Appointment history
Toast notifications
Admin Panel
Add/Update/Delete doctors
Approve or reject appointments
Dashboard analytics
Secure admin authentication
Manage users and transactions
Backend (Node.js + Express)
RESTful APIs
User & Admin authentication using JWT
MongoDB models (Users, Doctors, Appointments, Payments)
Cloud image upload with Cloudinary
Password hashing using bcrypt
Middleware protection
Payment gateway integration
🛠️ Tech Stack
Frontend / Admin
React.js (Vite)
React Router DOM
Tailwind CSS
Axios
React Toastify
Backend
Node.js
Express.js
MongoDB + Mongoose
JWT (jsonwebtoken)
bcrypt
Multer
Cloudinary
CORS
dotenv
Razorpay / Stripe
💳 Payments

Supports online appointment payments using Razorpay or Stripe.
Includes:

Order creation
Secure transactions
Payment verification backend
☁️ Cloud Storage

Doctor profile images uploaded via:

Multer (local processing)
Cloudinary (cloud storage + CDN optimization)
🧩 Authentication
JWT-based Login & Registration
Secure password hashing
Protected routes for admin & patients
Token verification middleware
📊 Admin Features
Manage doctors
View all users
Approve/cancel appointments
Track payments
Dashboard analytics
👨‍⚕️ Patient Features
Search doctors by category
View doctor details
Select date & time
Make online booking payments
Track upcoming visits
Cancel appointments
📁 Project Structure
CureConnect/
│
├── admin/        → Admin Panel (React + Vite)
├── frontend/     → User App (React + Vite)
└── backend/      → Node.js/Express API + Database
