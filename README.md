# 🏥 MedFlow – AI Clinic Appointment System

MedFlow is an **AI-powered clinic appointment management system** that allows patients to **book, reschedule, and cancel doctor appointments directly through WhatsApp**.

The system uses **AI automation and workflow orchestration** to reduce manual work for clinics and provide a smooth booking experience for patients.

---

## 🚀 Demo Video

Watch the full project demo here:

🎥 https://www.youtube.com/watch?v=YFRONxSnXjw

---

## ✨ Features

### 📱 WhatsApp Appointment Booking
Patients can book doctor appointments directly through **WhatsApp chat**.

### 🤖 AI Receptionist
An AI assistant automatically interacts with patients and guides them through the booking process.

### 👨‍👩‍👧 Multiple Patients per User
One WhatsApp number can register and manage **multiple patients (family members)**.

### 📅 Smart Date Selection
The system automatically shows **available dates for the next 7 days**.

### ⏰ Automatic Time Slot Generation
Time slots are generated dynamically based on **doctor working hours** and **existing bookings**.

### 💳 Online Payment with Stripe
Patients can pay appointment fees securely using **Stripe payment links**.

### 💵 Cash at Clinic Option
Patients can also choose **Cash at Clinic** as a payment option.

### 📋 View Upcoming Appointments
Patients can check their **upcoming bookings anytime via WhatsApp**.

### 🔄 Reschedule Appointment
Users can easily **change their appointment date or time**.

### ❌ Cancel Appointment
Appointments can be cancelled directly from WhatsApp.

### 📄 Google Sheets Database
All patient and appointment data is stored in **Google Sheets** for simplicity and quick access.

### ✅ Automatic Payment Confirmation
Stripe webhook automatically updates **payment status after successful payment**.

### 🔔 Daily Appointment Reminders
Patients receive **automatic WhatsApp reminders** on the day of their appointment.

### ⚙️ Fully Automated Workflow
The entire system runs automatically using **n8n workflow automation**.

---

## 🖥 Dashboard

MedFlow also includes dashboards for:

### 👨‍⚕️ Doctor Dashboard
- View patient details  
- View upcoming appointments  
- Appointment calendar view  
- Daily appointment overview  

### 🧑‍💼 Receptionist Dashboard
- Add new patients  
- Schedule appointments  
- View patient records  
- Manage bookings easily  

---

## 🛠 Tech Stack

- **n8n** – Workflow Automation  
- **Twilio** – WhatsApp Messaging API  
- **Stripe** – Online Payment Gateway  
- **Google Sheets** – Data Storage  
- **AI Agent** – Conversational patient interaction  

---

## 🔄 Workflow Overview

1. Patient sends a message on **WhatsApp**
2. **Twilio Trigger** receives the message
3. **AI Agent** processes the request
4. Patient selects:
   - Book Appointment
   - View Appointment
   - Reschedule
   - Cancel
5. Appointment data is stored in **Google Sheets**
6. Payment link is generated using **Stripe**
7. **Stripe Webhook** confirms payment
8. **Reminder system** sends WhatsApp notification on appointment day

---

## 📌 Use Cases

- Small Clinics
- Hospitals
- Healthcare Startups
- Automated Reception Systems
- AI Healthcare SaaS

---

## 📬 Feedback

If you like this project, feel free to ⭐ star the repository and share your feedback!

---

## 👨‍💻 Author

**Henil Bhavsar**  
Computer Engineering Student | AI & Automation Enthusiast

---
## Contact

**Linkedin:**
https://www.linkedin.com/in/henil-bhavsar-18b45b311/

**Portfolio:**
https://henil-portfolio.netlify.app/

**Gmail**
henilbhavsar164@gmail.com
