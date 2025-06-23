
# 💬 RedisTalk

A **highly scalable and efficient real-time chat application** built using the **MERN stack**, with **Kafka** and **Redis** to ensure seamless performance under heavy loads.

---

## 🚀 Features

- ⚡ **Real-Time Messaging** – Instant message delivery using Socket.io.
- 👥 **Group Chats** – Users can create, join, and manage group conversations.
- 🔐 **User Authentication** – Secure login with JWT and OAuth SSO support.
- 😀 **Emoji Support** – Send and receive emojis in chats.
- 📱 **Responsive UI** – Optimized for mobile, tablet, and desktop screens.

---

## ⚙️ Scalability and Performance

### 🧵 Kafka – Distributed Messaging System

Kafka handles real-time message streams by decoupling producers and consumers:

- **High Throughput** – Efficient message processing for large user bases.
- **Horizontal Scalability** – Scale easily by adding more brokers/partitions.
- **Fault Tolerance** – Guaranteed delivery with replication and recovery.

### 🚀 Redis – In-Memory Caching Layer

Redis improves real-time performance and lowers database load:

- **Fast Access** – Millisecond latency for reads/writes.
- **Pub/Sub Sync** – Real-time event syncing across multiple servers.
- **Session Caching** – Store frequently accessed user/session data.

---

## 🛠️ Tech Stack

### 🔧 Backend

- Node.js + Express
- MongoDB + Mongoose
- Socket.io
- KafkaJS
- Redis

### 🎨 Frontend

- React.js
- Redux Toolkit
- Tailwind CSS
- Axios

---

## 📂 Project Structure

```
REDISTALK/
├── client/               # React frontend
│   ├── public/
│   ├── src/
│   │   ├── apis/         # API calls
│   │   ├── assets/       # Images
│   │   ├── components/   # Reusable UI + Group/Profile
│   │   ├── pages/        # Chat, Login, Register, etc.
│   │   ├── redux/        # State slices
│   │   ├── utils/        # Helper logic
│   │   ├── App.jsx
│   │   ├── index.jsx
│   │   └── store.jsx
│   └── tailwind.config.js
│
├── server/               # Express backend
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── services/         # Kafka, Mongo, Socket server
│   └── server.js
```

---

## 🧪 Getting Started

### 🔨 Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- [Redis](https://redis.io/)
- [Kafka & Zookeeper](https://kafka.apache.org/quickstart)

---

### 🖥 Setup Instructions

#### 1. Clone the Repository

```bash
git clone https://github.com/rakeshrakhi9392/scalable-chat-app.git
cd scalable-chat-app
```

#### 2. Install Dependencies

Frontend:

```bash
cd client
npm install
```

Backend:

```bash
cd server
npm install
```

#### 3. Start Services

Ensure Kafka, Zookeeper, MongoDB, and Redis are running in the background.

#### 4. Start Backend

```bash
cd server
node server.js
```

#### 5. Start Frontend

```bash
cd client
npm start
```

> Visit the app at: [http://localhost:3000](http://localhost:3000)

---

## 📦 Scripts (React - CRA)

| Command         | Description                             |
|-----------------|-----------------------------------------|
| `npm start`     | Run dev server on `localhost:3000`      |
| `npm run build` | Create production build                 |
| `npm test`      | Launch test runner                      |
| `npm run eject` | Eject CRA config (not reversible)       |

---

## 🧠 Learn More

- [React Documentation](https://reactjs.org/)
- [Create React App Docs](https://create-react-app.dev/)
- [KafkaJS Docs](https://kafka.js.org/)
- [Redis Documentation](https://redis.io/)
- [Socket.io Docs](https://socket.io/docs/)

---

## 📌 Roadmap

- ✅ Group & private chat
- ✅ Typing indicator
- ✅ Message read status
- ⏳ Media & file sharing
- ⏳ Push notifications (Web & Mobile)
- ⏳ Docker & CI/CD deployment pipeline

---
