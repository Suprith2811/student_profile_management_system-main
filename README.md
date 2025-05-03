# 🧑‍🎓 Student Management System

A desktop-based Student Management System built using **Python Tkinter** for the GUI and **MySQL** for backend database operations. This application helps manage student records efficiently by allowing users to add, update, delete, and search student information.

---

## 📌 Features

- ✅ Add New Student Records  
- ✏️ Update Student Details  
- 🗑️ Delete Student Entries  
- 🔍 Search by Student ID, Name, Course  
- 📋 View All Records in a Scrollable Table  
- 🖥️ User-friendly GUI (Tkinter)  
- 💾 Data persistence using MySQL  

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

---

## 🚀 How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/student-management-system.git
   cd student-management-system
   ```

2. **Set Up the MySQL Database**
   - Open MySQL Workbench or any MySQL client.
   - Run the SQL script `setup.sql` provided in the repo to create the database and table.

3. **Update Database Configuration**
   - Open the main Python script (e.g., `main.py` or `student_app.py`).
   - Find the section with MySQL credentials:
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

## 🖼️ Screenshots

> _Include screenshots of the GUI here (e.g., Add Student Form, Search Panel, Records Table)_

![Home Screen](screenshots/home.png)
![Add Student](screenshots/add_student.png)
![Search Student](screenshots/search.png)

---

## 📁 Project Structure

```
student-management-system/
├── main.py
├── db_config.py
├── setup.sql
├── README.md
└── screenshots/
    ├── home.png
    ├── add_student.png
    └── search.png
```

---

## 🙋‍♂️ Author

Developed by [Your Name]  
📧 [your.email@example.com]  
🔗 [LinkedIn/GitHub profile link]

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).