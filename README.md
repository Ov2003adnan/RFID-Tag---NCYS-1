# RFID-Tag---NCYS-1
NCYS-1 RFID Tag System

Project Description

This project is an RFID-based attendance and authentication system developed for the NCYS-1 (Network and Cyber Security - 1) course. It allows an admin to register users with a unique RFID, and users can authenticate themselves by scanning their RFID to mark attendance. The project is purely for educational purposes and demonstrates fundamental RFID authentication techniques.

Features

Admin Functionalities:

Add new users (students or faculty) with a unique RFID.

View the complete database of registered users.

Export attendance records (Feature to be implemented).

User Functionalities:

Authenticate using an RFID tag.

Mark attendance upon successful authentication.

How It Works

The admin registers a person by entering their name, role (Student/Faculty), and the year of registration.

A random RFID is generated based on the year and assigned to the person.

The user scans their RFID to mark attendance.

The system authenticates the RFID and updates attendance records.

The admin can view the database of users and their attendance status.

Installation & Compilation

Requirements:

C++ Compiler (g++)

Any C++ IDE (e.g., Code::Blocks, VS Code, Dev-C++)

Compilation:

 g++ rfid_system.cpp -o rfid_system

Running the Program:

 ./rfid_system

Code Structure

Person Class: Stores user details, including name, role, RFID, and attendance status.

Admin Functions:

addPerson(): Registers a new person.

readRFID(): Simulates RFID scanning.

authenticatePerson(): Checks if the RFID is valid.

User Menu: Allows users to authenticate and mark attendance.

Database Management: Stores registered users and their attendance status.

Example RFID Format

Generated RFID Example: 23k-4512

Format: YYk-XXXX

YY: Last two digits of the year

k: Fixed character for consistency

XXXX: Random four-digit number

Future Enhancements

Implement file-based attendance export.

Support external RFID hardware integration.

Enhance security measures to prevent unauthorized access.

Disclaimer

This project is developed for educational purposes only under the NCYS-1 course. Unauthorized use for illegal activities is strictly prohibited.

Developed By: Ovais Adnan
Hamza Khan
Sohaib Jaber

Course: Network and Cyber Security - 1
