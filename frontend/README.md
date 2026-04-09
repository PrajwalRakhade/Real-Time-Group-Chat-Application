# 💬 Real-Time Group Chat Application

A scalable and responsive real-time group chat application that enables multiple users to communicate instantly. Built using modern web technologies and WebSockets, it ensures seamless and efficient message delivery across chat rooms.

---

## 🚀 Features

* ⚡ **Real-Time Messaging**

  * Instant communication using WebSockets with Socket.io

* 👥 **Group Chat Rooms**

  * Users can join specific rooms and chat with others in real time

* 🕒 **Message Timestamps**

  * Displays when each message was sent

* 🧑‍💻 **Sender Identification**

  * Clearly shows who sent each message

* 📱 **Responsive UI**

  * Optimized for desktop and mobile devices using React.js

---

## 🛠️ Tech Stack

### Frontend

* React.js
* HTML5
* CSS3

### Backend

* Node.js
* Express.js

### Real-Time Communication

* Socket.io

---

## 📂 Project Structure

```
Real-Time-Chat/
│── client/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── styles/
│
│── server/
│   ├── routes/
│   ├── socket/
│   └── controllers/
│
│── README.md
│── package.json
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/real-time-chat.git
cd real-time-chat
```

### 2. Install Dependencies

#### Install Server Dependencies

```bash
cd server
npm install
```

#### Install Client Dependencies

```bash
cd ../client
npm install
```

### 3. Run the Application

#### Start Backend Server

```bash
cd server
npm start
```

#### Start Frontend

```bash
cd client
npm start
```

---

## 🔍 How It Works

1. User joins a chat room
2. Socket.io establishes a WebSocket connection
3. Messages are emitted to the server
4. Server broadcasts messages to users in the same room
5. Messages appear instantly with sender name and timestamp

---

## 🎯 Future Improvements

* 🔐 User authentication (login/signup)
* 🟢 Online/offline user status
* 📎 File and image sharing
* 🔔 Notifications for new messages
* 🌐 Multi-room management dashboard







⭐ If you found this project useful, consider giving it a star!
