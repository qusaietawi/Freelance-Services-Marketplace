# Freelance Services Marketplace

A university web project that simulates a **Freelance Services Marketplace** similar to platforms like Fiverr. The system supports two main roles (**Client** and **Freelancer**) and allows browsing services, managing accounts, and handling orders.

---
<p align="center">
  <a href="http://freelanceservicesmarketplace.ct.ws" target="_blank">
    <button style="
      padding: 14px 24px;
      font-size: 16px;
      font-weight: bold;
      background-color: #2563eb;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    ">
      🚀 Open Live Project
    </button>
  </a>
</p>

---

## 📌 Project Overview

This project was developed as part of a university course requirement. It demonstrates the use of **PHP**, **MySQL**, **HTML**, and **CSS** to build a role‑based web application with database integration.

---

## 🛠️ Technologies Used

* **Frontend:** HTML5, CSS3
* **Backend:** PHP (PDO)
* **Database:** MySQL
* **Hosting:** InfinityFree
* **Version Control:** Git & GitHub

---

## 📂 Project Structure

```
std1221323/
│
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── icons/
│   └── img/
│       ├── logo.png
│       ├── default-avatar.png
│       └── placeholder.png
│
├── includes/
│   ├── db.php
│   ├── session.php
│   ├── header.php
│   ├── nav.php
│   ├── footer.php
│   └── Service.php
│
├── pages/
│   └── (application pages)
│
├── index.html
└── README.md
```

---

## ⚙️ Database Configuration

The project uses **PDO** for secure database access.

Update the database connection file:

```
includes/db.php
```

Example configuration:

```php
$dbHost = 'sqlXXX.infinityfree.com';
$dbName = 'if0_XXXXXXX_marketplace';
$dbUser = 'if0_XXXXXXX';
$dbPass = 'YOUR_INFINITYFREE_PASSWORD';
```

> ⚠️ Note: `localhost` will NOT work on InfinityFree hosting.

---

## 🗄️ Database Setup

1. Create a MySQL database from the InfinityFree Control Panel.
2. Open **phpMyAdmin**.
3. Import the provided `.sql` file.
4. Ensure all tables are created successfully.

---

## ▶️ How to Run the Project

1. Upload the project files to the `htdocs` directory on InfinityFree.
2. Configure the database connection in `db.php`.
3. Open the project URL in your browser.

---

## 👥 User Roles

* **Client**: Browse services, place orders.
* **Freelancer**: Create and manage services, handle orders.

---

## 🔐 Security Features

* Session‑based authentication
* Password hashing
* Prepared statements (PDO)

---

## 🎓 Academic Purpose

This project was created **for educational purposes only** and is not intended for commercial use.

---

## 👨‍💻 Author

**Qusai Etawi**
Computer Science Student

---

## 📜 License

This project is licensed for academic and learning use only.
 
