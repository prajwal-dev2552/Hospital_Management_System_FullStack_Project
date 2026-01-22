# Hospital_Management_System_FullStack_Project
Hospital Management System Project using fronted and Backend Technologies 

 Hospital Management System
 Project Overview

The Hospital Management System is a web-based application developed to manage day-to-day activities of a hospital such as patient registration, doctor management, billing, and receptionist operations.
This project is designed to reduce manual work and improve efficiency using a simple and clean interface.

 * Objective

Digitize hospital operations

Manage patient records easily

Generate and view patient bills

Provide role-based access (Admin / Receptionist)

Maintain clean and structured backend APIs

* Technologies Used
Frontend

HTML

CSS

JavaScript

EJS (Embedded JavaScript Templates)

Backend

Node.js

Express.js

Database

MySQL

 * Tools

VS Code

Git & GitHub

Postman (API Testing)

*  User Roles
# Admin

Add & manage doctors

View all patients

View billing details

# Receptionist

Register new patients

Assign doctors

Generate patient bills

View existing bills

* Project Structure
hospital-management-system/
│
├── controllers/
│   ├── patientController.js
│   ├── doctorController.js
│   └── billController.js
│
├── routes/
│   ├── patientRoutes.js
│   ├── doctorRoutes.js
│   └── billRoutes.js
│
├── views/
│   ├── addPatient.ejs
│   ├── viewPatients.ejs
│   ├── generateBill.ejs
│   └── viewBill.ejs
│
├── public/
│   ├── css/
│   └── images/
│
├── config/
│   └── db.js
│
├── app.js
├── package.json
└── README.md

🧾 Key Features

✅ Patient Registration

✅ Doctor Assignment

✅ Bill Generation

✅ View Patient Bills

✅ Clean UI for Receptionist Panel

✅ MVC Architecture

✅ RESTful APIs

 Database Tables
Patient Table

patient_id

name

health_problem

doctor_id

admit_date

Bill Table

bill_id

patient_id

room_charges

treatment_charges

nurse_charges

medicine_charges

total_amount

billing_date





📈 Learning Outcomes

Practical experience with Node.js & Express

Understanding MVC Architecture

MySQL database integration

Real-world hospital workflow implementation

👨‍💻 Developer

Name: Prajwal Dhanawade
Role: Software Developer (Fresher)
Skills: Java, Node.js, Express, MySQL, HTML, CSS
