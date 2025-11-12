

<<div align="center">
  <br />
  <img width="1470" alt="Screenshot 2025-05-27 at 1 18 06 PM" src="https://github.com/user-attachments/assets/a0d3d443-f5e1-433a-85a7-a76a3866858d" />
  <br /><br />

  <h2>🏥 Telemedicine Appointment Platform</h2>

  <p>
    A full-stack <b>telemedicine web application</b> built with <b>Next.js</b> and <b>Shadcn UI</b>, featuring secure authentication, doctor onboarding, subscription management, appointment booking, and real-time video consultations powered by the <b>Vonage Video API</b>.
  </p>

  <p><b>Developed by John Moshe Nayak Bhukya</b><br/>Full Stack Developer | AI & Web Enthusiast</p>

  <hr />
</div>

## 📘 Project Overview

**Telemedicine Appointment Platform** is a comprehensive web-based solution designed to connect **patients and doctors** seamlessly through **secure, real-time virtual consultations**.  

It provides a full workflow from **user sign-up, doctor onboarding, appointment scheduling, and subscription management**, to **live video calls** using **Vonage API integration**.

Built for **scalability, performance, and user-friendliness**, this platform showcases how modern technologies can revolutionize healthcare accessibility.

---

## 🧩 Key Features

### 🔐 User Authentication
- Secure sign-up, login, and session management using industry-standard authentication.
- Role-based access for **patients**, **doctors**, and **admins**.

### 💳 Subscription Plans
- Multiple tiered subscription options.
- Automatic access management based on plan type.
- Integration-ready for payment gateways like **Stripe**.

### 🩺 Doctor Onboarding
- Doctors can register, submit credentials, and get approved by the admin.
- Verification workflow ensures trusted medical professionals on the platform.

### 🧑‍⚕️ Doctor Dashboard
- Manage schedules, view appointments, and update availability.
- Add notes or mark appointments as complete.

### 📅 Appointment Booking
- Patients can browse available doctors, filter by specialty, and book time slots.
- Automated reminders for both patients and doctors.

### 🎥 Real-Time Video Consultation
- Integrated **Vonage Video API** for seamless, high-quality video calls.
- Encrypted peer-to-peer connections for patient confidentiality.

### 🩹 Notes & Appointment Status
- Doctors can record notes post-consultation.
- Patients can view appointment history and outcomes.

### 🧠 Admin Dashboard
- Manage user roles, doctor approvals, and system analytics.
- Oversee all appointments, payments, and subscription activity.

### 📱 Responsive UI/UX
- Built with **Next.js** and **Shadcn UI**, ensuring a sleek, consistent interface across devices.

### 🗄️ Database Design
- Well-structured schema for managing:
  - Users  
  - Doctors  
  - Appointments  
  - Subscriptions  
  - Notes and Availability

---

## ⚙️ Tech Stack

| Layer | Technologies Used |
|:------|:------------------|
| **Frontend** | Next.js 15, Shadcn UI, TailwindCSS |
| **Backend** | Next.js API Routes, Node.js |
| **Database** | PostgreSQL / Prisma ORM |
| **Authentication** | Clerk / NextAuth |
| **Video Calls** | Vonage Video API |
| **Payments (optional)** | Stripe Integration Ready |
| **Deployment** | Vercel / Render |
| **Styling** | TailwindCSS + Shadcn UI Components |

---

## 🧠 System Flow

1. **User Registration** → Create a patient or doctor account.  
2. **Doctor Verification** → Admin reviews credentials and approves.  
3. **Subscription Management** → Patients select a plan for consultations.  
4. **Appointment Scheduling** → Choose a doctor and time slot.  
5. **Real-Time Consultation** → Join video call powered by Vonage API.  
6. **Post-Call Updates** → Doctors add notes or mark as completed.  
7. **Admin Oversight** → Manage and monitor all platform activities.

---

## 📸 UI Preview

<div align="center">
  <img width="90%" src="https://github.com/user-attachments/assets/a0d3d443-f5e1-433a-85a7-a76a3866858d" alt="Telemedicine Dashboard Screenshot" />
</div>

---

## 🚀 Getting Started

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/johnmoshenayakbhukya/telemedicine-platform.git
cd telemedicine-platform

