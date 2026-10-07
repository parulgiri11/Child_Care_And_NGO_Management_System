# Child Care and NGO Management System

## 📌 Project Overview

The **Child Care and NGO Management System** is a MySQL-based database project designed to manage and organize information related to children, NGOs, volunteers, donations, staff, and other activities involved in child care and NGO operations.

The project demonstrates how a relational database can be used to efficiently store, manage, and retrieve structured information while maintaining relationships between different entities.

---

## 🎯 Objectives

* Manage child-related information efficiently.
* Maintain NGO and staff records.
* Manage volunteer information and assignments.
* Track donations and donor details.
* Store and retrieve child care and support information.
* Establish relationships between different entities using relational database concepts.
* Perform SQL queries to generate useful information and insights.
* Demonstrate practical implementation of database management concepts using MySQL.

---

## 🛠️ Technologies Used

* **Database:** MySQL
* **Tool:** MySQL Workbench
* **Language:** SQL
* **Version Control:** Git & GitHub

---

## 🗂️ Database Components

The database is designed around multiple entities involved in the management of child care and NGO activities.

Key entities include:

* **Children** – Stores information about children under care.
* **NGOs** – Contains details about registered NGOs.
* **Staff** – Stores information about NGO staff members.
* **Volunteers** – Maintains volunteer records.
* **Donors** – Contains donor information.
* **Donations** – Tracks donations made by donors.
* **Care/Support Records** – Maintains information related to child care and support activities.

The tables are connected using **Primary Keys** and **Foreign Keys** to maintain data integrity and establish relationships between entities.

---

## 🔑 Key SQL Concepts Demonstrated

This project demonstrates several important SQL and database concepts:

* Database creation
* Table creation
* Primary Keys
* Foreign Keys
* Constraints
* Data insertion
* Data retrieval
* `SELECT` statements
* `WHERE` conditions
* `ORDER BY`
* `GROUP BY`
* Aggregate functions
* `COUNT()`
* `SUM()`
* `AVG()`
* `MIN()` and `MAX()`
* `JOIN` operations
* Subqueries
* Filtering and sorting
* Data analysis using SQL

---

## 📊 Example Business Questions

The database can be used to answer questions such as:

* How many children are currently registered?
* Which NGOs are managing the highest number of children?
* How many volunteers are associated with each NGO?
* What is the total donation received?
* Which donors have contributed the most?
* Which children are associated with a particular NGO?
* How many volunteers are assigned to each NGO?
* What is the average donation amount?
* Which NGOs have received the highest donations?
* What child-care activities or support records are available?

---

## 📁 Project Structure

```text
Child-Care-and-NGO-Management-System/
│
├── README.md
│
├── p_adoption.sql
├── p_donation.sql
├── p_donor.sql
├── p_employees.sql
├── p_expense.sql
├── p_inventory.sql
├── p_orphan.sql
└── p_sponsor.sql


```


---

## 🚀 How to Run the Project

### 1. Install MySQL

Install **MySQL Server** and **MySQL Workbench** on your system.

### 2. Clone the Repository

```bash
git clone https://github.com/parulgiri11/Child_Care_And_NGO_Management_System.git
```

### 3. Open MySQL Workbench

Open the project SQL files in MySQL Workbench.

### 4. Create the Database

Run the database/schema SQL script first.

```sql
CREATE DATABASE child_care_ngo;
USE child_care_ngo;
```

### 5. Create Tables

Execute the table creation scripts to create the required tables and relationships.

### 6. Insert Sample Data

Run the sample data script to populate the database.

### 7. Run SQL Queries

Execute the queries provided in the project to retrieve information and perform analysis.

---

## 💡 Key Learning Outcomes

Through this project, I gained practical experience in:

* Designing a relational database.
* Creating interconnected tables.
* Defining primary and foreign key relationships.
* Writing SQL queries for data retrieval and analysis.
* Using joins and aggregate functions.
* Working with structured relational data.
* Understanding database normalization and data integrity.
* Using MySQL Workbench for database development and testing.

---

<!-- ## 📸 Project Screenshots

Screenshots of the database structure, tables, relationships, and SQL queries can be added here.

Example:

```markdown
![Database Schema](screenshots/database_schema.png)
``` -->

---

## 🔮 Future Improvements

The project can be further enhanced by:

* Adding a web-based interface.
* Implementing user authentication.
* Adding advanced reporting and analytics.
* Connecting the database with Python or Power BI.
* Adding automated donation and volunteer reports.
* Developing dashboards for NGO performance and child-care insights.

---

## 👩‍💻 Author

**Parul Giri**

Data Analyst | Python | SQL | Excel | Power BI

📌 GitHub: [https://github.com/parulgiri11]

📌 LinkedIn: [https://www.linkedin.com/in/parul-giri/]

---

## ⭐ Conclusion

The **Child Care and NGO Management System** demonstrates the practical application of **MySQL and SQL** for managing a structured NGO and child-care database.

The project focuses on relational database design, data management, SQL querying, and extracting meaningful information from connected datasets.
