# 💬 Real-Time Chat Application

A full-stack real-time chat application built with **Node.js**, **Express**, **Socket.io**, and **React**. Users can send and receive messages instantly without page refresh.

---

## 🚀 Live Demo

🔗 **[https://real-time-frontend-app.onrender.com](https://real-time-frontend-app.onrender.com)**


---

## 🛠️ Tech Stack

### Frontend
- React.js
- Redux Toolkit
- Tailwind CSS
- Socket.io-client
- Deployed on **Render**

### Backend
- Node.js
- Express.js
- Socket.io
- MongoDB (Mongoose)
- JWT Authentication
- Deployed on **Render**

---

## ✨ Features

- 🔴 Real-time messaging using WebSockets (Socket.io)
- 👥 See all online users in the sidebar
- 🔐 User Authentication (Signup / Login) with JWT
- 💬 One-to-one private messaging
- 📱 Fully responsive UI
- ⚡ Instant message delivery with no page refresh
- 🗃️ Messages stored in MongoDB

---

## 📁 Project Structure

```
Real-Time-Chat-App/
├── backend/
│   ├── controllers/       # Route controllers
│   ├── models/            # MongoDB models
│   ├── routes/
│   │   ├── messageRoute.js
│   │   └── userRoute.js
│   ├── socket/
│   │   └── socket.js      # Socket.io logic
│   ├── package.json
│   └── vercel.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/    # React components
│   │   ├── hooks/         # Custom hooks
│   │   ├── redux/         # Redux store & slices
│   │   ├── App.js
│   │   └── index.js
│   ├── tailwind.config.js
│   └── package.json
│
└── README.md
```

---

## ⚙️ Getting Started Locally

### Prerequisites
- Node.js (v14 or above)
- npm
- MongoDB

### Installation

**1. Clone the repository**
```bash
git clone https://github.com/007Ayushi/Real-Time-Chat-App.git
cd Real-Time-Chat-App
```

**2. Setup Backend**
```bash
cd backend
npm install
```

Create a `.env` file in backend folder:
```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

```bash
npm start
```

**3. Setup Frontend**
```bash
cd ../frontend
npm install
npm start
```

**4. Open in browser**
```
http://localhost:3000
```

---

## 🔌 How It Works

1. User signs up / logs in — JWT token is generated
2. Frontend connects to backend via **Socket.io**
3. Online users are shown in the sidebar in real-time
4. Messages sent by a user are instantly delivered to the receiver
5. All messages are stored in **MongoDB**

---

## 🌱 Future Improvements

- [ ] Group chat support
- [ ] Message read receipts
- [ ] Typing indicators
- [ ] File / image sharing
- [ ] Push notifications

---

## 👩‍💻 Author

**Ayushi Gupta**
- GitHub: [@007Ayushi](https://github.com/007Ayushi)

---
