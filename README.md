✈️ Flight Management System

📋 Overview

The Flight Management System is a robust C-based application built to optimize airport operations through distinct Administrator and User interfaces. It empowers admins to manage flights and tickets while offering users real-time flight information, booking services, self check-in, and connection planning.

🌟 Key Features

🛠️ Administrator Panel

✈️ Flight Management

➕ Add new flight records (Flight No., Country, Timing, Date)

✏️ Edit existing flight information

❌ Delete flight records

🔍 Search for specific flights

📄 View all available flights


🎫 Ticket Management
📋 View all booked tickets

🧾 Access full passenger details

👤 User Interface

🕒 Flight Information

🛬 View arrival and departure times

🌍 Check schedules for multiple destinations

🧳 Booking System

📝 Book flight tickets with passenger info

💾 Store ticket data in CSV format

🛂 Self Check-in Services

🔐 Check in using passport and ticket number

💺 View seat allocation

🔗 Connection Planning

🗺️ View connecting flight options

⏱️ Calculate total travel duration with layovers

🧱 Technical Implementation

📦 Data Structures

🛫 Flight Records — struct flight

Flight Number

Destination Country

Timing

Date (DD/MM/YYYY)

🎟️ Ticket System — struct ticket

Ticket Number

Destination

Passenger Name & Age

Purchase Date

📂 File Handling

lms.bin – Binary file for flight data

tickets.csv – CSV file for ticket records

recycle.bin – Backup for deleted records

🔐 Security Features

🛡️ Password-protected Admin login

✅ Data validation for user input

🧷 Safe file operations

🧩 Code Architecture

🧱 Core Modules

✈️ Flight Operations: Add, edit, delete, search

🎫 Ticket Management

👨‍💼 Admin & 👥 User Interfaces

⚙️ Utility Functions
📂 File I/O

🔍 Input validation

📜 Menu display and flow

💾 Data Management

🧱 Structured storage with custom struct types

💡 Persistent storage in binary and text format

🏗️ Development Highlights

✅ Full CRUD support for flight and ticket management

🔐 Role-specific access: Admin & User

🗃️ Organized and reliable data storage

🧭 Clear, menu-driven UI

⚠️ Strong error handling mechanisms

🚀 How to Use
👨‍✈️ Admin Access
Launch program

Select Admin Mode

Enter password: project123 (🔒 Change before deployment)

Navigate through flight & ticket management options

👤 User Access
Choose User Mode

Select from services:

🛬 Flight Info

🧾 Ticket Booking

🛂 Self Check-in

🔗 Connection Planning

🛠️ Future Enhancements

🔒 Security

🗝️ Encrypted password storage

👥 Multi-user authentication

🗃️ Database Integration

🛢️ Replace files with SQL database

🧮 Use queries for efficient access

🌐 Additional Features
💳 Payment processing integration

📧 Email/SMS notifications

📱 Mobile-friendly UI

🧹 Code Refactoring

🧱 Implement MVC architecture

🔄 Reduce code redundancy

🚫 Improve error recovery and messaging

👨‍💻 Author

Zaid Bin Naveed

Building new projects every day with passion and purpose.
