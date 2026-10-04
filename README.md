# 💬 Chatly – Real-Time Chat Application

A full-stack real-time chat application built with the MERN stack,
Socket.IO, and Cloudinary.

## 🚀 Live Demo
[Chatly](https://realtime-chat-app-frontend-h67t.onrender.com)

## ✨ Features

- User registration and login
- Secure authentication using JWT and HTTP-only cookies
- One-to-one real-time messaging
- Online/offline user status
- Search users by name or username
- Send text messages
- Send images
- Cloudinary image storage
- Persistent conversations and message history
- Edit user profile
- Responsive chat interface
- Emoji picker
- Logout functionality

## 🛠️ Tech Stack

### Frontend
- React
- Vite
- Redux Toolkit
- React Router
- Axios
- Tailwind CSS
- Socket.IO Client
- React Icons
- Emoji Picker

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- Socket.IO
- JWT
- bcryptjs
- Multer
- Cloudinary
- Cookie Parser
- CORS
- dotenv

## 🏗️ Architecture

React + Vite
      ↓
Axios / Socket.IO
      ↓
Node.js + Express
      ↓
MongoDB Atlas

Image Upload → Multer → Cloudinary

Real-time Events → Socket.IO

## 📁 Project Structure

```text
realtime-chat-app/
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   ├── socket/
│   ├── index.js
│   ├── package.json
│   └── ...
│
├── .gitignore
└── README.md
```

## ⚙️ Environment Variables

### Backend

PORT=
MONGODB_URL=
JWT_SECRET=
CLOUD_NAME=
API_KEY=
API_SECRET=

## 💻 Run Locally

### Backend

cd backend
npm install
npm run dev

### Frontend

cd frontend
npm install
npm run dev

## 🔐 Authentication

JWT tokens are issued during signup/login and stored using
HTTP-only cookies.

## ⚡ Real-Time Communication

Socket.IO is used for:
- Online user tracking
- Real-time message delivery
- Connection/disconnection handling

## ☁️ Deployment

Frontend: Render/Vercel
Backend: Render
Database: MongoDB Atlas
Media Storage: Cloudinary

## 📸 Screenshots

<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/59faabef-d6bc-4bd1-b747-2a486b3a8485" />

<img width="1280" height="800" alt="image" src="https://github.com/user-attachments/assets/989d94d5-a4fd-4151-92f3-dd825ec993c7" />

<img width="1278" height="754" alt="image" src="https://github.com/user-attachments/assets/cde9e594-f4d7-4072-b760-cbb5c4bb1a31" />

<img width="1279" height="755" alt="image" src="https://github.com/user-attachments/assets/6d01c1a5-195e-4d49-aa22-be0881bc9242" />

## 🔮 Future Improvements

- Group chats
- Typing indicators
- Read receipts
- Message reactions
- Message deletion/editing
- Voice/video calls
- Notifications
