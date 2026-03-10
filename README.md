Manicure Appointment Booking System
1. Course Name
Cap1: System Analysis and Design
________________________________________
2. Team Information
Team Name: Team 777
Name	Student ID	Role	Responsibilities
Mariya Gorbacheva	202490123	Team Leader	Oversees the project, manages tasks, ensures deadlines are met
Karina Gumerova	202490124	System Analyst	Analyzes system requirements and identifies user needs
Maksim Em	202490106	System Designer	Designs system models, diagrams, and system structure
Diyorbek Voidjonov	202490357	Documentation Specialist	Prepares and maintains project documentation
________________________________________
3. Project Title and Description
The Manicure Appointment Booking System is a digital platform designed to simplify and organize the process of scheduling manicure services in beauty salons. Many salons currently rely on phone calls, social media messages, or manual notebooks to manage appointments. These traditional methods often cause scheduling conflicts, missed bookings, and inefficient time management.
The proposed system provides a centralized platform where customers can easily book manicure appointments while salon staff can manage schedules and monitor service availability.
The system is designed to organize appointment information, customer data, and scheduling records in a structured manner.
Key Features and System Processes
●	Customer appointment booking
●	Viewing available time slots
●	Appointment management by salon staff
●	Organized scheduling and record keeping
●	Basic customer information storage
________________________________________
4. Problem Statement
Many manicure salons still manage appointments manually using phone calls or messaging applications. This approach often leads to scheduling conflicts, double bookings, and difficulties in tracking appointments.
Without a structured system, salon administrators and specialists may struggle to manage time efficiently, which can negatively affect customer satisfaction and service quality. Therefore, there is a need for a properly analyzed and designed booking system that improves scheduling accuracy and overall salon management.
________________________________________
5. Project Objectives
The main objectives of this project are:
●	To analyze the current manicure appointment booking process
●	To identify system users and their needs
●	To define functional and non-functional requirements
●	To design a structured manicure appointment booking system
●	To apply System Analysis and Design methodologies
●	To improve scheduling efficiency and customer experience
________________________________________
6. Scope of the System
The project focuses on the analysis and design stage of the system.
The system includes:
●	Customer appointment booking
●	Viewing available manicure time slots
●	Appointment management by salon staff
●	Customer information management
●	Organized scheduling records
System Limitations
The system has the following limitations:
●	Online payments are not included
●	Real-time chat between customers and staff is not supported
●	The system does not include automated reminders
●	Advanced analytics and reporting are not implemented
●	The project focuses on academic system analysis and design rather than full commercial deployment
________________________________________
7. Expected Users
The system is designed for the following users:
Customers
●	Book manicure appointments
●	View available time slots
Salon Administrators
●	Manage appointment schedules
●	Monitor booking activity
Manicure Specialists
●	View assigned appointments
●	Manage service availability
System Analysts and Academic Reviewers
●	Evaluate system structure and documentation
________________________________________
8. Project Timeline (7 Weeks)
Week	Activities
Week 1 (02 Feb – 09 Feb)	Problem identification and project planning
Week 2–3 (09 Feb – 23 Feb)	Requirement analysis and documentation
Week 4–5 (23 Feb – 02 Mar)	System modeling and design
Week 6–7 (02 Mar – 13 Mar)	Final documentation and project submission
________________________________________
9. Use Case Documentation
Use Case 1: Customer Books an Appointment
Primary Actor: Customer
Secondary Actors: System, Salon Administrator
Description
This use case describes the process of a customer booking a manicure appointment through the system.
Preconditions
●	Customer must be registered in the system
●	Customer must be logged in
●	Available time slots must exist
Main Flow
1.	Customer logs into the system.
2.	Customer opens the appointment booking page.
3.	System displays available manicure time slots.
4.	Customer selects a preferred date and time.
5.	Customer confirms the booking.
6.	System validates the request.
7.	System saves the appointment in the database.
8.	Appointment becomes visible to salon staff.
Alternative Flow
●	If the selected time slot is already booked → system shows an error message.
●	If the customer is not logged in → system redirects to login page.
Postconditions
●	Appointment is stored in the database.
●	Appointment appears in the salon schedule.
________________________________________
Use Case 2: Salon Administrator Manages Appointments
Primary Actor: Salon Administrator
Secondary Actors: System
Description
This use case describes how salon administrators view and manage customer appointments.
Preconditions
●	Administrator must be logged in.
Main Flow
1.	Administrator logs into the system.
2.	Administrator opens the appointment management panel.
3.	System displays a list of all scheduled appointments.
4.	Administrator can view, edit, or cancel appointments.
5.	System updates the appointment information.
Postconditions
●	Updated appointment data is stored in the system.
________________________________________
Use Case 3: Specialist Views Schedule
Primary Actor: Manicure Specialist
Secondary Actors: System
Description
This use case describes how manicure specialists view their daily schedule.
Preconditions
●	Specialist must be registered in the system
●	Specialist must be logged in
Main Flow
1.	Specialist logs into the system.
2.	Specialist opens the schedule dashboard.
3.	System displays a list of appointments assigned to the specialist.
4.	Specialist reviews appointment details.
Postconditions
●	Specialist has access to organized appointment information.
________________________________________
Use Case Summary Table
Use Case	Primary Actor	Main Outcome
Book Appointment	Customer	Appointment created
Manage Appointments	Administrator	Appointment updated
View Schedule	Specialist	Schedule displayed
________________________________________

 
10. Business Process Model (BPM)
The Business Process Model helps to visualize the workflow of the manicure appointment booking system.
It helps to:
●	Identify system actors
●	Define system processes
●	Organize workflow logic
●	Support system design decisions
BPM Diagram
 
 
 
   
________________________________________
11. Enterprise Resource Planning (ERP) System Design
The ERP design represents the overall architecture of the system and its main modules.
The system uses a modular structure where all components are connected through a centralized database.
1. User Management Module
Functions:
●	Customer registration
●	Login authentication
●	User profile management
2. Appointment Management Module
Functions:
●	Book appointment
●	View appointments
●	Cancel or edit bookings
3. Schedule Management Module
Functions:
●	Manage available time slots
●	Assign specialists to appointments
●	Track daily schedules
System Architecture Diagram
      ┌─────────────────────┐
      │   User Management   │
      └─────────┬───────────┘
                │
      ┌─────────▼───────────┐
      │ Appointment System  │
      └─────────┬───────────┘
                │
      ┌─────────▼───────────┐
      │ Schedule Management │
      └─────────┬───────────┘
                │
      ┌─────────▼───────────┐
      │     SQL Database    │
      └─────────────────────┘
________________________________________
12. Database Design and SQL Implementation
The system database stores information about users, appointments, and schedules.
Relationships between tables ensure structured data storage and efficient retrieval of appointment information.
 
 
 
 
 
 
 
________________________________________
13. Outcome of the Project
As a result of this project:
●	A structured system design for manicure appointment booking is created
●	Business processes are clearly documented
●	System requirements are identified and analyzed
●	System models and diagrams support the proposed architecture
●	The project demonstrates practical application of System Analysis and Design principles
________________________________________
14. Conclusion
The Manicure Appointment Booking System project demonstrates how structured system analysis and design can improve appointment scheduling processes in beauty salons.
By applying system analysis methodologies, the project identifies user needs, defines system processes, and develops a clear system architecture. The design improves scheduling organization, reduces booking conflicts, and enhances customer experience.
Overall, the project illustrates how proper system planning and documentation contribute to the development of efficient digital service platforms.
________________________________________
15. References
The following resources were used during the development of this project:
System Analysis and Design course materials
W3Schools – https://www.w3schools.com
Programiz – https://www.programiz.com
Draw.io (Diagrams.net) – https://www.diagrams.net

