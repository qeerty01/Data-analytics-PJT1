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

# 9. Use Case 1: Customer Books an Appointment

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

# 10. Use Case 2: Administrator Manages Appointments

Primary Actor: Administrator

1. Administrator logs into system
2. Opens appointment management panel
3. Views scheduled appointments
4. Edits or cancels bookings

---
# 11. Use Case 3: Specialist Views Schedule

**Primary Actor:** Manicure Specialist  
**Secondary Actors:** System  

## Description
This use case describes how manicure specialists view their daily schedule.

## Preconditions
- Specialist must be registered in the system
- Specialist must be logged in

## Main Flow
1. Specialist logs into the system.
2. Specialist opens the schedule dashboard.
3. System displays a list of appointments assigned to the specialist.
4. Specialist reviews appointment details.

## Postconditions
- Specialist has access to organized appointment information.

---

# 12. Use Case Summary Table

| Use Case | Primary Actor | Main Outcome |
|--------|--------|--------|
| Book Appointment | Customer | Appointment created |
| Manage Appointments | Administrator | Appointment updated |
| View Schedule | Specialist | Schedule displayed |
<img width="623" height="278" alt="image" src="https://github.com/user-attachments/assets/76a32ecb-bf56-41a0-8753-859d6444311e" />

## 13. Business Process Model (BPM)

The Business Process Model helps to visualize the workflow of the manicure appointment booking system.  

It helps to:  
- Identify system actors  
- Define system processes  
- Organize workflow logic  
- Support system design decisions  

### BPM Diagram
<img width="602" height="112" alt="image" src="https://github.com/user-attachments/assets/f9b535bc-8f6b-47fd-8105-66cc4ebf2d8e" />
<img width="602" height="111" alt="image" src="https://github.com/user-attachments/assets/9a993569-098c-4252-9737-2ca2edb00a2d" />
<img width="602" height="127" alt="image" src="https://github.com/user-attachments/assets/dc179ffc-948b-4ed1-8e42-a3b6a2748238" />
<img width="190" height="305" alt="image" src="https://github.com/user-attachments/assets/77b61675-bf2b-4572-b275-ca703a693c72" />
<img width="210" height="281" alt="image" src="https://github.com/user-attachments/assets/4fbf4a77-33a9-411f-bfff-73d9ebbcdd99" />
<img width="185" height="253" alt="image" src="https://github.com/user-attachments/assets/6ccfaa93-c0cc-49cd-94ab-d7b0663fa095" />

 ## 14. Enterprise Resource Planning (ERP) System Design

The ERP design represents the overall architecture of the system and its main modules.  
The system uses a modular structure where all components are connected through a centralized database.  

### 1. User Management Module
**Functions:**  
- Customer registration  
- Login authentication  
- User profile management  

### 2. Appointment Management Module
**Functions:**  
- Book appointment  
- View appointments  
- Cancel or edit bookings  

### 3. Schedule Management Module
**Functions:**  
- Manage available time slots  
- Assign specialists to appointments  
- Track daily schedules  

### System Architecture Diagram
<img width="219" height="297" alt="image" src="https://github.com/user-attachments/assets/eb375a41-7462-473b-9297-f5ab266f61f0" />

---

## 15. Database Design and SQL Implementation

The system database stores information about users, appointments, and schedules.  
Relationships between tables ensure structured data storage and efficient retrieval of appointment information.
 
 <img width="416" height="396" alt="image" src="https://github.com/user-attachments/assets/7a6ef615-1d0d-4056-a9ef-818919787b31" />
<img width="451" height="376" alt="image" src="https://github.com/user-attachments/assets/9531a446-b62e-48f4-bb1f-1267ae2d3381" />
<img width="390" height="376" alt="image" src="https://github.com/user-attachments/assets/47c8720d-344f-4c76-b416-7b6e8b3e3c78" />
<img width="602" height="540" alt="image" src="https://github.com/user-attachments/assets/7a76aff1-60cb-4bc9-9ec9-06314b54e7b1" />
<img width="468" height="295" alt="image" src="https://github.com/user-attachments/assets/c313ce77-819d-409c-a146-c6cc1e2710bf" />


<img width="255" height="220" alt="image" src="https://github.com/user-attachments/assets/4d1fe397-2581-4be8-8e91-f747989855b3" />
<img width="602" height="339" alt="image" src="https://github.com/user-attachments/assets/0f1bf5d7-0c23-4356-9c24-7a2fdc999a33" />


## 16. Outcome of the Project

As a result of this project:  
- A structured system design for manicure appointment booking is created  
- Business processes are clearly documented  
- System requirements are identified and analyzed  
- System models and diagrams support the proposed architecture  
- The project demonstrates practical application of System Analysis and Design principles  

---

## 17. Conclusion

The Manicure Appointment Booking System project demonstrates how structured system analysis and design can improve appointment scheduling processes in beauty salons.  

By applying system analysis methodologies, the project identifies user needs, defines system processes, and develops a clear system architecture. The design improves scheduling organization, reduces booking conflicts, and enhances customer experience.  

Overall, the project illustrates how proper system planning and documentation contribute to the development of efficient digital service platforms.  

---

## 18. References

The following resources were used during the development of this project:  
- System Analysis and Design course materials  
- [W3Schools](https://www.w3schools.com)  
- [Programiz](https://www.programiz.com)  
- [Draw.io (Diagrams.net)](https://www.diagrams.net)
