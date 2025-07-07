# 💬 Chat App

A **real-time chat application** built with **Node.js**, **Express**, **Socket.IO**, and **MongoDB**. This app allows multiple users to join chat rooms and send messages instantly with seamless two-way communication. The frontend is developed using **HTML, CSS, and JavaScript** to provide a responsive and interactive user experience.

---

## 📌 Features

- ✅ Real-time messaging using WebSockets
- ✅ Join custom chat rooms
- ✅ User connection and disconnection notifications
- ✅ Server-side message broadcasting
- ✅ MongoDB integration for message persistence
- ✅ Clean and minimal user interface

---

## 🚀 Tech Stack

| Frontend | Backend | Database |
|----------|---------|----------|
| HTML, CSS, JavaScript | Node.js, Express, Socket.IO | MongoDB |

---

## 🖥️ Screenshots

### 🔹 Landing Page
> Replace the image path with your own screenshot  
![Screenshot](/screenshots/landing-page.png)

---

### 🔹 Join Chat Room
![Screenshot](/screenshots/join-chat-room.png)

---

### 🔹 Chat Interface
![Screenshot](/screenshots/chat-interface.png)

---

### 🔹 Real-Time Messaging
![Screenshot](/screenshots/message-in-action.gif)

---

## 🔐 Authentication (Planned Feature)

- Secure user registration and login using JWT or sessions
- Protected chat rooms
- User-specific chat history

## 🧠 Application Architecture

The app follows a **client-server model** where:

- **Client-side**: Sends/receives messages via Socket.IO and renders the UI
- **Server-side**: Manages rooms, broadcasts messages, and handles user sessions
- **Database**: Stores user data and chat history (MongoDB)

## 🧪 Testing

Manual testing was performed for:

- Multiple users joining/leaving rooms
- Message delivery and sync
- Disconnection and reconnection scenarios

> Automated testing with Mocha/Chai coming soon.

## 🚀 Deployment

To deploy the app on platforms like **Render**, **Railway**, or **Heroku**:

1. Push code to GitHub
2. Connect repo to the platform
3. Set environment variables
4. Deploy and open live link

> Make sure to allow WebSockets on your hosting provider.


## ⚙️ Installation & Setup
### Setup .env file

```js
PORT=...
MONGO_DB_URI=...
JWT_SECRET=...
NODE_ENV=...
```

### Build the app

```shell
npm run build
```

### Start the app

```shell
npm start
```
