🎓 **Student Database Management System**

A simple yet scalable student record manager built with Python & SQLite3 — perform CRUD operations to efficiently manage academic data.

🧩 ** Project Overview**

This project demonstrates how to create and manage a Student Database System using SQLite3 in Python.
It allows users to Add, View, Update, and Delete student information such as Name, Roll Number, Class, and Marks, making record management fast and reliable.

🗄️ ** Database Details**

Database Name: student_database.db
Table: students

Column	Type	Description
id	INTEGER	Primary Key
name	TEXT	Student Name
roll_no	INTEGER	Unique Roll Number
class	TEXT	Class/Grade
marks	INTEGER	Student Marks

⚙️ **How to Run**

# 1. Clone this repository
git clone https://github.com/<your-username>/student_database.git
cd student_database

# 2. Run the Python script
python student_database.py

The system will automatically create student_database.db and display a console menu for CRUD operations.

💾** Example SQL Queries**

INSERT INTO students (name, roll_no, class, marks)
VALUES ('John Doe', 101, '10-A', 87);

SELECT * FROM students;

UPDATE students SET marks = 92 WHERE roll_no = 101;

DELETE FROM students WHERE roll_no = 101;

🧠** Key Findings**

SQLite3 offers a lightweight, serverless way to manage structured data efficiently.

Python’s sqlite3 library makes CRUD implementation fast and intuitive.

The schema is easily extendable for additional academic features.

Proper input validation ensures data reliability.

The .db file is fully portable and easy to integrate with dashboards or web apps.

⚗️** Challenges & Learnings**

Ensured data uniqueness and error handling for roll numbers.

Learned how Python interacts directly with SQL databases.

Built a foundation for integrating this system with analytics dashboards.

💼 **Freelance Pitch**

“Developed a robust Student Management System using Python & SQLite3 — designed for schools and freelancers seeking simple, efficient data tracking and reporting.”

👩‍💻** About Me**

Hi, I’m Nadia Hafsa — a passionate Data Science and Analytics Enthusiast with hands-on experience in Python, SQL, React, and Docker.
I enjoy building data-driven projects and automating workflows that bridge analysis and development.

💼 **Freelance Focus**:

Interactive dashboards

Data automation tools

Web & API integration

📫 **Connect:** 
 | GitHub: https://github.com/NadiaHafsa
 | LinkedIn: www.linkedin.com/in/nadia-hafsa-93986975
 | ✉️ nadia26hafsa@gmail.com
