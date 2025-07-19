# 🧠 ThinkBoard - MERN Stack Project

**ThinkBoard** is a full-stack note-taking web application built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js). It allows users to create, read, update, and delete notes efficiently through a clean and responsive interface.

---

## 🔗 Live Demo

🌐 Hosted on **Render**: [Click Here to Visit the App](https://thinkboard-mern-stack-10tz.onrender.com)

---

## ✨ Features

- 📝 Create and manage personal notes
- ✏️ Edit and delete existing notes
- 📄 View notes in an organized card layout
- 🔍 Search/filter notes (if implemented)
- 🧭 Sidebar and Header UI components
- 📱 Fully responsive across devices
- 💬 Clear date formatting using utility functions
- 🔌 Connected with MongoDB Atlas database

---

## ⚙️ Tech Stack

- **MongoDB** – NoSQL database
- **Express.js** – Backend framework
- **React.js** – Frontend library
- **Node.js** – JavaScript runtime
- **Mongoose** – MongoDB object modeling
- **Axios** – Promise-based HTTP client
- **React Router DOM** – Client-side routing
- **Render** – Deployment platform

---

## 📁 Project Structure

ThinkBoard-Mern-Stack-/
├── backend/
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ └── server.js
├── frontend/
│ ├── public/
│ └── src/
│ ├── components/
│ ├── pages/
│ ├── App.jsx
│ └── index.js
├── .gitignore
├── README.md
└── package.json


---

### 📥 Clone the Repository

```bash
git clone https://github.com/Snehashis87/ThinkBoard-Mern-Stack-.git
cd ThinkBoard-Mern-Stack-
```

### ⚙️ Setup Backend

```bash
cd backend
npm install
```

Create a `.env` file inside `backend/`:

```env
MONGO_URI=your_mongodb_connection_uri
PORT=5001
```

Start the backend server:

```bash
npm start
```

### 💻 Setup Frontend

```bash
cd ../frontend
npm install
npm run dev
```

Your app should now be running locally at `http://localhost:5173` and connected to the backend at `http://localhost:5001`.

---

## 🌍 Deployment

This app is deployed using **Render**:

- **Frontend** (React) and **Backend** (Express + MongoDB) are hosted as separate services.
- MongoDB is hosted on **MongoDB Atlas**.

---

## 👨‍💻 Author

Developed by **Snehashis Mandal**

- GitHub: [@Snehashis87](https://github.com/Snehashis87)
- LinkedIn: [linkedin.com/in/snehashis-mandal](https://www.linkedin.com/in/snehashis-mandal-796640284)








