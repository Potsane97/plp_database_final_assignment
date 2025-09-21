# plp_database_final_assignment
# 🏥 Clinic Booking System Database

## 📌 Project Overview
This project is a **relational database management system (RDBMS)** built using **MySQL**.  
It models a **clinic booking system** where patients can book appointments with doctors.  

The database includes well-structured tables, constraints, and relationships to ensure data integrity and efficient management.

---

## 🎯 Objectives
- Design a relational database schema for a real-world use case.  
- Implement **tables with constraints** (PRIMARY KEY, FOREIGN KEY, NOT NULL, UNIQUE).  
- Establish **relationships** (One-to-Many, Many-to-One).  
- Deliver a **single `.sql` file** with the schema creation.  

---

## 🗂️ Database Schema
### Entities
1. **Patients** – Stores patient details (name, DOB, contact info).  
2. **Doctors** – Stores doctor details and specialization.  
3. **Appointments** – Manages bookings between patients and doctors.  

### Relationships
- **One Patient → Many Appointments**  
- **One Doctor → Many Appointments**  

---

## ⚙️ Setup Instructions
1. Install **MySQL Server** on your system.  
2. Open **MySQL Workbench** or your preferred client.  
3. Run the provided SQL script:

   ```bash
   source clinic_booking.sql;
