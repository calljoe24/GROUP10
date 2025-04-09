Hospital Management System (HMS)
Overview
The Hospital Management System (HMS) is a comprehensive solution designed to manage and automate various administrative functions of a hospital, including patient appointments, pharmacist data, nurse and doctor records, and more. This system enhances the efficiency and accuracy of hospital operations by providing a streamlined platform for managing appointments, treatments, and healthcare data.

Features
Appointment Management:

Ability to add, update, and delete appointments.

Doctors' availability is managed through a timer-based system, allowing automatic updates when appointment times expire.

Patient and doctor details are linked for each appointment.

Pharmacist Management:

Manage the inventory of medicines, including tracking medicine names, costs, and stock.

Nurse Management:

Manage nurse details such as name, specialization, experience, and gender.

Password Reset:

Secure reset password feature for users to manage their account credentials.

Technologies Used
Backend: SQL Server for the database management

Frontend: Visual Basic .NET (VB.NET) for the UI and application logic

Database: SQL Server tables such as AppointmentTbl, PharmacistTbl, NurseTbl, and TreatmentTbl for managing data.

Database Schema
Appointment Table (AppointmentTbl)
AptId: Appointment ID (Primary Key)

PatId: Patient ID

PatName: Patient's Name

DocId: Doctor ID

DocName: Doctor's Name

Pharmacist Table (PharmacistTbl)
InpId: Input ID (Primary Key)

Med: Medicine Name

Cost: Medicine Cost

Stk: Medicine Stock

Nurse Table (NurseTbl)
NuId: Nurse ID (Primary Key)

NuName: Nurse Name

NuExp: Nurse Experience

NuGender: Nurse Gender

NuSpec: Nurse Specialization

Treatment Table (TreatmentTbl)
TreatId: Treatment ID (Primary Key)

TreatDesc: Treatment Description

TreatCost: Treatment Cost

Setup
Clone or download the repository to your local machine.

Install Visual Studio with VB.NET support and SQL Server.

Set up the database on your SQL Server with the provided schema.

Configure the connection strings in the App.config file to link to your database.

Build and run the project in Visual Studio.

Usage
Launch the application to access the different forms (Appointment, Pharmacist, Nurse, Treatment).

For appointments, select a patient, doctor, and date/time. Appointments will be managed and updated based on available slots.

For pharmacist management, add or update medicine details such as name, cost, and stock.

For nurse management, record the nurse’s details including specialization, experience, and gender.

Future Enhancements
Implementing patient records management to store and retrieve patient medical history.

Adding a search and filter feature across forms for easy data management.

Implementing notifications for appointment reminders.

Contact
For any questions or contributions, feel free to reach out via email or open an issue on this repository.

