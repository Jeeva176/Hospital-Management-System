Hospital Management System

Project Description:

The Hospital Management System (HMS) project is designed to manage hospital operations such as doctor schedules, patient appointments, medical records, and more. It uses a relational database to track patient information, doctor details, appointments, and medical histories.

Database Setup:

Create a new database named "Hospital" to store the information.

Doctor Table: Stores doctor info (ID, name, specialization, contact).

Patient Table: Stores patient details (ID, name, age, contact).

Appointment Table: Stores appointment details (ID, patient ID, doctor ID, date/time).

Medical Records Table: Stores patient medical records (record ID, patient ID, diagnosis, treatment).

Features:

Appointment scheduling and tracking.

Managing patient records and history.

Doctor availability and specialization management.

Generating reports and statistics on patient care. 

Queries and Analysis

The project includes various SQL queries and data analysis tasks to extract valuable insights from the hospital's data. Some of the key queries implemented include:

1. Join: Retrieve the names of all patients and their assigned doctors by joining the Patient and Doctor tables through the Appointment table.


2. Group By: Find the total number of appointments for each doctor, grouped by doctor name.


3. Order By: List all appointments in descending order of date and time.


4. Aggregate Function: Calculate the average age of patients in the hospital.


5. Join with Condition: Get all patients who have appointments with a specific doctor, joining the Appointment and Patient tables.


6. Case: Display the patient status as "Senior" if their age is above 60, otherwise "Adult", using a CASE statement.


7. Order By ASC: Retrieve all doctors sorted in ascending order of their specialization.


8. Group By with Having: List all doctors with more than 10 appointments, using the HAVING clause.


9. Join with Aggregate Function: Find the total number of medical records created for each patient by joining the MedicalRecords and Patient tables.


10. Aggregate Function with Condition: Count how many appointments took place in the last 30 days.


11. Join with Multiple Tables: Retrieve all appointments, patient names, and doctor names by joining Appointment, Patient, and Doctor tables.


12. Order By with Multiple Columns: List patients who have appointments sorted first by doctor specialization and then by appointment date in descending order.





