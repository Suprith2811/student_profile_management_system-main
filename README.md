#  Student Management System

A desktop-based Student Management System built using **Python Tkinter** for the GUI and **MySQL** for backend database operations. This application helps manage student records efficiently by allowing users to add, update, delete, and search student information.

---

##  Features

-  Add New Student Records  
-  Update Student Details  
-  Delete Student Entries  
-  Search by Student ID, Name, Course  
-  View All Records in a Scrollable Table  
-  User-friendly GUI (Tkinter)  
-  Data persistence using MySQL
-  Export Data into excel Sheets 

---

## 🛠️ Tech Stack

- **Frontend:** Python (Tkinter)  
- **Backend:** Python  
- **Database:** MySQL  
- **Connector:** `mysql-connector-python`  

---

## 📦 Requirements

- Python 3.x  
- MySQL Server  
- `mysql-connector-python` (Install using: `pip install mysql-connector-python`)
- `Pillow==10.2.0` (Install using: `pip install Pillow`)
- `PyMySQL==1.1.0` (Install using: `pip install PyMySql`)

---

## 🚀 How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/suprith2811/student-management-system.git
   cd student-management-system
   ```

2. **Set Up the MySQL Database**
   - Open MySQL Workbench or any MySQL client.
   - create this Structure
CREATE DATABASE student_db;
USE student_db;
CREATE TABLE students (
    id INT PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(100),
    dob DATE,
    gender VARCHAR(10),
    email VARCHAR(100),
    phone VARCHAR(15),
    address TEXT,
    photo_path VARCHAR(255)
);



3. **Update Database Configuration**
   - Open the main Python script.
   - Find the section with Mysql credentials:
     ```python
     mydb = mysql.connector.connect(
         host="localhost",
         user="your_username",
         password="your_password",
         database="student_db"
     )
     ```
   - Replace with your MySQL credentials.

4. **Run the Application**
   ```bash
   python main.py
   ```

---



---

## 🙋‍♂️ Author

Developed by [Supreeth]  
📧 [gollapallisupreeth@gmail.com]  
🔗 [https://www.linkedin.com/in/gpllapally-supreeth]

---
