# 🧑‍💼 Employee Management System (Java Swing + MySQL)

This is a simple desktop GUI application built using **Java Swing** for the front-end and **MySQL** for the database. The system allows you to insert new employees and search employee details either by ID or fetch all records from the database.

---

## 🚀 Features

- Add new employee records (ID, Name, Department)
- Search employee by ID
- View all employee records
- Scrollable output panel for cleaner display
- Responsive, clean, and intuitive GUI

---

## 💻 Technologies Used

- Java (JDK 8 or later)
- Swing (for GUI)
- JDBC (Java Database Connectivity)
- MySQL Database

---

## 🧱 Table Structure

Make sure your MySQL database `subh` has a table named `emp` with the following structure:

```sql
CREATE TABLE emp (
  empid INT PRIMARY KEY,
  name VARCHAR(100),
  dept VARCHAR(100)
);
