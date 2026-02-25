# SQL_PROJECT
Library Database Analysis using MySQL Designed and implemented a relational database for library management with 7 interconnected tables. Performed advanced SQL queries using JOIN, GROUP BY, COUNT, and subqueries to analyze book availability, loan records, and borrower activity.
# 📚 Library Database Analysis using MySQL

## 📌 Project Overview
This project focuses on designing and analyzing a structured relational database for a Library Management System using MySQL.

The database consists of 7 interconnected tables with proper Primary Keys and Foreign Keys to maintain referential integrity.

---

## 🏗️ Database Design

### 🔹 Tables Created:
- Books
- Authors
- Publishers
- Library Branch
- Borrowers
- Book Copies
- Book Loans

An ER Diagram was designed before implementation to clearly define relationships between all entities.

---

## 🔗 Relationships Implemented
- One-to-Many relationships between:
  - Branch → Book Copies
  - Book → Book Loans
  - Borrower → Book Loans
- Many-to-Many handled using:
  - Book Authors table

---

## 🧠 SQL Concepts Used
- SELECT statements
- INNER JOIN
- LEFT JOIN
- GROUP BY
- HAVING
- COUNT()
- Aggregate Functions
- Subqueries
- Primary & Foreign Keys

---

## 📊 Task-Based SQL Analysis

### ✅ Task 1
Find number of copies of "The Lost Tribe" in Sharpstown branch.

### ✅ Task 2
Find number of copies of "The Lost Tribe" in each branch.

### ✅ Task 3
Retrieve borrowers who have no books checked out.

### ✅ Task 4
Find books loaned from Sharpstown branch due on 2/3/18 with borrower details.

### ✅ Task 5
Find total books loaned from each branch.

### ✅ Task 6
Retrieve borrowers who have more than 5 books checked out.

### ✅ Task 7
Find books authored by Stephen King available in Central branch.

---

## 🎯 Key Learnings
✔ Designed structured relational database  
✔ Implemented 7 interconnected tables  
✔ Maintained data integrity using Primary & Foreign Keys  
✔ Performed real-world analytical SQL queries  
✔ Improved understanding of database normalization and joins  

---

## 🛠️ Tools Used
- MySQL
- MySQL Workbench
- ER Diagram Tool

---

## 📌 Conclusion
This project strengthened my understanding of real-world database design and SQL operations used in analytics and backend systems.

---

👨‍💻 Developed By: Rajsekhar Velagala
