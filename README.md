# 🏥 Hospital Management System – MySQL Project

## 📌 Project Overview

The **Hospital Management System** is a relational database project developed using MySQL. It is designed to manage hospital operations, including patient information, doctor details, departments, appointments, and payment records.

This project demonstrates practical SQL skills through table creation, data insertion, relationships between tables, and queries involving multiple tables.

## 🎯 Project Objectives

- Design and implement a relational database.
- Maintain patient and doctor information.
- Manage hospital departments and appointments.
- Track payment details and payment statuses.
- Retrieve meaningful information using SQL queries.
- Practice SQL JOINs and aggregate functions.

## 🛠️ Technologies Used

- **Database:** MySQL
- **IDE:** MySQL Workbench
- **Language:** SQL

## 🗄️ Database Structure

The project consists of five tables:

| Table Name | Description |
|---|---|
| `departments` | Stores hospital department details. |
| `doctor` | Stores doctor information and specialization. |
| `patient` | Stores patient personal details. |
| `appoinments` | Stores appointment details and diagnosis. |
| `payment` | Stores appointment payment information. |

## 🔗 Table Relationships

The database uses Primary Keys (PK) and Foreign Keys (FK) to establish relationships between tables.

1. **Departments → Doctor:** One department can have multiple doctors.
2. **Patient → Appointments:** One patient can book multiple appointments.
3. **Doctor → Appointments:** One doctor can handle multiple appointments.
4. **Appointments → Payment:** Payments are linked to appointments.

## 📚 SQL Concepts Covered

This project covers the following SQL concepts:

- CREATE TABLE
- INSERT INTO
- PRIMARY KEY
- FOREIGN KEY
- INNER JOIN
- LEFT JOIN
- Multiple Table JOINs
- WHERE Clause
- ORDER BY
- GROUP BY
- HAVING
- Aggregate Functions (SUM, COUNT)
- DISTINCT
- IS NULL

## 💡 SQL Queries Implemented

The project includes **15 practical SQL queries**:

1. Display patient names, appointment dates, diagnoses, and assigned doctors.
2. Display doctors with their specializations and department names, sorted alphabetically.
3. Find patients who have appointments with Cardiology doctors.
4. Display patient names, appointment IDs, and paid amounts.
5. List all patients along with their appointment details, including patients without appointments.
6. Display all departments and their assigned doctors, including departments without doctors.
7. Find doctors who have not received any appointments.
8. Display patient, doctor, department, appointment, and payment details for completed appointments.
9. Calculate the total payment amount collected for each doctor.
10. Find patients who have visited more than one distinct doctor.
11. Find the total number of appointments handled by each doctor.
12. Display patients with pending appointments and their assigned doctors.
13. Calculate the total amount received through each payment method.
14. Find departments that have more than one doctor.
15. Calculate the total appointments and payment amount for each patient, filtering patients whose total payment exceeds 2000.

## 📊 Key Learning Outcomes

- Understanding relational database design.
- Creating tables with appropriate constraints.
- Establishing relationships between multiple tables.
- Retrieving data using different JOIN operations.
- Applying aggregate functions to generate reports.
- Filtering grouped data using HAVING.
- Writing practical SQL queries based on real-world scenarios.

## 🚀 How to Run the Project

1. Install MySQL Server and MySQL Workbench.
2. Open MySQL Workbench and connect to your database.
3. Create a database:

   ```sql
   CREATE DATABASE hospital_management;
   USE hospital_management;
   ```

4. Execute the CREATE TABLE statements in the correct order:
   - departments
   - doctor
   - patient
   - appoinments
   - payment

5. Execute the INSERT statements to populate the tables.
6. Run the 15 SQL queries to explore the database.
