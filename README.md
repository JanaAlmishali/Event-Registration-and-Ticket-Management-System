##Project Overview
Event Registration and Ticket Management System is a desktop-based application developed using Java and Java Swing as part of the CS342 course.
The project includes the full design and implementation of the graphical user interface (GUI), database integration using MySQL and JDBC, role-based authentication, event seat tracking, ticket generation, and system notifications.
All application screens including login, dashboards, event management, tickets, and notifications were designed and implemented using Java Swing components.
##Project Objectives
Build a fully functional GUI-based desktop application
Integrate the system with a MySQL relational database using JDBC
Implement role-based authentication
Manage event seat tracking and prevent overbooking
Apply exception handling and input validation
Generate reports and analytics for monitoring
##User Roles
Admin
Login through a dedicated admin panel
View system statistics
Manage users
View and delete events
Access reports and analytics
Event Organizer
Create new events
Edit or delete events
View attendee lists
Monitor seat availability
Attendee
Browse available events
Filter events by category, location, or date
Register for events
Receive ticket confirmation
View notifications
Cancel registration (seat count updates automatically)
##Key Features
Secure authentication with password hashing
Automatic ticket generation with a unique identifier
Dashboard with system statistics
Real-time seat tracking
Overbooking prevention
In-app notification system
Event filtering and search
Reports and analytics
Robust exception handling using try/catch and JOptionPane
##Technologies and Tools Used
Programming Language
Java
GUI Framework
Java Swing
JFrame
JPanel
JTable
JButton
JTextField
JPasswordField
JComboBox
JOptionPane
Database
MySQL
Main tables:
users
admins
events
categories
registrations
notifications
Database Connectivity
JDBC (Java Database Connectivity)
Security
Password hashing utilities
IDE
NetBeans
File Management
Google Drive / OneDrive (for collaboration)
##Database Structure
The system includes relational tables with:
Primary keys
Foreign keys
UNIQUE constraints
Auto-increment IDs
Timestamp tracking (created_at, updated_at)
Key integrity rules:
UNIQUE(event_id, attendee_id)
Foreign key enforcement
Seat count synchronization
##System Modules
Authentication Module
Event Management Module
Registration and Seat Tracking Module
Ticket Generation Module
Notification Module
Admin Dashboard
Reports and Analytics
##Testing and Validation
The system was tested for:
Valid and invalid login attempts
Duplicate registration prevention
Blocking registration when event is full
Automatic seat updates
Ticket generation
Admin deletion handling
Foreign key enforcement
Database error handling
All exceptions display clear, user-friendly messages.
##How to Run the Project
Install Java JDK 8 or higher.
Install MySQL.
Create the database and required tables.
Update the database credentials inside DBConnection.java.
Open the project in NetBeans.
Run the main class.
