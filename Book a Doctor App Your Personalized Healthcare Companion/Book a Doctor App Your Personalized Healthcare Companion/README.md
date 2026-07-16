# 🩺 Book a Doctor App: Your Personalized Healthcare Companion

## 📖 Overview

**Book a Doctor App** is a full-stack healthcare appointment booking platform that simplifies the process of connecting patients with qualified doctors. The application provides a secure, fast, and user-friendly environment where patients can search for doctors, book appointments, make online payments, and manage their healthcare records. Doctors can efficiently organize their schedules, while administrators oversee the entire system to ensure smooth operations.

Built using the **MERN Stack (MongoDB, Express.js, React.js, and Node.js)**, the application offers secure authentication with **JWT** and supports **Stripe** and **Razorpay** payment gateways for safe and seamless online transactions.

---

# 🚀 Tech Stack

* **Frontend:** React.js
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **Authentication:** JSON Web Token (JWT)
* **Payment Integration:** Stripe & Razorpay

---

# ✨ Features

## 👤 Patient Module

Patients can:

* Register and log in securely.
* Browse doctors by specialization.
* View doctor profiles, qualifications, experience, and consultation fees.
* Book appointments by selecting an available date and time.
* Cancel appointments when required.
* Pay consultation fees using Cash, Stripe, or Razorpay.
* Update personal profile details including photo, address, gender, and date of birth.
* View current and previous appointment history.

---

## 👨‍⚕️ Doctor Module

Doctors can:

* Log in securely.
* Manage appointment schedules.
* View patient appointment details.
* Mark appointments as completed or cancel them.
* Monitor total earnings and appointment statistics.
* Update profile information including fees, description, address, and availability status.

---

## 🛡️ Admin Module

Administrators have complete control over the system by:

* Managing doctor accounts.
* Adding new doctors.
* Viewing all appointments.
* Monitoring patients, doctors, and appointment statistics.
* Cancelling or completing appointments.
* Maintaining overall platform operations.

---

# 🏠 Application Pages

### Home

* Browse featured doctors.
* Search doctors by specialty.
* Navigate to About, Contact, and other sections.

### Doctors

* Display all registered doctors.
* Filter doctors according to specialization.
* View complete doctor profiles.

### Appointment Booking

* Select appointment date and time.
* Choose preferred payment method.
* Receive booking confirmation.

### About

* Information about the platform.
* Vision and mission.
* Benefits of using the application.

### Contact

* Office information.
* Contact details.
* Career opportunities.

### User Profile

* Edit profile information.
* Upload profile picture.
* Manage appointments.
* Logout securely.

---

# 💳 Payment Methods

The application supports multiple payment options:

* Cash Payment
* Stripe Payment Gateway
* Razorpay Payment Gateway

These payment methods ensure secure and reliable transactions.

---

# 📊 Dashboard Features

### Admin Dashboard

* Total Doctors
* Total Patients
* Total Appointments
* Recent Bookings
* Doctor Management
* Appointment Management

### Doctor Dashboard

* Total Earnings
* Patient Count
* Appointment Count
* Latest Appointments
* Profile Management

---

# 🔐 Security

* JWT-based Authentication
* Protected API Routes
* Role-Based Authorization
* Secure Password Handling
* Protected Payment Processing

---

# ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/your-username/book-a-doctor-app.git
cd book-a-doctor-app
```

### Install Dependencies

```bash
npm install

cd frontend
npm install

cd ../backend
npm install
```

### Configure Environment Variables

Create a **.env** file inside the backend folder.

```env
MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

STRIPE_SECRET_KEY=your_stripe_secret_key

RAZORPAY_KEY_ID=your_key_id

RAZORPAY_KEY_SECRET=your_key_secret
```

### Run the Application

```bash
npm run dev
```

---

# 📁 Project Structure

```plaintext
Book-a-Doctor-App/
│
├── frontend/
│   ├── components/
│   ├── pages/
│   ├── assets/
│   └── context/
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── models/
│   ├── config/
│   └── server.js
│
├── package.json
├── README.md
└── .env
```

---

# 🎯 Key Benefits

* Easy appointment scheduling
* Secure online payments
* Efficient doctor schedule management
* User-friendly interface
* Fast and reliable healthcare access
* Centralized appointment management
* Role-based access for Patients, Doctors, and Admins

---

# 🤝 Contributing

Contributions are welcome. Feel free to fork this repository, create a new branch, and submit a pull request with improvements or bug fixes.

---

# 🙏 Acknowledgements

Special thanks to the developers and communities behind **MongoDB**, **Express.js**, **React.js**, **Node.js**, **JWT**, **Stripe**, and **Razorpay** for providing the technologies that made this project possible.


