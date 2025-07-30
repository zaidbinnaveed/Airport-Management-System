Flight Management System 

Overview

This Flight Management System is a comprehensive C program that provides both administrative and user interfaces for managing airport operations. The system allows administrators to manage flight records while enabling users to check flight information, book tickets, and perform self check-in procedures.

Features

Admin Panel

Flight Management:

Add new flight records with complete details (flight number, country, timing, date)

Edit existing flight information

Delete flight records

Search for specific flights

View all available flights

Ticket Management:

View all booked tickets

Access comprehensive passenger information

User Interface

Flight Information:

View arrival and departure details

Check flight schedules for multiple destinations

Booking System:

Book flight tickets with passenger details

Store booking information in CSV format

Check-in Services:

Self check-in using passport and ticket number

Seat allocation information

Connection Planning:

View possible connecting flights

Calculate total travel duration with connections

Technical Implementation

Data Structures

Flight Records: Structured storage using struct flight containing:

Flight number

Destination country

Timing information

Flight date (day, month, year)

Ticket System: struct ticket for passenger information:

Ticket number

Destination

Passenger details (name, age)

Purchase date

File Handling

Binary file storage for flight records (lms.bin)

CSV file storage for ticket information (tickets.csv)

Backup system for deleted records (recycle.bin)

Security Features

Password-protected admin interface

Data validation for critical inputs

Secure file operations

Code Structure

The program follows a modular design with clearly separated functionalities:

Core Modules:

Flight operations (add, edit, delete, search)

Ticket booking and management

User interface components

Utility Functions:

File I/O operations

Input validation

Menu displays and navigation

Data Management:

Structured storage using custom data types

Persistent storage in binary and text formats

Development Highlights
Implemented complete CRUD operations for flight management

Developed dual interfaces (admin/user) with appropriate access controls

Created comprehensive data storage and retrieval system

Designed intuitive user menus and navigation

Added robust error handling for file operations

How to Use

Admin Access:

Run the program and select admin mode

Use password "project123" (should be changed in production)

Manage flights through the admin menu

User Access:

Select user mode from main menu

Choose from available services:

Flight information

Ticket booking

Self check-in

Connection planning

Future Enhancements

Security Improvements:

Encrypted password storage

User authentication system

Database Integration:

Replace file storage with proper database

Implement SQL queries for data management

Additional Features:

Payment processing integration

Email notification system

Mobile-friendly interface

Code Refactoring:

Implement proper MVC architecture

Reduce code complexity

Improve error handling

Author:

Zaid Bin Naveed

Building new projects everyday

Push to the branch

Create a new Pull Request
