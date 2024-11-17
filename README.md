The Hospital Management System is a simple Java-based application that allows hospital staff to manage various aspects of hospital operations efficiently. The system uses JDBC (Java Database Connectivity) to connect with a relational database (DBMS), such as MySQL, to handle patient, doctor, and appointment data.

Features:

    Add Patient: Add a new patient's details to the system by entering their Patient ID and Name.
    View Patients: View a list of all registered patients in the hospital.
    View Doctors: View the list of available doctors along with their specialization.
    Book Appointment: Book an appointment by associating a Patient ID with a Doctor ID.
    Exit: Exit the program.

Database Structure:

    The system interacts with the following tables in the database:

    Patients: Contains patient information (Patient ID, Name).
    Doctors: Contains doctor information (Doctor ID, Name, Specialization).
    Appointments: Records appointments by linking Patient ID and Doctor ID.

How it Works:

    The user interacts with the system via a menu to add, view, or manage patient and doctor records.
    The program uses SQL queries to interact with the database and update or retrieve records.
    JDBC handles the connection between the Java application and the database.

This Hospital Management System offers a straightforward approach to hospital administration, with a focus on managing patient and doctor records, as well as handling appointments, all integrated through Java and JDBC for smooth database operations.
