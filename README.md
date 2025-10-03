# Hospital-Management-System-Java-MySQL-
A simple console-based Hospital Management System built in Java with MySQL as the backend database. The system allows users to manage patient records, view doctor details, and book appointments between patients and doctors with date validation.

🚀 Features
➕ Add new patients
📄 View all patients
👨‍⚕️ View available doctors
📅 Book appointments (only if doctor is available on selected date)
✅ Validates existence of patient and doctor before booking

📂 Modules
HospitalManagementSystem.java – Main controller class with menu-driven interface
Patient.java – Handles patient-related operations
Doctor.java – Handles doctor-related operations

📌 Database Tables (Basic structure)
patients(id, name, age, gender)
doctors(id, name, specialization)
appointments(id, patient_id, doctor_id, appointment_date)
