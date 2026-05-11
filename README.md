# 🗂️ Employee Management System — SQL Project

A SQL project built around an Employee Management System. This is a self-made project designed to practice and demonstrate fundamental SQL skills using a small, structured dataset.

---

## 📌 Project Overview

This project simulates a basic company database with two related tables — `Employees` and `Departments`. Through a series of queries, it covers the most essential SQL operations used in real-world data analysis and database management.

The dataset was intentionally kept small and relatable, since every organization has employees and departments — making it easy to connect SQL concepts to practical scenarios.

---

## 🗃️ Database Structure

**Employees Table**
- EmployeeID
- Name
- DepartmentID
- Salary
- HireDate

**Departments Table**
- DepartmentID
- DepartmentName

---

## 🔍 Queries Covered

| # | Query Task | Concept Used |
|---|-----------|--------------|
| 1 | Show all employee names and salaries | `SELECT` |
| 2 | Find employees in the Finance department | `WHERE` |
| 3 | Display the first 3 employees | `LIMIT` |
| 4 | Count employees in the IT department | `COUNT` |
| 5 | Total salary paid in the HR department | `SUM` |
| 6 | Find the highest salary across all employees | `MAX` |
| 7 | Show employee names with their department names | `INNER JOIN` |
| 8 | Show all departments including ones with no employees | `LEFT JOIN` |
| 9 | Find employees earning above average salary | Subquery + `AVG` |
| 10 | Employees hired after 2019 in Marketing | `WHERE` + `AND` |

---

## 💡 Key Learnings

- How to design and structure relational tables
- Writing clean, readable SQL queries
- Using aggregate functions (`COUNT`, `SUM`, `MAX`, `AVG`) to answer business questions
- Connecting tables with `INNER JOIN` and `LEFT JOIN`
- Using subqueries to make comparisons dynamic
- Handling date filtering with comparison operators

---

## ⚙️ How to Run This Project

1. Open your preferred SQL environment (MySQL Workbench, pgAdmin, DB Browser for SQLite, etc.)
2. Create a new database:
```sql
   CREATE DATABASE employee_management;
   USE employee_management;
```
3. Create the `Departments` and `Employees` tables
4. Insert the sample data
5. Run any of the queries from the project

---

## 🚧 Challenges Faced

One of the trickier parts was working with date formats and making sure queries returned the right output when filtering by hire date. I also had to thoughtfully design the dataset itself — if the data isn't set up right, the queries don't produce meaningful results. Working through these issues independently helped build real confidence with SQL.

---

## 👤 Author

**Md. Sirajul Islam**  
Data Aspirant | SQL Enthusiast  

---

> *This is a self-made project created for learning and portfolio purposes.*
