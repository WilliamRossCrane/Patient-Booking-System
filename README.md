# 🏥 Patient Booking System

![Project Status](https://img.shields.io/badge/status-in%20progress-yellow)  
This project is under active development. A few features are still being polished before the final version.

This project is a comprehensive **Patient Booking System** built during the [JavaScript Mastery](https://jsmastery.pro/) course. It leverages the latest technologies, including **Next.js**, **TypeScript**, **TailwindCSS**, and **Appwrite** to provide a full-featured platform for managing patient registrations, appointments, and more.

Designed and taught by Adrian Hajdin of JavaScript Mastery, this build demonstrates how to create a **scalable**, **responsive**, and **production-ready** healthcare app with features such as SMS notifications, admin dashboards, and secure file uploads.

![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white) ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/-TailwindCSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white) ![Appwrite](https://img.shields.io/badge/-Appwrite-01a9d9?style=flat-square&logo=appwrite&logoColor=white) ![Twilio](https://img.shields.io/badge/-Twilio-FF5C8D?style=flat-square&logo=twilio&logoColor=white)

---

## 🐛 Bugs

---

## ⚙️ Tech Stack

- **Next.js** – Frontend framework for building SSR and static web applications
- **TypeScript** – Adds type safety to JavaScript for better maintainability
- **Appwrite** – Backend-as-a-Service for database, authentication, and file storage
- **TailwindCSS** – Utility-first CSS framework for fast, responsive design
- **Twilio** – SMS service for appointment notifications
- **Sentry** – Performance monitoring and error tracking
- **ShadCN** – Design system for building UI components

---

## 🔋 Features

👉 **Patient Registration**  
Users can create and manage their profiles as patients, storing all necessary personal information securely.

👉 **Appointment Booking**  
Patients can book multiple appointments with available doctors and view their appointment history.

👉 **Admin Dashboard**  
Administrators can manage, confirm, and cancel appointments directly from the admin interface.

👉 **SMS Notifications**  
Patients receive SMS notifications confirming appointment details, powered by Twilio.

👉 **Appointment Scheduling**  
Admins can set and adjust appointment times based on doctor availability.

👉 **File Uploads**  
Users can upload medical documents securely to the cloud using Appwrite's file storage.

👉 **Complete Responsiveness**  
The application works seamlessly on desktop, tablet, and mobile devices.

---

## 🤸 Quick Start

### ✅ Prerequisites

Make sure you have the following installed:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

### 📦 Install Dependencies

npm install

### 🔐 Set Up Environment Variables

Create a .env.local file in the root of your project and add the following:

APPWRITE - 
NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1

PROJECT_ID=<your_project_id>

API_KEY=<your_api_key>

DATABASE_ID=<your_database_id>

PATIENT_COLLECTION_ID=<patient_collection_id>

APPOINTMENT_COLLECTION_ID=<appointment_collection_id>

NEXT_PUBLIC_BUCKET_ID=<bucket_id>

NEXT_PUBLIC_ADMIN_PASSKEY=111111

Make sure to replace the placeholder values with your actual Appwrite credentials.

### 🚀 Run the Project Locally

npm run dev

Then, open your browser and go to http://localhost:3000 to see the app in action.

---

## 📺 Course Link

This project was built using the [JavaScript Mastery Healthcare Management System Course](https://jsm.dev/healthcare-kit).  

Watch the full tutorial on YouTube:  
🔗 [Build a Full Stack Healthcare Management System App (YouTube)](https://www.youtube.com/watch?v=O5cmLDVTgAs)

---

## 📄 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub and joining the JSMastery community:

- [JS Mastery Discord](https://discord.gg/jsmastery)
- [JS Mastery Pro](https://jsm.dev/uber-jsmpro)
- [More Projects](https://jsm.dev/uber-kit)
