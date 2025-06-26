# 🚮 Garbage Management System (GMS)

A web-based system for smart management of garbage collection requests across Admin, Driver, and User portals.

[![License](https://img.shields.io/github/license/yourusername/gms)](LICENSE)
[![PHP](https://img.shields.io/badge/PHP-7.4%2B-blue)]()
[![Bootstrap](https://img.shields.io/badge/UI-Bootstrap%205-blueviolet)]()
[![Status](https://img.shields.io/badge/project-live-success)](https://managemygarbage.rf.gd/gms/index.php)

---

## 🚦 System Roles & Features

### 👨‍💼 Admin Portal

- 📊 **Dashboard** — View system stats
- 🚚 **Driver Management**
  - Add / view / delete drivers
- 📁 **Complaints**
  - View user complaints
  - Respond to complaints
- 🗑️ **Driver Bin Responses**
- 🔍 **Search** — Filter users and complaints
- 📈 **Reports** — View summarized complaint/bin data
- 👤 **Registered Users**
- 🧾 **Static Pages**
  - About Us
  - Contact Us
- 🛠️ **Profile**, **Settings**, and **Logout**

---

### 🚛 Driver Portal

- 📊 **Dashboard**
- 📩 **Assigned Complaints** — View & update
- 🗑️ **Assigned Garbage Bins**
- 🔍 **Search**
- 📈 **Reports**
- 🛠️ **Profile**, **Settings**, and **Logout**

---

### 👤 User Portal

- 📊 **Dashboard**
- 📝 **Lodge Complaint**
- 📜 **Complaint History**
- 🔍 **Search**
- 🛠️ **Profile**, **Settings**, and **Logout**

---

## 🧪 Demo Access

Live URL: [https://managemygarbage.rf.gd/gms](https://managemygarbage.rf.gd/gms)

> ⚠️ This is a public demo; use dummy data only.

---

## 📸 Screenshots

> Add these in a `screenshots/` folder in your repo.

- Admin Dashboard  
  ![Admin](screenshots/admin-dashboard.png)

- Driver Panel  
  ![Driver](screenshots/driver-dashboard.png)

- User Complaint Page  
  ![User](screenshots/user-complaint.png)

---

## ⚙️ Tech Stack

- PHP 7.x (Core Backend)
- MySQL (Database)
- Bootstrap 5 (Frontend UI)
- FontAwesome, Themify Icons

---

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/gms.git
   cd gms


How to run the Garbage Management System (GMS) Project

1. Download the  zip file

2. Extract the file and copy gms folder

3.Paste inside root directory(for xampp xampp/htdocs, for wamp wamp/www, for lamp var/www/html)

4. Open PHPMyAdmin (http://localhost/phpmyadmin)

5. Create a database with name garbagemsdb

6. Import garbagemsdb.sql file(given inside the zip package in SQL file folder)

7.Run the script http://localhost/gms (frontend)


Test Login Credentials:-

Credential for  driver panel :

Username: vams123
Password: Test@123
Or Register a new driver.

Credential for  User panel :

Username: Johndoe123
Password: Test@123
Or Register a new User.
