# 🎓 Student Management System

## 📌 Overview
The **Student Management System** is a dynamic web application designed to efficiently manage and organize student data. Built using **PHP, MySQL, HTML, CSS, and JavaScript**, this system provides an intuitive interface for performing CRUD (Create, Read, Update, Delete) operations.

It offers a streamlined and user-friendly platform for administrators to manage student records with accuracy, accessibility, and real-time updates.

---

## 🚀 Features

- 📊 Interactive dashboard for viewing student records  
- ➕ Add new students using modal forms  
- ✏️ Edit existing student details  
- 🗑️ Delete student records securely  
- 🖼️ Upload and manage student profile images  
- ⚡ Real-time database updates  
- 📱 Fully responsive design using Bootstrap  

---

## 🏗️ Tech Stack

- **Backend:** PHP  
- **Database:** MySQL  
- **Frontend:** HTML, CSS, JavaScript  
- **UI Framework:** Bootstrap  

---

## 📂 Project Structure

/project-root
│
├── index.php # Dashboard (view, add, delete students)
├── edit.php # Edit student details
├── db.php # Database connection
├── assets/ # CSS, JS, images
└── uploads/ # Uploaded student images


---

## 📄 Pages Description

### 🔹 Index Page (`index.php`)
- Displays all student records in a table  
- Allows adding, editing, and deleting records  
- Uses modal forms for better user experience  
- Responsive UI using Bootstrap  

---

### 🔹 Edit Page (`edit.php`)
- Fetches student data using ID  
- Pre-fills form for editing  
- Updates student information in database  
- Supports image upload  

---

### 🔹 Delete Functionality
- Deletes selected student record  
- Ensures proper database handling  

---

## 🎯 Advantages

- Efficient student data management  
- Easy-to-use interface  
- Real-time updates  
- Organized and structured data handling  
- Reduces manual errors  

---

## 🔐 Security (Recommended Improvements)

- Use prepared statements (PDO/MySQLi)  
- Validate all form inputs  
- Secure file uploads  

---

## ⚙️ Installation & Setup

### 1. Clone Repository
```bash
git clone https://github.com/your-username/student-management.git

2. Open Project
cd student-management
3. Setup Database
Create a MySQL database
Import the .sql file
4. Configure Database

Edit db.php:

$conn = mysqli_connect("localhost", "root", "", "database_name");
5. Run Project
Place project in htdocs (XAMPP)
Open in browser:
http://localhost/student-management
