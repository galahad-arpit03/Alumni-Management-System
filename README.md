# Alumni Management System

The **Alumni Management System** is a web-based application built with PHP and MySQL to help institutions maintain a database of their alumni, enabling better communication and record-keeping.

---

## 📦 How to Run the Project

Follow the steps below to set up and run the project on your local machine.

### 🔽 1. Download the Source Code
- Download the zipped source code from the provided location.
- Extract the contents to a folder on your system.

### 🌐 2. Set Up a Local Web Server
You can use any local server environment that supports PHP and MySQL. The most common one is **XAMPP**.

> 💡 Download XAMPP from [https://www.apachefriends.org/index.html](https://www.apachefriends.org/index.html)

### 🛠️ 3. Set Up the Database
1. Open **phpMyAdmin** (`http://localhost/phpmyadmin`) via your browser.
2. Create a new database with the name:
3. Import the SQL file:
- Locate the `alumni_db.sql` file inside the `database` folder of the source code.
- Use phpMyAdmin's **Import** feature to import this SQL file into the newly created `alumni_db` database.

### 📁 4. Move the Project to Web Server Directory
- Copy the extracted folder (e.g., `alumni-management-system`) to your web server's root directory.

Example for XAMPP:
Final path should look like:C:\xampp\htdocs\


### 🌍 5. Run the Project in a Browser
- Start your **Apache** and **MySQL** services from XAMPP Control Panel.
- Open a browser and visit:

- **Alumni Side:**
  ```
  http://localhost/alumni-management-system
  ```
- **Admin Side:**
  ```
  http://localhost/alumni-management-system/admin
  ```

---

## 🔐 Admin Login Credentials

| Username | Password   |
|----------|------------|
| admin    | admin123   |

> ⚠️ It is recommended to change the default credentials after the first login for security purposes.

---

## 📂 Project Structure


---

## 🧰 Requirements

- PHP >= 7.x
- MySQL or MariaDB
- Web Server (e.g., Apache)
- Web Browser (Chrome, Firefox, etc.)

---

## 🚀 Features

- Alumni registration and profile management
- Admin dashboard for managing alumni records
- Event updates and announcements
- Search and filter alumni
- Secure login for both alumni and admin

---

## 📌 Notes

- Ensure your PHP environment has the required extensions (like `mysqli`) enabled.
- The app is intended to be run in a local development environment.

