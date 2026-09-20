# School Management System - MySQL Mini Project

# Project Overview:
The School Management System is a database-driven application designed to manage student records, subjects, exams, and performance reports. It eliminates manual record-keeping inefficiencies by providing a centralized platform for storing and retrieving academic data.

# Features:
- Student registration and profile management
- Subject and exam scheduling
- Marks entry and performance tracking
- Query outputs for top performers, averages, and failures
- Centralized database with secure access

# Tech Stack:
- Frontend: HTML, CSS, JavaScript (optional for UI)
- Backend: Python / PHP (depending on implementation)
- Database: MySQL
- Tools: MySQL Workbench, VS Code

# API / Database Notes:
# Tables:
- Students (ID, Name, Class, Contact)
- Subjects (SubjectID, Name)
- Exams (ExamID, Date, SubjectID)
- Marks (StudentID, ExamID, Marks)
# Relationships:
- Student ↔ Subject (many-to-many)
- Exam ↔ Marks (one-to-many)
--> Queries include joins and aggregate functions for performance analysis.
  
# Database
The project uses MySQL as the database management system.

# Author
Roopasri Ummadisetty

# Document URL:
https://drive.google.com/file/d/1dTlUIbpWXTRmBlNURUhDxwNE0r_TgsWI/view?usp=sharing
