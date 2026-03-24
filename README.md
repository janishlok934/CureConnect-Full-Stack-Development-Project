🚑 CureConnect – Full Stack Doctor Appointment Booking System

CureConnect is a full-stack medical appointment booking platform designed for clinics and healthcare centers. It provides patients an easy way to book doctor appointments online and offers an admin panel to manage doctors, schedules, users, and payments.

Built with React (Vite), Node.js, Express, MongoDB, Tailwind CSS, and modern tools like Cloudinary, JWT, Multer, Razorpay/Stripe, this project showcases complete end-to-end full-stack development.

🚀 Features
👨‍⚕️ Patient (Frontend)
Browse doctors by specialization
View detailed doctor profiles
Book appointments with date & time slot
Online payments via Razorpay / Stripe
Login & Registration (JWT based)
Profile & appointment history
Cancel appointments
Toast notifications for all actions
🛠️ Admin Panel
Secure admin login
Add / edit / delete doctors
Manage doctor schedules
Approve / cancel appointments
View all registered users
Track payments
Dashboard analytics
🖥️ Backend
RESTful API architecture
User & admin authentication (JWT)
MongoDB database models
Cloud image upload (Multer + Cloudinary)
Payment gateway integration
Secure password hashing (bcrypt)
Middleware-protected routes
🛠️ Tech Stack
Frontend (Patient App)
React.js (Vite)
React Router DOM
Tailwind CSS
Axios
React Toastify
Admin Panel
React.js (Vite)
Tailwind CSS
Axios
React Router DOM
React Toastify
Backend
Node.js
Express.js
MongoDB + Mongoose
JWT (jsonwebtoken)
bcrypt
Cloudinary
Multer
Razorpay / Stripe
dotenv
CORS
📁 Project Structure
CureConnect/
│
├── admin/        # Admin Panel (React + Vite)
├── frontend/     # Patient Frontend (React + Vite)
└── backend/      # Node.js/Express Backend API
⚙️ Installation & Setup Guide
1️⃣ Clone the repository
git clone https://github.com/janishlok934/CureConnect-Full-Stack-Development-Project.git
2️⃣ Install dependencies for each part
🔹 Backend
cd backend
npm install
npm run server     # or: npm start
🔹 Frontend (Patient App)
cd ../frontend
npm install
npm run dev
🔹 Admin Panel
cd ../admin
npm install
npm run dev
🔑 Environment Variables

Inside backend/.env create:

MONGO_URL=your_mongo_database_url
JWT_SECRET=your_secret_key
CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_key
CLOUDINARY_API_SECRET=your_secret
RAZORPAY_KEYID=your_key
RAZORPAY_SECRET=your_secret
STRIPE_SECRET_KEY=your_key
🔒 Security Features
JWT authentication for secure login
Password hashing with bcrypt
Protected routes for admin & users
Input validation using validator.js
💳 Payment Integration

Supports:

Razorpay online payments
Stripe payment processing

Backend verifies payment & stores transaction details.

📸 Screenshots (Add later)

You can add UI screenshots here once available.

🙌 Contributions

Pull requests are welcome. For major changes, please open an issue first to discuss.

⭐ Show Your Support

If you like this project, consider giving it a ⭐ on GitHub!
