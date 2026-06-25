# Product-Catelog

 # 🛍️ Product Catalog Management System

A full-stack Product Catalog Management System built using **Node.js, Express.js, MongoDB**, and a simple **HTML, CSS UI**. This application allows users to add, view, and manage products efficiently.

---

## 🚀 Features

* ➕ Add new products
* 📦 View all products
* 🗂️ Categorize products
* 💾 Data stored in MongoDB (persistent storage)
* 🎨 Simple and responsive UI using HTML & CSS
* 🔗 RESTful API integration

---

## 🛠️ Tech Stack

### 🔹 Backend

* Node.js
* Express.js
* MongoDB (Atlas)
* Mongoose

### 🔹 Frontend

* HTML
* CSS
* JavaScript (Fetch API)

---

## 📁 Project Structure

```
product-catalog/
│── config/
│   └── db.js
│── models/
│   └── Product.js
│── routes/
│   └── productRoutes.js
│── public/
│   └── index.html
│   └── style.css
│── .env
│── server.js
│── package.json
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/product-catalog.git
cd product-catalog
```

### 2️⃣ Install dependencies

```
npm install
```

### 3️⃣ Setup environment variables

Create a `.env` file and add:

```
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

---

### 4️⃣ Run the server

```
npm run dev
```

Server will run on:

```
http://localhost:5000
```

---

## 🔌 API Endpoints

| Method | Endpoint      | Description      |
| ------ | ------------- | ---------------- |
| GET    | /api/products | Get all products |
| POST   | /api/products | Add new product  |

---

## 🧪 Testing

You can test APIs using:

* Thunder Client (VS Code)
* Postman

---

## 🎯 Future Enhancements

* ✏️ Update product (PUT)
* ❌ Delete product (DELETE)
* 🔐 User authentication
* ⚛️ React frontend integration
* 📊 Admin dashboard

---

## 🙌 Author

**SIMRAN JAISWAL**
B.Tech CSE (Data Science) Student

---

## ⭐ Acknowledgment

This project was built as part of learning backend development and full-stack integration.

---

