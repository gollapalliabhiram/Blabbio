# 💬 Blabbio – Realtime Chat Application

A modern, full-stack real-time messaging platform built using the **MERN** stack, **Socket.io**, **TailwindCSS**, and **DaisyUI** for sleek responsiveness and performance.

![Demo Screenshot](/frontend/public/screenshot-for-readme.png)

---

### 🚀 Key Features

- ⚙️ **Tech Stack**: MongoDB, Express.js, React.js, Node.js, TailwindCSS, DaisyUI, Zustand
- 🔐 **Authentication & Authorization**: Secure JWT-based login and route protection
- 💬 **Real-time Chat**: WebSocket-powered private and group chats using Socket.io
- 👤 **Presence Indicators**: Online user status and "typing..." indicators
- 🌐 **Global State Management**: Managed via lightweight Zustand store
- 📈 **Optimized for Scalability**: Efficient broadcasting and socket architecture
- ☁️ **Deployment**: Hosted using free-tier cloud services (e.g., Render, Vercel, etc.)

---

### 🛠️ Environment Setup (`.env`)

Create a `.env` file in the root with the following variables:

```env
MONGODB_URI=your_mongo_connection_string
PORT=5001
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

NODE_ENV=development
