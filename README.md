# Clinic_Hospital_Management

IMPORTANT INSTRUCTIONS HOW TO RUN THE PROJECT :-


Run the main.py file 
In login page 
  user name: abc 
  password : pqr

Create a database for the students in mysql commandline using following Commands:

1.  CREATE DATABASE PATIENTS_DB;

2.   USE PATIENTS_DB;
   
3.  CREATE TABLE `patients` (
  `MOBILE` varchar(200) NOT NULL,
  `NAME` varchar(200) NOT NULL,
  `DOB` varchar(200) NOT NULL,
  `HISTORY` varchar(200) NOT NULL,
  `MEDICINES` varchar(200) NOT NULL,
   PRIMARY KEY (`MOBILE`)
);

# Screen Shot of Project: 
![Screenshot (1849)](https://github.com/adityasurya4103/Clinic-Hospital-Management-System-/assets/97177344/40392e22-41e4-4a3b-ad60-a8c40ab7e808)

# Description of the project :
The project is build using Python and tkinter and uses mysql as a database
Welcome to the Clinic/Hospital Management System! Our system is designed to efficiently store and manage patient data, as well as handle appointment bookings and cancellations. Here are the key features:


   - Patients can book appointments at their preferred date and time.
   - In case of schedule changes or conflicts, patients can cancel their appointments.
   - You can search for upcoming or past appointments for any patient.

Our Clinic/Hospital Management System is designed to streamline administrative tasks, improve patient record-keeping, and enhance the overall appointment management process. It ensures that essential patient information and appointment details are readily accessible and efficiently managed. If you have any questions or need assistance, feel free to ask!
