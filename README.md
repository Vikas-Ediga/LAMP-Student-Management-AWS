# Student Management System

A web-based **Student Management System** developed using the **LAMP stack** and deployed on an **AWS EC2 instance**.

## 🚀 Project Overview

This project is designed to manage student information through a simple web interface. It demonstrates how a PHP application can be hosted on an AWS EC2 server using Apache and connected to a database.

## 🛠️ Technologies Used

* **HTML5** – Web page structure
* **CSS3** – Styling and layout
* **PHP** – Backend development
* **MySQL** – Database management
* **Apache** – Web server
* **Linux/Ubuntu** – Server operating system
* **AWS EC2** – Cloud hosting

## ✨ Features

* Add student details
* View student records
* Manage student information
* Store data in a MySQL database
* PHP-based dynamic web pages
* Hosted on an AWS EC2 instance
* Accessible through a web browser

## 🏗️ Architecture

```text
User
  ↓
Web Browser
  ↓
AWS EC2 Instance
  ↓
Apache Web Server
  ↓
PHP Application
  ↓
MySQL Database
```

## ☁️ AWS Deployment

The application was deployed on an **AWS EC2 instance**.

### Deployment Steps

1. Launch an EC2 instance.
2. Connect to the instance using SSH.
3. Install Apache.
4. Install PHP.
5. Install MySQL.
6. Configure the web server.
7. Upload the PHP project files.
8. Configure the database.
9. Access the application using the EC2 public IP address.

## 📂 Project Structure

```text
student-management/
│
├── index.php
├── add.php
├── edit.php
├── delete.php
├── db.php
├── style.css
└── README.md
```

> File names may vary depending on the final version of the project.

## 🗄️ Database

The project uses **MySQL** to store and manage student information.

Typical student information includes:

* Student ID
* Student Name
* Email
* Course
* Phone Number

## 🔐 Security Group Configuration

For web access, the EC2 security group allows:

| Type | Port | Purpose               |
| ---- | ---: | --------------------- |
| SSH  |   22 | Server administration |
| HTTP |   80 | Web application       |

## ▶️ How to Run Locally

1. Install Apache, PHP, and MySQL.
2. Place the project inside the Apache web directory.
3. Start Apache and MySQL.
4. Create the required MySQL database.
5. Configure the database connection in the PHP file.
6. Open the application in a browser.

Example:

```text
http://localhost/student-management/
```

## 🌐 AWS Access

After deployment, the application can be accessed using:

```text
http://<EC2-PUBLIC-IP>/
```

## 📌 Learning Outcomes

Through this project, I gained practical experience in:

* PHP web development
* MySQL database integration
* Linux server administration
* Apache configuration
* AWS EC2 deployment
* Security Group configuration
* Hosting web applications on the cloud

## 🔮 Future Improvements

* User authentication and authorization
* Student search and filtering
* Attendance management
* Course management
* Responsive UI
* HTTPS/SSL configuration
* Automated deployment using CI/CD

## 👨‍💻 Author

**Vikas N D**

Cloud & DevOps Learner

---

⭐ If you found this project useful, feel free to explore the repository and give it a star.
