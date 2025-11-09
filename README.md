# 🧪 REST API Experiment 15 — File Upload using Multer & Request Throttling (Rate Limiting)

## 📘 Objective
To implement **file upload** functionality using **Multer** and **rate limiting** using **express-rate-limit** to prevent abuse of API endpoints in a Node.js + Express + MongoDB REST API.

---

## 🧠 Learning Outcomes
- Learn how to handle file uploads in REST APIs using Multer.
- Understand middleware integration for file handling.
- Implement rate limiting to prevent excessive API requests.
- Enhance API security and performance.

---

## ⚙️ Tools & Technologies
- **Node.js**
- **Express.js**
- **Multer**
- **Express-Rate-Limit**
- **MongoDB / Mongoose**
- **dotenv**
- **Postman**
- **VS Code**

---

## 🏗️ Folder Structure
rest-exp15-file-upload-rate-limit/
│
├── server.js
├── uploads/
├── routes/
│ └── uploadRoutes.js
├── middleware/
│ ├── uploadMiddleware.js
│ └── rateLimiter.js
├── .env
├── .env.example
├── package.json
└── README.md

---

## 🚀 Setup Instructions
```bash
# Step 1: Initialize Node project
npm init -y

# Step 2: Install dependencies
npm install express multer express-rate-limit dotenv mongoose

# Step 3: Create required folders
mkdir uploads routes middleware
touch server.js routes/uploadRoutes.js middleware/uploadMiddleware.js middleware/rateLimiter.js .env .env.example

# Step 4: Run the server
node server.js
```
## output

<img width="1075" height="670" alt="rest_15 (1)" src="https://github.com/user-attachments/assets/483149c2-3a64-4428-a626-bca89ae63fe3" />





