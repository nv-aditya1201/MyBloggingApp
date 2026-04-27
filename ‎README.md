# BloggingApp
A full-stack blogging platform that enables users to create, share, and interact with content in real time.

## 🚀 Features
✍️ Create, edit, and delete blog posts
❤️ Like and 💬 comment on posts
🔐 User authentication & authorization
🔔 Real-time updates using WebSockets
📱 Responsive UI for seamless experience
🧑‍🤝‍🧑 User interaction tracking and engagement

## 🛠️ Tech Stack

### Frontend
React.js
JavaScript (ES6+)
HTML5, CSS3

### Backend
Node.js
Express.js

### Database
MongoDB

### Real-Time
Socket.io

### Other Tools
JWT (Authentication)
bcrypt (Password hashing)

## 📂 Project Structure
MyBloggingApp/
│
├── client/        # React frontend
├── server/        # Node.js backend
├── models/        # Database schemas
├── routes/        # API routes
├── controllers/   # Business logic
└── config/        # DB & environment setup

## ⚙️ Installation & Setup
### 1️⃣ Clone the repository
```bash
git clone https://github.com/shreya-1634/MyBloggingApp.git
cd MyBloggingApp
```
### 2️⃣ Install dependencies
```bash
# For backend
cd server
npm install

# For frontend
cd ../client
npm install
```
### 3️⃣ Setup environment variables
Create a .env file in the server folder:
```Code snippet
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```
### 4️⃣ Run the application
```bash
# Start backend
cd server
npm start

# Start frontend
cd client
npm start
```

## 🌐 Live Demo
👉 https://ndblogs.onrender.com/
