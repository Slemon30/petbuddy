# 🐾 PetBuddy

PetBuddy is a full-stack web application that streamlines pet care by connecting pet owners with veterinary clinics, pet boarding houses, and transport services. It offers real-time tracking, digital health records, and intelligent automation — all in one platform.

## 🚀 Features

- 🐶 **User Role Management** – Role-based dashboards for Pet Owners, Clinics, and Pet Boarding Houses.
- 📍 **Real-Time GPS Tracking** – Monitor pickup and drop services using OpenStreetMap and OpenCage geocoding.
- 📸 **Live Photo & Video Check-ins** – Receive real-time updates during pet boarding.
- 🧠 **Context-Aware AI Chatbot** – Gemini 2.0-based chatbot to help with service selection and pet care guidance.
- 💬 **Live Chat System** – Chat with service providers in real-time.
- 📅 **Appointment & Booking System** – Schedule vet appointments, boarding, and grooming with ease.
- 🛡️ **Secure Authentication** – JWT-based login and **SHA-256 encryption** for sensitive data.
- 📧 **Email Notifications** – Automated alerts for bookings, transport status, and emergencies.
- 📂 **Digital Health Records** – Maintain vaccination history, prescriptions, allergies, and more.
- 💰 **Service Packages & Subscriptions** – Flexible packages and premium options for users and providers.

## 🛠️ Tech Stack

### Frontend
- React.js
- Tailwind CSS
- React Router DOM
- Framer Motion
- React Leaflet / OpenStreetMap
- Axios

### Backend
- Node.js
- Express.js
- MongoDB (with Mongoose)
- JWT for auth, SHA-256 for data hashing
- Socket.io for real-time features

### APIs & Services
- OpenCage Geocoding
- OpenStreetMap (location tracking)
- Brevo SMTP (email)
- Gemini 2.0 Flash (AI chatbot)

## 📦 Installation

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/petbuddy.git
cd petbuddy
