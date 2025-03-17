# Node.js Task CRUD API

This is a simple **Node.js CRUD API** built using **Express.js** and **MongoDB** for managing tasks.

## 📌 Features
- Create, Read, Update, and Delete (CRUD) tasks
- Uses **MongoDB** with **Mongoose ORM**
- API testing with **Postman**
- Version control with **Git & GitHub**

---

## 📂 Project Structure
```
project-folder/
├── server.js           # Main server file
├── models/
│   ├── task.js        # Task schema
├── routes/
│   ├── taskRoutes.js  # Task API routes
├── .gitignore          # Ignoring unnecessary files
├── .env                # Environment variables
├── package.json        # Project dependencies
└── node_modules/       # Installed packages
```

---

## 🚀 Installation & Setup
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-username/nodejs-task-crud.git
cd nodejs-task-crud
```

### 2️⃣ Install Dependencies
```sh
npm install
```

### 3️⃣ Configure Environment Variables
Create a `.env` file and add:
```sh
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

### 4️⃣ Start the Server
```sh
node server.js
```
Server will run on **`http://localhost:5000`** 🚀

---

## 📌 API Endpoints
### 🔹 Create a Task (POST)
```sh
POST /tasks
```
**Body:**
```json
{
  "title": "Complete Project",
  "description": "Finish Node.js API",
  "status": "pending"
}
```

### 🔹 Get All Tasks (GET)
```sh
GET /tasks
```

### 🔹 Get Single Task (GET by ID)
```sh
GET /tasks/:id
```

### 🔹 Update a Task (PUT)
```sh
PUT /tasks/:id
```
**Body:**
```json
{
  "status": "completed"
}
```

### 🔹 Delete a Task (DELETE)
```sh
DELETE /tasks/:id
```

---

## 🔗 GitHub Setup
```sh
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/your-username/nodejs-task-crud.git
git push -u origin main
```

---

## 📌 Postman Testing
1. Open **Postman**
2. Use **`http://localhost:5000/tasks`**
3. Test CRUD operations

---

## 🚀 Deploying to a Cloud Platform (Optional)
You can deploy your API using **Render**, **Heroku**, or **Vercel**.

---

### 👨‍💻 Author
**Sharulatha**

🔗 GitHub: [Sharulatha2607](https://github.com/Sharulatha2607)

🎉 Happy Coding! 🚀

