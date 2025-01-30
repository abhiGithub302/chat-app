# AbhiChatKaro web App

Built a simple real-time chating  application  with the **MERN (MongoDB, Express, React, Node.js)** stack and **Socket.io** for real-time communication.

## 🚀 Features

- 🔐 **User Authentication** (Sign up, Login, JWT-based authentication)
- 💬 **Real-time Messaging** (Instant message updates using Socket.io)
- 👥 **One-on-One Chat** (Private conversations)
- 📝 **Message History** (Persist chat messages using MongoDB)
- 📡 **Online Status** (Show when users are online)
- 🔔 **Real-time Notifications** (Message delivery updates)
- 🖼️ **Media Sharing** (Send images and files in chat)

## 🛠️ Tech Stack

- **Frontend:** React, Vite, Tailwind CSS, React Router, Zustand (State Management)
- **Backend:** Node.js, Express.js, MongoDB, Mongoose, Socket.io,
- **Deployment:** Vercel (Frontend), Render (Backend)

## 📦 Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/chat-app.git
cd chat-app
```

### 2️⃣ Setup the Backend

```bash
cd backend
npm install
```

#### Configure Environment Variables (`.env`)

Create a `.env` file in the `backend` folder and add the following:

```env
PORT=5001
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Run the backend server:

```bash
nodemon index.js
```

### 3️⃣ Setup the Frontend

```bash
cd ../frontend
npm install
npm run dev
```

## 🚀 Usage

1. Register or log in with an account.
2. Start a one-on-one chat or join a group conversation.
3. Send messages and see real-time updates.

## 🛠 API Endpoints (Backend)

- `POST /api/auth/signup` – Register a new user
- `POST /api/auth/login` – Authenticate and log in a user
- `GET /api/users` – Fetch all users
- `POST /api/messages` – Send a message
- `GET /api/messages/:chatId` – Retrieve chat messages

## 🎯 Future Improvements

- ✅ Video & Voice Calls
- ✅ AI-powered Chatbot
- ✅ Dark Mode

## 🤝 Contributing

We welcome contributions! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m 'Added new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## 📜 License

This project is licensed under the **MIT License**.

---

### 🚀 Stay Connected

For any queries or discussions, feel free to reach out!

📧 Email: [abhishek.yadav.dev4u@gmail.com](mailto\:abhishek.yadav.dev4u@gmail.com)\
🐙 GitHub: [https://github.com/abhiGithub302](https://github.com/abhiGithub302)\
💼 LinkedIn: [https://www.linkedin.com/in/abhishekdev4u/](https://www.linkedin.com/in/abhishekdev4u/)

