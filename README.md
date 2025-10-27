# 🐔 MycoCheck Frontend

**MycoCheck** is a web-based poultry monitoring platform designed to help farmers detect and respond to symptoms of *Mycoplasma* infection in chickens.  
This repository contains the **frontend code**, built using **Vue 3**, **Pinia**, and **Vuetify**.

---

## 🚀 Features

- ✅ Real-time snapshot viewing of symptomatic chickens  
- 📊 Dashboard displaying detection accuracy and timestamps  
- 💬 Vet-to-Farmer messaging system (via **SignalR**)  
- 📱 Mobile-responsive sidebar and adaptive layout  
- 🔐 Login/logout with user-type-based access (Farmer / Vet)  
- 🔔 SMS alerts for flagged symptoms (handled via backend)  
- ✅ JWT + Google OAuth 2.0 authentication from backend  

---

## 🛠 Tech Stack

| Category     | Tools               |
|---------------|--------------------|
| **Framework** | Vue 3              |
| **UI Library** | Vuetify 3          |
| **State Mgmt** | Pinia              |
| **Realtime**   | SignalR            |
| **HTTP**       | Axios + REST API   |
| **Build Tool** | Vite               |

---

## 📁 Project Structure
src/
│
├── components/ # Reusable UI components (layout, tables, etc.)
├── pages/ # Main route views like Dashboard, Messages
├── stores/ # Pinia stores (e.g., FarmerStore)
├── plugins/axios.js # Axios instance for backend communication
├── App.vue # Root Vue component
└── main.js # App entry point
