
# 📊 Sales Tracker Management System

A **Sales Tracker Management System** built using **PHP**, **MySQL**, **HTML**, **CSS**, and **JavaScript**. This web application helps businesses efficiently **manage and monitor sales records**, including customers, products, and transactions, through a simple and user-friendly interface.

---

## ✅ Features
- **Dashboard Overview**  
  View key metrics such as total sales, customers, and products.
  
- **Customer Management**  
  Add, edit, and delete customer records.
  
- **Product Management**  
  Manage product details including name, price, and stock.
  
- **Sales Records**  
  Track sales transactions and generate reports.
  
- **User Authentication**  
  Secure login system for admin access.

---

## 🛠️ Tech Stack
- **Frontend**: HTML, CSS, JavaScript, Bootstrap  
- **Backend**: PHP  
- **Database**: MySQL  

---

## 📂 Project Structure
```
Sales-Tracker-Management/
│
├── db/               # Database file (SQL script)
├── assets/           # CSS, JS, and image files
├── includes/         # PHP files for processing
├── index.php         # Main dashboard page
└── login.php         # Admin login page
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/sales-tracker-management.git
```

### 2. Move Files to Server Directory
Place the project folder inside your **XAMPP htdocs** or **WAMP www** directory.

### 3. Create Database
- Open **phpMyAdmin**.
- Create a new database (e.g., `sales_tracker_db`).
- Import the provided **SQL file** located in the `db/` folder.

### 4. Configure Database Connection
Update `includes/db_connect.php` with your database credentials:
```php
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "sales_tracker_db";
```

### 5. Run the Application
Start **Apache** and **MySQL** in XAMPP/WAMP and access the app in your browser:
```
http://localhost/sales-tracker-management/
```

---

## 🔐 Default Admin Credentials
```
Username: admin
Password: admin123
```

---

## 📸 Screenshots
*(Add your screenshots here)*

---

## 🖋 License
This project is **open-source** and available for educational purposes.
