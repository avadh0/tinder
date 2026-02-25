
# 💖 Tinder Clone – Full Stack Dating Application

A full-stack dating application inspired by Tinder, built using **React.js, Node.js, Express, and MongoDB Atlas**. The application allows users to register, create profiles, discover matches, and chat in real time.

---

## 🚀 Features

* 🔐 User Authentication (Signup / Login)
* 👤 Profile Creation & Onboarding
* 🎯 Match Discovery based on preferences
* ❤️ Match Management System
* 💬 Real-time Chat Interface
* 🍪 Cookie-based Session Handling
* 📦 RESTful APIs with Express
* ☁️ Cloud Database using MongoDB Atlas

---

## 🛠️ Tech Stack

**Frontend**

* React.js
* CSS

**Backend**

* Node.js
* Express.js

**Database**

* MongoDB Atlas

**Libraries & Tools**

* Axios
* dotenv
* cookie-parser

---

## 📂 Project Structure

```id="sk2a0f"
tinder-clone/
│
├── client/
│   ├── public/
│   │   ├── favicon.ico
│   │   ├── index.html
│   │   ├── logo192.png
│   │   ├── logo512.png
│   │   ├── manifest.json
│   │   └── robots.txt
│   │
│   ├── src/
│   │   ├── components/
│   │   │   ├── AuthModal.js
│   │   │   ├── Chat.js
│   │   │   ├── ChatContainer.js
│   │   │   ├── ChatDisplay.js
│   │   │   ├── ChatHeader.js
│   │   │   ├── ChatInput.js
│   │   │   ├── MatchesDisplay.js
│   │   │   └── Nav.js
│   │   │
│   │   ├── images/
│   │   ├── pages/
│   │   ├── App.js
│   │   ├── index.css
│   │   └── index.js
│   │
│   ├── package.json
│   └── README.md
│
├── server/
│   ├── index.js
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash id="1px37y"
git clone https://github.com/your-username/tinder-clone.git
cd tinder-clone
```

---

### 2️⃣ Backend Setup

```bash id="ijh7x9"
cd server
npm install
```

Create a `.env` file inside the **server folder**:

```id="szizct"
MONGO_URI=your_mongodb_connection_string
PORT=8000
JWT_SECRET=your_secret_key
```

Run backend server:

```bash id="o7ay0q"
npm start
```

---

### 3️⃣ Frontend Setup

```bash id="4pdslp"
cd client
npm install
npm start
```

---

## 🧠 Core Functionalities

### 🔐 Authentication

* User registration using MongoDB `insertOne()`
* Login using `findOne()`
* Session management using cookies

### 👤 User Profiles

* Onboarding UI for collecting user data
* Profile updates using `updateOne()`

### 🎯 Matching System

* Users filtered based on preferences
* Matches stored in database

### 💬 Chat System

* Real-time messaging between matched users
* Chat history stored in MongoDB

---

## 🔧 API Endpoints

| Method | Endpoint  | Description         |
| ------ | --------- | ------------------- |
| POST   | /signup   | Register new user   |
| POST   | /login    | Login user          |
| GET    | /users    | Fetch users         |
| PUT    | /user     | Update user profile |
| GET    | /messages | Fetch chat messages |
| POST   | /message  | Send new message    |

---

## 🔒 Environment Variables

```id="9dp14y"
MONGO_URI=
JWT_SECRET=
PORT=
```

---

## 📌 Future Improvements

* 🔥 Swipe animation (Tinder-like UI)
* ⚡ Real-time communication using Socket.io
* 📸 Image upload support (Cloudinary)
* 📍 Location-based matching
* 🔔 Push notifications

---

## 👨‍💻 Author

**Ankit Yadav**
B.Tech CSE (3rd Year)
Delhi Technological University

---

## 📜 License

This project is for educational purposes only.

