# Manicure Appointment Booking System

## Course
**Cap1: System Analysis and Design**

---

## Team Information

**Team Name:** Team 777

| Name | Student ID | Role | Responsibilities |
|-----|-----|-----|-----|
| Mariya Gorbacheva | 202490123 | Team Leader | Oversees the project, manages tasks, ensures deadlines are met |
| Karina Gumerova | 202490124 | System Analyst | Analyzes system requirements and identifies user needs |
| Maksim Em | 202490106 | System Designer | Designs system models, diagrams, and system structure |
| Diyorbek Voidjonov | 202490357 | Documentation Specialist | Prepares and maintains project documentation |

---

# Project Description

The **Manicure Appointment Booking System** is a digital platform designed to simplify and organize the process of scheduling manicure services in beauty salons.

Many salons currently rely on phone calls, social media messages, or manual notebooks to manage appointments. These traditional methods often cause scheduling conflicts, missed bookings, and inefficient time management.

The proposed system provides a centralized platform where customers can easily book manicure appointments while salon staff can manage schedules and monitor service availability.

---

# Key Features

- Customer appointment booking  
- Viewing available time slots  
- Appointment management by salon staff  
- Organized scheduling and record keeping  
- Basic customer information storage  

---

# Problem Statement

Many manicure salons still manage appointments manually using phone calls or messaging applications. This approach often leads to scheduling conflicts, double bookings, and difficulties in tracking appointments.

Without a structured system, salon administrators and specialists may struggle to manage time efficiently, which can negatively affect customer satisfaction and service quality.

---

# Project Objectives

- Analyze the current manicure appointment booking process  
- Identify system users and their needs  
- Define functional and non-functional requirements  
- Design a structured booking system  
- Apply System Analysis and Design methodologies  
- Improve scheduling efficiency and customer experience  

---

# System Scope

## System Includes

- Customer appointment booking  
- Viewing available manicure time slots  
- Appointment management by salon staff  
- Customer information management  
- Organized scheduling records  

## Limitations

- Online payments are not included  
- No real-time chat support  
- No automated reminders  
- No advanced analytics or reporting  
- Academic system design only (not commercial deployment)

---

# Expected Users

### Customers
- Book manicure appointments  
- View available time slots  

### Salon Administrators
- Manage appointment schedules  
- Monitor booking activity  

### Manicure Specialists
- View assigned appointments  
- Manage service availability  

### System Analysts / Academic Reviewers
- Evaluate system structure and documentation  

---

# Project Timeline

| Week | Activities |
|-----|-----|
| Week 1 | Problem identification and project planning |
| Week 2–3 | Requirement analysis and documentation |
| Week 4–5 | System modeling and design |
| Week 6–7 | Final documentation and project submission |

---

# Use Cases

## 1. Customer Books an Appointment

**Primary Actor:** Customer  
**Secondary Actors:** System, Salon Administrator  

### Main Flow

1. Customer logs into the system  
2. Opens appointment booking page  
3. System displays available time slots  
4. Customer selects date and time  
5. Customer confirms booking  
6. System validates request  
7. Appointment is saved in the database  

### Alternative Flow

- If time slot is already booked → error message  
- If customer is not logged in → redirect to login  

---

## 2. Salon Administrator Manages Appointments

**Primary Actor:** Administrator  

### Process

1. Administrator logs into system  
2. Opens appointment management panel  
3. Views scheduled appointments  
4. Edits or cancels appointments  

---

## 3. Specialist Views Schedule

**Primary Actor:** Manicure Specialist  

### Process

1. Specialist logs into system  
2. Opens schedule dashboard  
3. Views assigned appointments  

---

# System Architecture

```
User Management
        |
Appointment System
        |
Schedule Management
        |
SQL Database
```

---

# ERP System Modules

### User Management
- Registration
- Login
- Profile management

### Appointment Management
- Book appointment
- View appointments
- Cancel bookings

### Schedule Management
- Manage time slots
- Assign specialists
- Track daily schedules

---

# Database Design

The database stores information about:

- Users  
- Appointments  
- Schedules  

Relationships between tables ensure structured data storage and efficient appointment management.

---

# Project Outcome

- Structured system design created  
- Business processes documented  
- System requirements analyzed  
- System architecture developed  

---

# Conclusion

The Manicure Appointment Booking System demonstrates how structured system analysis can improve scheduling processes in beauty salons.

The design reduces booking conflicts, improves organization, and enhances customer experience.

---

# References

- System Analysis and Design course materials  
- https://www.w3schools.com  
- https://www.programiz.com  
- https://www.diagrams.net
