# Manicure Appointment Booking System

## Course
Cap1: System Analysis and Design

---

# 1. Team Information

Team Name: Team 777

| Name | Student ID | Role | Responsibilities |
|-----|-----|-----|-----|
| Mariya Gorbacheva | 202490123 | Team Leader | Oversees the project and coordinates the team |
| Karina Gumerova | 202490124 | System Analyst | Analyzes system requirements |
| Maksim Em | 202490106 | System Designer | Creates system models and diagrams |
| Diyorbek Voidjonov | 202490357 | Documentation Specialist | Prepares project documentation |

---

# 2. Project Description

The Manicure Appointment Booking System is designed to simplify the process of scheduling manicure services in beauty salons.

Many salons currently manage appointments using phone calls, social media messages, or handwritten notebooks. These methods often lead to scheduling conflicts, missed appointments, and inefficient time management.

The proposed system provides a centralized platform where customers can easily book manicure appointments, while salon staff can manage schedules and monitor service availability.

---

# 3. Key Features

- Customer appointment booking
- Viewing available time slots
- Appointment management by salon staff
- Organized scheduling and record keeping
- Customer information storage

---

# 4. Problem Statement

Many manicure salons still manage appointments manually using phone calls or messaging applications.

This approach often leads to:

- Scheduling conflicts
- Double bookings
- Difficulties tracking appointments

Without a structured system, salon administrators and specialists may struggle to manage time efficiently, which can negatively affect customer satisfaction and service quality.

---

# 5. Project Objectives

The objectives of this project are:

- Analyze the current manicure appointment booking process
- Identify system users and their needs
- Define functional and non-functional requirements
- Design a structured booking system
- Apply System Analysis and Design methodologies
- Improve scheduling efficiency and customer experience

---

# 6. System Scope

## 6.1 System Includes

- Customer appointment booking
- Viewing available manicure time slots
- Appointment management by salon staff
- Customer information management
- Organized scheduling records

## 6.2 Limitations

- No online payments
- No real-time chat support
- No automated reminders
- No advanced analytics

This system is designed for **academic purposes only**.

---

# 7. Expected Users

## 7.1 Customers

Customers can:

- View available time slots
- Book manicure appointments

## 7.2 Salon Administrators

Administrators can:

- Manage appointment schedules
- Monitor bookings
- Cancel or modify appointments

## 7.3 Manicure Specialists

Specialists can:

- View assigned appointments
- Manage their availability

---

# 8. Project Timeline

| Week | Activities |
|-----|-----|
| Week 1 | Problem identification and planning |
| Week 2-3 | Requirements analysis |
| Week 4-5 | System design |
| Week 6-7 | Documentation and submission |

---

# 9. Use Case: Customer Books an Appointment

Primary Actor: Customer

### Main Flow

1. Customer logs into the system
2. Opens booking page
3. System displays available time slots
4. Customer selects date and time
5. Customer confirms booking
6. System saves appointment in the database

### Alternative Flow

- If the slot is already booked → error message  
- If the user is not logged in → redirect to login page

---

# 10. Use Case: Administrator Manages Appointments

Primary Actor: Administrator

1. Administrator logs into system
2. Opens appointment management panel
3. Views scheduled appointments
4. Edits or cancels bookings

---

# 11. System Architecture Diagram

Insert architecture diagram from the Word file.

![System Architecture](images/system_architecture.png)

Architecture components:

- User Management
- Appointment System
- Schedule Management
- SQL Database

---

# 12. Database Design and SQL Implementation

The system database stores information about users, appointments, and schedules.

Relationships between tables ensure structured data storage and efficient retrieval of appointment information.

---

## 12.1 Creating Database Tables

Insert screenshot of SQL code that creates tables.

![Create Tables](images/create_tables.png)

---

## 12.2 Creating Schedule Table

Insert screenshot showing schedule table creation.

![Create Schedule Table](images/create_schedule_table.png)

---

## 12.3 Creating Appointment Table

Insert screenshot showing appointment table creation.

![Create Appointment Table](images/create_appointment_table.png)

---

## 12.4 Inserting Sample Users

Insert screenshot inserting users.

![Insert Users](images/insert_users.png)

---

## 12.5 Inserting Services

Insert screenshot inserting services.

![Insert Services](images/insert_services.png)

---

## 12.6 Displaying Tables in Database

Insert screenshot showing list of database tables.

![Database Tables](images/database_tables.png)

---

## 12.7 Displaying Users Table

Insert screenshot showing users table output.

![Users Table](images/users_table.png)

---

# 13. Outcome of the Project

As a result of this project:

- A structured system design for manicure appointment booking is created
- Business processes are clearly documented
- System requirements are identified and analyzed
- System models and diagrams support the proposed architecture
- The project demonstrates practical application of System Analysis and Design principles

---

# 14. Conclusion

The Manicure Appointment Booking System project demonstrates how structured system analysis and design can improve appointment scheduling processes in beauty salons.

By applying system analysis methodologies, the project identifies user needs, defines system processes, and develops a clear system architecture.

The design improves scheduling organization, reduces booking conflicts, and enhances customer experience.

---

# 15. References

- System Analysis and Design course materials
- https://www.w3schools.com
- https://www.programiz.com
- https://www.diagrams.net
