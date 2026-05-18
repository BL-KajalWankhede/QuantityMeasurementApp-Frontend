# 📏 Quantity Measurement Application (QMA) - Frontend Client

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![React](https://img.shields.io/badge/React-18-blue.svg)
![Vite](https://img.shields.io/badge/Build-Vite-purple.svg)

**Quantity Measurement App (QMA)** is a high-end, industrial-grade application designed for precision unit conversions and comparisons. This repository contains the **Premium React Frontend**, which acts as the presentation layer for the QMA microservices ecosystem.

---

## 🚀 Live Environment
*   **Production Frontend:** [https://quantitymeasurementapp-p0gz.onrender.com](https://quantitymeasurementapp-p0gz.onrender.com)
*   **Backend API Gateway:** Connects to `https://quantitymeasurementapp-api-5be3.onrender.com`

---

## 🏗️ The Frontend Workspace

Unlike traditional monoliths, this frontend is entirely decoupled from the backend. It focuses purely on delivering a fast, responsive user experience:
1.  **Professional Split-Screen Auth:** A clean, high-end branding sidebar and centered login/signup forms.
2.  **Advanced Dashboard:** A unified workspace for real-time conversions (Length, Weight, Volume, Temperature) and history tracking.

---

## ✨ Key Features

*   **⚡ Precision UI:** Highly accurate input forms for complex unit conversion mathematics.
*   **📊 History Tracking:** Every conversion is automatically displayed in your profile history.
*   **🛡️ Multi-Method Auth:** Secure login via traditional Email/Password or the ultra-fast **Continue with Google** (OAuth2).
*   **🎨 Premium UI/UX:** A professional "Indigo & Teal" design language with custom SCSS styling.

---

## 🔐 Security & Authentication Handshake

This frontend securely communicates with the backend microservices:
1.  **Identity Handshake:** When using Google Login, the frontend receives a signed JWT from the Gateway.
2.  **Cross-Origin Persistence:** Tokens are persisted to `localStorage` securely.
3.  **Gateway Validation:** The frontend attaches the JWT to the `Authorization` header for all requests (like saving history).

---

## ☁️ Production Architecture (Render)

This React application is optimized for cloud deployment using **Render** as a static site.

### **Required Environment Variables**
To run this in production, ensure the following variable is set in your hosting dashboard:
*   `VITE_API_BASE_URL`: The live URL of your API Gateway (e.g., `https://quantitymeasurementapp-api-5be3.onrender.com`)

---

## 🛠️ Technology Stack

### **Frontend (The Experience)**
*   **React 18 / Vite** (Lightning-fast builds).
*   **State Management:** React Context API & Hooks.
*   **Styling:** Custom SCSS with a professional design system (Inter & Space Grotesk fonts).
*   **Icons:** Lucide-React.
*   **Network:** Axios (for connecting to the Java Gateway).

---

## 🚦 Getting Started (Production Deployment)

### **1. Building the Client**
To create an optimized production build of the React application:
```powershell
# Install dependencies
npm install

# Compile the application for production
npm run build
```
The compiled files will be generated in the `/dist` directory, ready to be served by any static hosting provider.

### **2. Backend Connection Setup**
Ensure your production hosting environment (e.g., Render, Vercel, Netlify) has the following Environment Variable configured to point to your live API Gateway:
```properties
VITE_API_BASE_URL=https://quantitymeasurementapp-api-5be3.onrender.com
```

---

## 👤 Author
**Kajal Wankhede**
***GitHub:** [@BL-KajalWankhede](https://github.com/BL-KajalWankhede)

---
*Precision in every unit, excellence in every calculation.*
