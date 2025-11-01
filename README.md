# 📘 E-Learning

A web-based **E-Learning platform** that provides a simple and user-friendly interface for online education, course management, and student-faculty interaction.

---

## 🚀 Overview

This project is an **E-Learning Management System (LMS)** built using **PHP**, **MySQL**, **HTML**, **CSS**, and **JavaScript**.  
It enables admins, faculty, and students to interact through course content, assignments, and lecture uploads in a structured digital environment.

---

## 🛠️ Built With

- **PHP** — Backend development  
- **MySQL** — Database management  
- **HTML5** & **CSS3** — Frontend layout and styling  
- **JavaScript / jQuery** — Client-side interactivity  
- **Composer** — Dependency management (if used)  
- **Bootstrap** — Responsive UI framework  

---

## ✨ Features

- 👨‍🏫 **Admin Dashboard** — Manage users, courses, and content  
- 📚 **Faculty Module** — Create and upload course materials (PDFs, PPTs, etc.)  
- 👩‍🎓 **Student Portal** — Access uploaded content and submit assignments  
- 🗂️ **Course Management** — Add, edit, and delete courses easily  
- 🧠 **PPT / Lecture Viewer** — In-browser lecture slide display  
- 🔒 **User Authentication** — Login system for all roles  
- ⚙️ **Configurable Database** — Simple setup via `config.php`  
- 📁 **Uploads Directory** — Centralized file storage for content  
- 🧩 **Modular Folder Structure** — Clear separation of concerns  

---

## 📂 Project Structure

```
E-Learning/
├── admin/
├── faculty/
├── student/
├── classes/
├── css/
├── database/
├── dist/
├── inc/
├── libs/
├── plugins/
├── uploads/
├── index.php
├── config.php
├── initialize.php
├── 404.html
└── ...
```

---

## ⚙️ Getting Started

### ✅ Prerequisites

Before you begin, ensure you have the following installed:

- [XAMPP](https://www.apachefriends.org/) / WAMP / LAMP (for local server)  
- PHP ≥ 7.4  
- MySQL Database  
- Composer (optional, if dependencies used)  

---

### 📦 Installation Steps

1. **Move to your server directory**
   ```bash
   C:\xampp\htdocs\E-Learning
   ```

2. **Create a database**
   - Open **phpMyAdmin**
   - Create a new database, e.g., `e_learning_db`

3. **Configure database connection**
   - Open `config.php`
   - Set your database credentials:
     ```php
     $host = 'localhost';
     $username = 'root';
     $password = '';
     $database = 'e_learning_db';
     ```

4. **Import SQL**
   - Go to **phpMyAdmin**
   - Import the `.sql` file from the `database/` folder

5. **Run the project**
   - Open your browser and go to:
     ```
     http://localhost/E-Learning/
     ```

6. **Login**
   - Use default credentials (if provided) or register a new user.

---

## 💡 Usage

- **Admin:** Manage users, faculty, and overall content  
- **Faculty:** Upload course materials and assignments  
- **Students:** Access and download learning resources  

Example important pages:
- `portal.php` — Main student/faculty dashboard  
- `ppt-view.php` — PowerPoint viewer for lectures  

---

## 🤝 Contributing

Contributions are always welcome!

1. **Fork** the repository  
2. **Create your feature branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**

---

## 📧 Contact

**Developer:** Nabeel Ahmad  
**GitHub:** [nabeelahmad55](https://github.com/nabeelahmad55)  
**Project Link:** [E-Learning Repository](https://github.com/nabeelahmad55/E-Learning)



