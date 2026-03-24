<<<<<<< HEAD
# Prescripto - Hospital Management System

## Description
**Prescripto** is a comprehensive Hospital Management System built on the MERN stack to enhance hospital operations. This system includes features such as secure user authentication, efficient appointment scheduling, patient record management, and real-time communication between doctors and patients. It provides a scalable and user-friendly platform to streamline healthcare workflows and improve the hospital experience.

## Features
- **User Authentication**: Secure login for patients, doctors, and administrators.
- **Appointment Scheduling**: Easy booking, rescheduling, and cancellation of appointments.
- **Patient Records Management**: Store, access, and update patient health records.
- **Doctor-Patient Communication**: Real-time messaging for consultations and follow-ups.
- **Admin Dashboard**: Manage users, appointments, and view analytics.
- **Secure Data Storage**: Ensure patient privacy and data security with MongoDB.

## Tech Stack
- **Frontend**: React.js
- **Backend**: Node.js and Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **State Management**: Redux (optional)

## Getting Started
Follow these instructions to set up the project locally.

### Prerequisites
- Node.js installed
- MongoDB installed or access to a MongoDB cloud instance
- Git installed

### Installation
1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/Prescripto-Hospital_Management_System.git
   cd Prescripto-Hospital_Management_System

## Install dependencies

1. **Install admin dependencies**
   ```bash
   cd admin
   npm install
   ```

2. **Install frontend dependencies**
   ```bash
   cd frontend
   npm install
   ```

3. **Set up environment variables**
   In the server directory, create a .env file with the following:

   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   Run the application

4. **Start server:**
   ```bash
   cd backend
   npm run server
   ```

5. **Start Admin Panel:**
   ```bash
   cd admin
   npm run dev
   ```

6. **Start Frontend Panel:**
   ```bash
   cd frontend
   npm run dev
   ```

# Topics
Hospital Management, MERN Stack, MongoDB, Express.js, React, Node.js, Healthcare App, Patient Records, Appointments.

# Contributors
Niraj Kumar [Github](https://github.com/meniraj07)

# Deployment Links
[Prescripto Backend](https://prescriptobackend-4ylq.onrender.com)

[Prescripto Patient Panel](https://prescripto-hospital-management-system.vercel.app/)

[Prescripto Admin/Doctor Panel](https://prescripto-hospital-management-system-c29o.vercel.app/)

# Contact
For any questions or feedback, please contact [Niraj Kumar](https://www.linkedin.com/in/nirajkumar-nk/)

# License
This project is licensed under the MIT License.
=======
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

🙌 Contributions

Pull requests are welcome. For major changes, please open an issue first to discuss.

⭐ Show Your Support

If you like this project, consider giving it a ⭐ on GitHub!
  Payment gateway integration
  Secure password hashing (bcrypt)
  Middleware-protected routes
>>>>>>> 20024e3f84aa01763898d6cc4b88409650203f54
