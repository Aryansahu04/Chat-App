# 💬 Real-Time Chat Application

A full-stack real-time chat application built using the MERN stack (MongoDB, Express, React, Node.js) with Socket.IO for instant messaging. The application supports secure authentication, real-time communication, online/offline user status, and persistent chat history.

---

## 🚀 Features

- 🔐 User Authentication (Signup / Login / Logout)
- 💬 Real-Time Messaging using Socket.IO
- 🟢 Online / Offline User Status
- 📜 Persistent Chat History (MongoDB)
- 📱 Fully Responsive UI
- ⚡ Fast frontend powered by Vite
- 🎨 Styled using Tailwind CSS + DaisyUI

---

## 🛠️ Tech Stack

### Frontend
- React (with Vite)
- Tailwind CSS
- DaisyUI
- React Icons
- Axios

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- Socket.IO
- JWT Authentication
- bcrypt.js

---

## 📂 Project Structure

```
chat-app/
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── ...
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Aryansahu04/Chat-App.git
```

### 2️⃣ Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file inside the backend folder:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Run backend:

```bash
npm start
```

---

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

## 🔑 Environment Variables

| Variable      | Description |
|--------------|------------|
| MONGO_URI     | MongoDB connection string |
| JWT_SECRET    | Secret key for JWT authentication |
| PORT          | Backend server port |

---


## 📌 Future Improvements

- 🌙 Dark/Light Theme Toggle
- 📎 Media/File Sharing
- 🧑‍🤝‍🧑 Group Chat Support
- 🔔 Message Notifications

---
