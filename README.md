# 📚 Library Management System

A **web-based Library Management System** developed using **Java, JSP, Servlets, JDBC, MySQL, Apache Tomcat, HTML, CSS, and Bootstrap**. The system enables administrators to manage books and students to search, reserve, issue, renew, and return books through an intuitive web interface.

---

## 🚀 Features

### 👨‍💼 Admin Module

* Secure Admin Login
* Add New Books
* Update Book Information
* Delete Books
* View All Books
* Issue Reserved Books
* View Reserved Books
* View Issued Books
* Renew Books
* Return Books
* View Renewed Books
* View Returned Books

### 👨‍🎓 Student Module

* Student Registration
* Secure Login
* View Available Books
* Reserve Books
* View Reserved Books
* View Issued Books
* View Renewed Books
* View Returned Books

---

## 🛠️ Technologies Used

| Technology      | Purpose                 |
| --------------- | ----------------------- |
| Java            | Backend Development     |
| JSP             | Dynamic Web Pages       |
| Servlets        | Request Processing      |
| JDBC            | Database Connectivity   |
| MySQL           | Database Management     |
| Apache Tomcat 7 | Web Server              |
| HTML5           | Frontend Structure      |
| CSS3            | Styling                 |
| Bootstrap 4     | Responsive UI           |
| Eclipse IDE     | Development Environment |

---

## 📂 Project Structure

```text
LibraryManagementSystem
│
├── src
│   └── main
│       ├── java
│       │   ├── beans
│       │   ├── dao
│       │   ├── factory
│       │   └── servlets
│       │
│       └── webapp
│           ├── admin
│           ├── student
│           ├── bootstrap
│           ├── WEB-INF
│           ├── index.jsp
│           ├── Register.html
│           └── Logout.jsp
│
└── README.md
```

---

## 🗄️ Database Design

**Database Name**

```sql
lms
```

**Tables**

* register
* book
* bookIssued

---

## ⚙️ Installation

### 1. Import the Project

* Open Eclipse IDE.
* Import the project as a Dynamic Web Project.

### 2. Configure Apache Tomcat

* Install Apache Tomcat 7.
* Configure the Tomcat server in Eclipse.

### 3. Configure MySQL

Create a database named:

```sql
CREATE DATABASE lms;
```

Execute the SQL script provided in the project to create all required tables.

### 4. Configure JDBC

Update the database credentials in `DBConn.java` according to your local MySQL configuration.

### 5. Add MySQL Connector

Add the MySQL Connector JAR file to the Apache Tomcat `lib` directory.

### 6. Run the Project

* Start the Apache Tomcat server.
* Open the application in your browser:

```text
http://localhost:8080/LibraryManagementSystem
```

---

## 🎯 Future Enhancements

* Password Encryption
* Email Notifications
* Advanced Book Search
* Fine Management System
* Mobile Responsive UI
* Cloud Deployment
