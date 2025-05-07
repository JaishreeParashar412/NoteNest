# NoteNest
# 📝 NoteNest

*NoteNest* is a web-based educational platform that provides students with easy access to a structured repository of academic notes. It allows users to search, upload, and organize study materials by subject, topic, and difficulty level — promoting collaborative learning and academic success.

---

## 👥 Team Members

- *Jaishree Parashar* (Roll: 2401560003)  
- *Shalu* (Roll: 2401560032)  
- *Ayush* (Roll: 2401560031)  
- *Kanishak Choudhary* (Roll: 2401560071)

---



## 📄 Project Description

The platform features:

- ✍ User-friendly navigation  
- 🔍 Powerful search capabilities  
- 🤝 A collaborative environment where students can contribute their own notes  

---

## 🎥 Video Explanation

👉 [Watch the Video Explanation](https://drive.google.com/file/d/1x17uB4PIrBWQptr-QtbFdB8d-uzNtylT/view)

---

## 🛠 Technologies Used

| Technology        | Purpose                     |
|------------------|-----------------------------|
| HTML             | Frontend Markup             |
| CSS              | Styling                     |
| JavaScript       | Client-side Interactivity   |
| Bootstrap        | Responsive Design           |
| PHP              | Backend Development         |
| MySQL/PostgreSQL | Database Management         |
| AJAX             | Asynchronous Data Updates   |
---

## 🚀 Steps to Run/Execute the Project

### ⿡ Install XAMPP

- Download XAMPP from the official site: [https://www.apachefriends.org/index.html](https://www.apachefriends.org/index.html)  
- Install and launch the XAMPP Control Panel  
- Start *Apache* and *MySQL* modules

### ⿢ Clone the Repository

``bash
git clone <repository-url>
cd NoteNest

⿣ Set Up the Project in XAMPP
Copy the NoteNest folder into the htdocs directory
(Example: C:\xampp\htdocs\ on Windows)


⿤ Set Up the Database
Open phpMyAdmin: http://localhost/phpmyadmin

Create a new database (e.g., notenest_db)

Import the provided .sql file into the newly created database

⿥ Configure the Database Connection
$db_host = 'localhost';
$db_user = 'root';
$db_pass = '';
$db_name = 'notenest_db';
