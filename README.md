# 📚 Library Management System

A web-based Library Management System built using **PHP**, **MySQL**, **HTML/CSS**, and **Bootstrap** to manage and automate the core functionalities of a library such as book issuance, user management, book tracking, and admin services.

---

## 🚀 Features

- 🔐 **Login Authentication**
  - Separate login for Admin and Users
- 📖 **Book Management**
  - Add, update, delete books
  - View book catalog with images
- 👩‍🎓 **User Management**
  - Register new users (students/staff)
  - Delete or manage user accounts
- 📬 **Book Requests**
  - Users can request books
  - Admin approval required for issue
- 📤 **Book Issuance & Return**
  - Track issued books and return dates
- 📊 **Admin Dashboard**
  - Access statistics and manage operations from a central dashboard

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| PHP        | Backend scripting |
| MySQL      | Database management |
| HTML/CSS   | Frontend structure and design |
| Bootstrap  | Responsive styling |
| JavaScript & jQuery | Interactive elements |
| XAMPP/WAMP | Recommended local server for deployment |

---

## 📁 Project Structure

```
Project Root
├── Images/                         # Book cover/category images
│   ├── basic-civil-engineering-pdf.jpg
│   ├── CSE.jpg
│   ├── EC.jpg
│   └── ...
│
├── library_Project/                 # Core application logic
│   ├── index.php                    # Login page
│   ├── db.php                       # Database connection setup
│   ├── data_class.php               # Main class with DB functions
│   ├── admin_service_dashboard.php  # Admin panel
│   ├── addbookserver_page.php       # Book addition backend
│   ├── issuebook_server.php         # Book issue handling
│   ├── deleteuser.php
│   ├── approvebookrequest.php
│   └── ... other PHP modules
│
└── README.md                      # Project documentation
```


---

## 🧑‍💻 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/library-management-system.git
```
### 2. Setup Database

1. Open **phpMyAdmin** (via **XAMPP** or **WAMP**).
2. Create a new database, for example:
   ```
   library_db
   ```

3. Import the SQL file if provided,  
or manually create the necessary tables by referring to logic inside `data_class.php`.


### 3. Configure Database Connection

Edit the `db.php` file to match your local MySQL setup:

```php
$host = "localhost";
$user = "root";
$password = "";
$dbname = "library_db";
```
### 4. Run the App

1. Start **Apache** and **MySQL** using **XAMPP/WAMP**.
2. In your browser, go to:
   ```bash
   http://localhost/library_Project/index.php
   ```
---

## 🙋‍♀️ Author

**Khanak Agrawal**  
🔗 [LinkedIn](https://www.linkedin.com/in/khanak-agrawal-361277210/)  
💻 Passionate about building smart systems with AI & Web Tech.

---

## 📄 License

This project is licensed under the **Apache License 2.0**.  
See the [LICENSE](https://www.apache.org/licenses/LICENSE-2.0) file for more details.

