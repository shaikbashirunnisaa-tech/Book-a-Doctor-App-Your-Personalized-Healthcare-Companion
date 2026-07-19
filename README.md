Book a Doctor App is a full-stack healthcare appointment booking platform that simplifies the process of connecting patients with qualified doctors. The application provides a secure, fast, and user-friendly environment where patients can search for doctors, book appointments, make online payments, and manage their healthcare records. Doctors can efficiently organize their schedules, while administrators oversee the entire system to ensure smooth operations.

Built using the MERN Stack (MongoDB, Express.js, React.js, and Node.js), the application offers secure authentication with JWT and supports Stripe and Razorpay payment gateways for safe and seamless online transactions.

🚀 Tech Stack
Frontend: React.js
Backend: Node.js, Express.js
Database: MongoDB
Authentication: JSON Web Token (JWT)
Payment Integration: Stripe & Razorpay
---Demo video:https://drive.google.com/file/d/1_BbQTKYWJfyS-2KR5IZYpSRMMPTmTSP_/view?usp=drivesdk ---Live Demo:https://prescriptoapp-wheat.vercel.app/

✨ Features
👤 Patient Module
Patients can:

Register and log in securely.
Browse doctors by specialization.
View doctor profiles, qualifications, experience, and consultation fees.
Book appointments by selecting an available date and time.
Cancel appointments when required.
Pay consultation fees using Cash, Stripe, or Razorpay.
Update personal profile details including photo, address, gender, and date of birth.
View current and previous appointment history.
👨‍⚕️ Doctor Module
Doctors can:

Log in securely.
Manage appointment schedules.
View patient appointment details.
Mark appointments as completed or cancel them.
Monitor total earnings and appointment statistics.
Update profile information including fees, description, address, and availability status.
🛡️ Admin Module
Administrators have complete control over the system by:

Managing doctor accounts.
Adding new doctors.
Viewing all appointments.
Monitoring patients, doctors, and appointment statistics.
Cancelling or completing appointments.
Maintaining overall platform operations.
🏠 Application Pages
Home
Browse featured doctors.
Search doctors by specialty.
Navigate to About, Contact, and other sections.
Doctors
Display all registered doctors.
Filter doctors according to specialization.
View complete doctor profiles.
Appointment Booking
Select appointment date and time.
Choose preferred payment method.
Receive booking confirmation.
About
Information about the platform.
Vision and mission.
Benefits of using the application.
Contact
Office information.
Contact details.
Career opportunities.
User Profile
Edit profile information.
Upload profile picture.
Manage appointments.
Logout securely.
💳 Payment Methods
The application supports multiple payment options:

Cash Payment
Stripe Payment Gateway
Razorpay Payment Gateway
These payment methods ensure secure and reliable transactions.

📊 Dashboard Features
Admin Dashboard
Total Doctors
Total Patients
Total Appointments
Recent Bookings
Doctor Management
Appointment Management
Doctor Dashboard
Total Earnings
Patient Count
Appointment Count
Latest Appointments
Profile Management
🔐 Security
JWT-based Authentication
Protected API Routes
Role-Based Authorization
Secure Password Handling
Protected Payment Processing
⚙️ Installation
Clone Repository
git clone https://github.com/your-username/book-a-doctor-app.git
cd book-a-doctor-app
Install Dependencies
npm install

cd frontend
npm install

cd ../backend
npm install
Configure Environment Variables
Create a .env file inside the backend folder.

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

STRIPE_SECRET_KEY=your_stripe_secret_key

RAZORPAY_KEY_ID=your_key_id

RAZORPAY_KEY_SECRET=your_key_secret
Run the Application
npm run dev
📂 Project Structure
Book-a-Doctor-App-Your-Personalized-Healthcare-Companion/
│
├── 1. Ideation Phase/
│   └── README.md
│
├── 2. Requirement Analysis/
│   └── README.md
│
├── 3. Project Design Phase/
│   └── README.md
│
├── 4. Project Planning/
│   └── README.md
│
├── 5. Project Development/
│   └── README.md
│
├── 6. Project Documentation/
│   └── README.md
│
├── 7. Project Demonstration/
│   └── README.md
│
├── frontend/
│   ├── public/
│   ├── src/
│   └── package.json
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── package.json
│
└── README.md
This repository contains a full-stack MERN healthcare appointment booking application along with complete project documentation.

Ideation Phase – Project idea, objectives, and problem statement.
Requirement Analysis – Functional and non-functional requirements.
Project Design Phase – System architecture, database design, and UI planning.
Project Planning – Timeline, milestones, and development roadmap.
Project Development – Development process and implementation details.
Project Documentation – Technical documentation, installation guide, and user manual.
Project Demonstration – Demo video, screenshots, and project presentation.
frontend – React.js client application.
backend – Node.js, Express.js, and MongoDB server application.
🎯 Key Benefits
Easy appointment scheduling
Secure online payments
Efficient doctor schedule management
User-friendly interface
Fast and reliable healthcare access
Centralized appointment management
Role-based access for Patients, Doctors, and Admins
