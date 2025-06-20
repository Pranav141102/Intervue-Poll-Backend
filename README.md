# Intervue Poll - Backend

This is the backend server for the **Intervue Polling App**, handling API routes, socket connections, and MongoDB database operations.

## 🔗 Connected To

This backend is used by the [Intervue Poll Frontend](https://github.com/Pranav141102/Intervue-Poll-Frontend) to perform all core operations.

## ⚙️ Features

- RESTful APIs for poll creation and voting
- Real-time communication with socket.io
- MongoDB-based storage using Mongoose

## 🛠️ Tech Stack

- Node.js
- Express.js
- Mongoose
- Socket.io

## 📦 Installation

# Clone the repository
git clone https://github.com/Pranav141102/Intervue-Poll-Backend.git
cd Intervue-Poll-Backend

# Install dependencies
npm install

# Start the server
node src/app.js

# Environment Variables
PORT=3000
MONGODB_URI=mongodb+srv://your-mongodb-uri

# Folder Structure
src/
├── controllers/
│   ├── login.js
│   └── poll.js
├── models/
│   ├── pollModel.js
│   └── teacher.js
└── app.js


# Author
Pranav Deshmukh
