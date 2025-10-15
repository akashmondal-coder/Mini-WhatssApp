# 💬 Mini WhatsApp Chat App

This is a simple **CRUD-based chat web application** built using **Node.js, Express, MongoDB, and EJS**.  
It allows users to create, view, edit, and delete chat messages — simulating a mini version of WhatsApp.

---

## 🚀 Technologies Used
- **Node.js** – Backend runtime environment  
- **Express.js** – Server framework for Node  
- **MongoDB + Mongoose** – Database and ODM  
- **EJS** – Templating engine for rendering dynamic views  
- **HTML, CSS** – Frontend design and layout  
- **Method-Override** – For handling PUT and DELETE requests  

---

## ⚙️ Features
✅ Create, Read, Update, and Delete chats (CRUD)  
✅ Dynamic EJS templates for rendering chat messages  
✅ Timestamp display for each message  
✅ Responsive and clean UI using simple CSS  
✅ MongoDB integration with Mongoose  

---

## 💡 How It Works
1. **Homepage (/chats)** displays all saved chats.  
2. **/chats/new** lets you create a new chat message.  
3. **/chats/:id/edit** allows editing a message.  
4. Chats can also be **deleted** using the delete button.  

---

## 🛠️ How to Run Locally

### 1️⃣ Clone the repository
```bash
git clone https://github.com/akashmondal-coder/Mini-Whatsapp-Chat-App.git

###2️⃣ Install dependencies
npm install

###3️⃣ Start MongoDB server
Make sure MongoDB is running locally (default: mongodb://127.0.0.1:27017/)

###4️⃣ Initialize sample data
node init.js

###5️⃣ Run the application
node index.js
Now open your browser and visit 👉 http://localhost:8080/chats

---

##📸 Screenshots 
<img width="1514" height="864" alt="Screenshot 2025-10-15 125258" src="https://github.com/user-attachments/assets/0c6430f0-de98-457e-8453-31b6592cd986" />

---

##👨‍💻 Author
**Akash Mondal**  
🔗 [LinkedIn](https://www.linkedin.com/in/akashmondal956)  
💻 [GitHub](https://github.com/akashmondal-coder)

---

## 📁 Project Status
🟢 Fully Functional
This project performs complete CRUD operations using Node.js and MongoDB.

---

##🧠 Future Enhancements
Add user authentication
Add real-time messaging using Socket.io
Improve UI with Bootstrap or Tailwind CSS

---
