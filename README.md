## Prescripto - A Full Stack Doctor Appointment Booking System


This project is a **MERN Stack** (MongoDB, ExpressJS, ReactJS, NodeJS) application designed to build a complete Doctor Appointment Booking System. The system provides a seamless experience for patients, doctors, and administrators through three levels of authentication.

## Features

### Patient Functionality:
1. **Login/Signup**: Patients can create an account or log in to their existing account.
2. **Book Appointments**: Patients can browse available doctors and book appointments.
3. **Manage Appointments**: View, reschedule, or cancel booked appointments.

### Doctor Functionality:
1. **Login/Signup**: Doctors can log in to their profile.
2. **View Appointments**: Doctors can see their daily schedules and appointment details.
3. **Earnings Management**: Doctors can track their earnings.
4. **Profile Management**: Doctors can update their profiles directly from the dashboard.

### Admin Dashboard:
1. **Appointment Management**: Admin can manage all appointments, ensuring smooth operations.
2. **Doctor Management**: Admin can add, edit, or remove doctor profiles.

### Payment Integration:
- **Razorpay Integration**: Patients can pay their appointment fees online securely through Razorpay.

## Live Demo
- **Main Website (Patient Login/Signup Page/Create Account)**: [Patient Portal](https://prescripto-frontend-gfq6.onrender.com)
- **Admin Dashboard**: [Admin Portal](https://prescripto-admin-5tcw.onrender.com)

## Tech Stack
- **Frontend**: React JS, React Router DOM, React Toastify
- **Backend**: Node JS, Express JS
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT) and bcrypt for secure password hashing
- **File Upload**: Cloudinary and multer for profile and document uploads

## Prerequisites
- **Node.js** and **npm** installed on your machine.
- MongoDB instance set up locally or on a cloud service.
- Razorpay account for payment integration.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/prescripto.git
   cd prescripto
   ```

2. Install dependencies in each folder:
   ```bash
   npm install
   ```

3. Create a `.env` file in the `server` directory and configure the following variables:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   CLOUDINARY_NAME=your_cloudinary_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   RAZORPAY_KEY_ID=your_razorpay_key_id
   RAZORPAY_KEY_SECRET=your_razorpay_key_secret
   ```

4. Start the backend server:
   ```bash
   cd backend
   npm run server
   ```
5. Start the admin server:
   ```bash
   cd admin
   npm run dev
   ```

6. Start the frontend:
   ```bash
   cd frontend
   npm run dev
   ```



## Dependencies

### Server-Side:
```json
"dependencies": {
  "axios": "^latest",
  "bcrypt": "^latest",
  "cloudinary": "^latest",
  "cors": "^latest",
  "dotenv": "^latest",
  "express": "^latest",
  "jsonwebtoken": "^latest",
  "mongoose": "^latest",
  "multer": "^latest",
  "nodemon": "^latest",
  "razorpay": "^latest",
  "validator": "^latest"
}
```

### Client-Side:
```json
"dependencies": {
  "react": "^latest",
  "react-dom": "^latest",
  "react-router-dom": "^latest",
  "react-toastify": "^latest"
}
```
