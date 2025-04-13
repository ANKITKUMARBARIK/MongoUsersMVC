
# 🚀 MongoUsersMVC

A clean and scalable RESTful API built using **Node.js**, **Express**, and **MongoDB**, following the **MVC (Model-View-Controller)** architecture.

---

## 📁 Project Structure

```
MongoUsersMVC/
│
├── models/         # Mongoose schemas and models 📦
│   └── UserModel.js
│
├── controllers/    # Business logic 🎯
│   └── userController.js
│
├── routes/         # Express routes 🌐
│   └── userRoutes.js
│
├── config/         # MongoDB connection config ⚙️
│   └── db.js
│
├── .env            # Environment variables 🔐
├── app.js          # Main app file 🚂
└── package.json    # Project metadata and scripts 📜
```

---

## ✅ Features

- 📦 Full CRUD operations (Create, Read, Update, Delete)
- 🏗️ Organized with MVC architecture
- 🔐 Mongoose validations
- ⚙️ RESTful API design
- 🌍 MongoDB database (local or Atlas)
- 💡 Error handling

---

## 🛠️ Installation

```bash
git clone https://github.com/ANKITKUMARBARIK/MongoUsersMVC.git
cd MongoUsersMVC
npm install
```
Create a `.env` file:
```
MONGO_URI=your_mongodb_connection_string
PORT=3000
```

---

## 🚀 Usage

Start the server:

```bash
npm start
```

API endpoints:
- `GET /api/users` – Get all users
- `POST /api/users` – Create a new user
- `GET /api/users/:id` – Get user by ID
- `PATCH /api/users/:id` – Update user
- `DELETE /api/users/:id` – Delete user

---

## 📌 Tech Stack

- **Node.js** 🚀
- **Express.js** 🔧
- **MongoDB + Mongoose** 🧠
- **MVC Architecture** 🏗️

---

## 🙌 Author

**Ankit Kumar Barik** – Full Stack Developer 🧑‍💻  
[GitHub](https://github.com/ANKITKUMARBARIK)

---

## 📜 License

This project is licensed under the GNU License.
