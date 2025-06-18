# 💬 ChatCord - Real-Time Chat Application

ChatCord is a real-time chat application that allows multiple users to communicate instantly via web sockets. Built using **Node.js**, **Express**, and **Socket.io**, it provides live message transmission between clients in different chat rooms, using a responsive UI created with HTML, CSS, and vanilla JavaScript.

## 🚀 Features

- Real-time bi-directional communication using Socket.io
- Join specific chat rooms with unique usernames
- Dynamic message broadcasting to connected clients
- Room-based user tracking and notifications
- Simple and clean user interface
- Built-in timestamping for chat messages

## 🛠️ Technologies Used

| Frontend | Backend         | Utilities/Packages    |
|----------|------------------|------------------------|
| HTML     | Node.js          | dotenv                 |
| CSS      | Express.js       | moment.js              |
| JavaScript | Socket.io (client) | nodemon (dev only)   |
|          | Socket.io (server) | redis + redis adapter |

## 📁 Project Structure

chatcord/
│

├── public/

│ ├── css/

│ ├── js/

│ └── index.html

│

├── server.js # Main Node.js server

├── package.json # Project metadata and dependencies

├── .env # Environment variables (optional)

└── README.md # Project documentation

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/chatcord.git
   cd chatcord

2. Install dependencies:

   npm install

3. Run in development mode:

   npm run dev

4. Open your browser and go to:

   http://localhost:3000



