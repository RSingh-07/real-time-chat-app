# real-time-chat-app
A real-time chat application built with the MERN stack and Socket.IO, based on a tutorial by GreatStack. Includes real-time messaging, authentication, and MongoDB backend. Extended with custom features like online user status and UI improvements.
<br>
# Real-Time Chat Application

A full-stack real-time chat application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) and Socket.IO. This app allows users to sign up, log in, and chat with each other in real-time without refreshing the page. Messages are stored in MongoDB, and the chat interface updates instantly using WebSocket communication.

## 📺 Based On
This project is built by following the [Real-Time Chat App Tutorial](https://www.youtube.com/watch?v=tEmt1Znux58) by [GreatStack](https://www.youtube.com/@GreatStack) on YouTube. It has been customized and extended for learning and practice purposes.

## 🚀 Features
- User Registration and Login (with JWT authentication)
- Real-time messaging using Socket.IO
- Chat conversations and message history
- Online/offline user status
- Tailwind CSS-based responsive UI
- MongoDB integration for persistent storage
- Clean project structure (client/server)
- Ready for deployment (Render + Vercel)

## 🛠️ Tech Stack
**Frontend:**
- React.js
- Tailwind CSS
- Axios
- React Router

**Backend:**
- Node.js
- Express.js
- MongoDB (Mongoose)
- Socket.IO
- JWT (JSON Web Tokens)


## 🔐 Authentication
JWT-based authentication is implemented to secure user access. Login and registration endpoints return tokens, which are used to access protected routes and establish socket connections.

## ⚙️ Environment Variables
Create `.env` files in both `client` and `server` directories.

**server/.env**

---

## 🛠️ Install & Run Locally

```bash
# Backend
cd server
npm install
npm run dev

# Frontend
cd client
npm install
npm run dev

