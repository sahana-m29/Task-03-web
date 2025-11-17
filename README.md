# Task-03-web
# Frontend Tester for Books REST API

This project provides a **single–file HTML frontend** to test your Node.js + Express Books API.  
You can use this interface to perform all CRUD operations: **GET, POST, PUT, DELETE**.

---

## 🚀 How to Use

### **1. Start Your Node.js Books API**
Your Express server must run on:

```
http://localhost:3000
```

Make sure CORS is enabled in your backend if running HTML directly from your filesystem.

---

## 📁 Included Endpoints

| Method | Endpoint          | Description                  |
|--------|-------------------|------------------------------|
| GET    | /books            | Fetch all books              |
| POST   | /books            | Add a new book               |
| PUT    | /books/:id        | Update a book by its ID      |
| DELETE | /books/:id        | Delete a book by its ID      |

---

## 🖥 Frontend Features

The HTML file includes:
- Fetch all books
- Add a new book
- Update a book by ID
- Delete a book by ID
- Display JSON responses in pretty format
- Show table output for book lists

---

## 📌 Requirements

- A running Node.js Express server:
  ```bash
  npm install express cors
  node server.js
  ```

- A browser to open the HTML file.

---

## 📄 How to Run the Frontend

1. Save the provided HTML code as:  
   **frontend.html**
2. Open the file in a browser or run it with **Live Server**.
3. Use the interface to test your API.

---

## ✔ Notes
- If browser blocks requests, install CORS in Express:
  ```bash
  npm install cors
  ```
  Add this in server:
  ```js
  const cors = require("cors");
  app.use(cors());
  ```

---

## 🎯 Outcome
This HTML tool helps you understand:
- CRUD API operations
- Express routing
- JSON handling
- Frontend-to-backend communication

