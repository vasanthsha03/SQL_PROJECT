# 🏥 Hospital Management System – SQL Project

### A complete MySQL-based Hospital Management System project designed for practicing core SQL concepts such as:

Database Design
CRUD Operations
JOIN Queries
GROUP BY & HAVING
Subqueries
Views
Triggers
Stored Procedures

## 📌 Project Objective

### The objective of this project is to build a relational database system to manage:

Patients
Doctors
Appointments
Treatments
Billing

The project demonstrates real-world hospital database operations using SQL.

## 🛠️ Technologies Used
MySQL
SQL
MySQL Workbench 

## 🗂️ Database Tables

### 1️⃣ Patients

Stores patient details.

Column	Data Type
patient_id	INT (PK)
name	VARCHAR(100)
age	INT
gender	VARCHAR(10)
phone	VARCHAR(15)
city	VARCHAR(50)

### 2️⃣ Doctors

Stores doctor information.

Column	Data Type
doctor_id	INT (PK)
name	VARCHAR(100)
specialization	VARCHAR(50)
consultation_fee	DECIMAL(10,2)

### 3️⃣ Appointments

Stores appointment records between patients and doctors.

Column	Data Type
appointment_id	INT (PK)
patient_id	INT (FK)
doctor_id	INT (FK)
appointment_date	DATE
status	VARCHAR(20)

### 4️⃣ Treatments

Stores treatment details and treatment cost.

Column	Data Type
treatment_id	INT (PK)
appointment_id	INT (FK)
treatment_details	VARCHAR(255)
cost	DECIMAL(10,2)

### 5️⃣ Billing

Stores billing and payment details.

Column	Data Type
bill_id	INT (PK)
patient_id	INT (FK)
total_amount	DECIMAL(10,2)
payment_status	VARCHAR(20)

## 📥 Sample Data

### The project includes sample records for:

10 Patients
5 Doctors
15 Appointments
10 Treatments
10 Billing Records
