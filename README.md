# 🎓 Student Registration & Data Storage

A simple full-stack web application that allows users to register student details and store them in MongoDB. The application also retrieves and displays all stored student records (similar to SQL SELECT).

---

## 📌 Project Description

This project demonstrates:

- HTML5 form design
- CSS3 styling
- Node.js backend using Express
- MongoDB database integration
- Data insertion and retrieval

Users can:
- Enter student details
- Store data in MongoDB
- View all registered students

---

## 🛠 Technologies Used

- HTML5
- CSS3
- JavaScript
- Node.js
- Express.js
- MongoDB

---

## 📁 Project Structure

student-registration
│
├── server.js
├── package.json
├── node_modules
│
└── public
├── index.html
└── style.css


---

## 🗄 Database

- Database Name: `college`
- Collection Name: `students`
- Data is stored as JSON documents in MongoDB.

Example Document:

{
"name": "deepak",
"email": "deepakkesh75@gmail.com",
"dob": "2005-11-30",
"department": "CSE",
"phone": "9042736400"
}


---

## 🚀 How to Run the Project

### 1️⃣ Install Node.js
Download and install from:
https://nodejs.org

Check installation:
node -v
npm -v


---

### 2️⃣ Install MongoDB
Download and install MongoDB Community Edition.

Make sure MongoDB service is running.

---

### 3️⃣ Clone the Repository

git clone <your-repository-link>
cd student-registration


---

### 4️⃣ Install Dependencies

npm install


---

### 5️⃣ Run the Server

node server.js


You should see:

Connected to MongoDB
Server running at http://localhost:3000


---

### 6️⃣ Open in Browser

http://localhost:3000


To view all students:

http://localhost:3000/students


---

## 📖 Features

- Student Registration Form
- Form Validation (HTML5 required fields)
- MongoDB Data Storage
- Display Student Records
- Clean and Simple UI

---

## 🧠 Learning Outcomes

- Understanding client-server architecture
- Handling HTTP requests using Express
- Connecting Node.js with MongoDB
- Implementing basic CRUD operations

---

## 📌 Future Enhancements

- Add Update and Delete functionality
- Add Bootstrap UI
- Add Login Authentication
- Convert to REST API
- Deploy to cloud (Render / Railway)

---

## 👨‍💻 Author

DEEPAK J 
B.Tech CSE Student  
Full Stack Development Practice Project
