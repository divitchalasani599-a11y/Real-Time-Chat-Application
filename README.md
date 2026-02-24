# 🌐 Real-Time Chat Application (Web + Sockets)

A real-time multi-user chat application built using Flask and WebSockets that allows users to communicate instantly through a web interface.

---

## 📌 Project Overview

The Real-Time Chat Application is a web-based messaging system that enables multiple users to join chat rooms and exchange messages instantly.

The system uses WebSockets to maintain a persistent connection between the server and clients, ensuring low-latency, real-time communication.

This project demonstrates the implementation of real-time communication systems using Flask-SocketIO.

---

## 🎯 Objective

- To build a real-time communication system.
- To implement WebSocket-based bidirectional messaging.
- To create multi-user chat room functionality.
- To demonstrate backend and frontend integration.

---

## ✨ Features

- 💬 Real-time messaging  
- 👥 Multi-user chat support  
- 🏠 Chat room functionality  
- ⚡ Instant message broadcasting  
- 🔄 Live connection updates  
- 🌐 Web-based interface  

---

## 🛠 Technologies Used

- Python  
- Flask  
- Flask-SocketIO  
- HTML  
- CSS  
- JavaScript  
- WebSockets  

---

## ⚙ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/realtime-chat-app.git
cd realtime-chat-app
```

---

### 2️⃣ Install Dependencies

```bash
pip install flask flask-socketio eventlet
```

Or if using requirements file:

```bash
pip install -r requirements.txt
```

---

## ▶ Usage

### 1️⃣ Run the Application

```bash
python app.py
```

---

### 2️⃣ Open in Browser

```
http://127.0.0.1:5000/
```

---

## 📂 Project Structure

```
realtime-chat-app/
│
├── app.py
├── requirements.txt
├── templates/
│   ├── index.html
│   └── chat.html
├── static/
│   └── style.css
└── README.md
```

---

## 🔄 How It Works

1. User enters a username and selects a chat room.
2. The client establishes a WebSocket connection with the server.
3. Messages are sent to the Flask server.
4. The server broadcasts messages to all users in the same room.
5. Users receive messages instantly without refreshing the page.

---

## 📡 System Architecture

Client (Browser)  
⬇  
Flask Server  
⬇  
WebSocket (Socket.IO)  
⬇  
Connected Users  

---

## 🚀 Future Enhancements

- Private messaging  
- Message history storage (Database integration)  
- User authentication system  
- Emoji support  
- Online user status indicator  
- Deployment on AWS / Heroku  

---

## 👨‍💻 Developer

Divit Chalasani  

---

## 📄 License

This project is developed for educational and learning purposes.

---
