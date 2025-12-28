Laboratory Equipment & Management System
Project Name:       PROPER USE OF LABRORATORY EQUIPMENT Package: project16 Language: Java

📖 Project Overview
This project is a modular Java application designed to manage the day-to-day operations of a university Chemistry Laboratory. It assists students and staff with equipment selection, chemical inventory management, scheduling, course information, and student validation. The system promotes laboratory safety and logistical efficiency.

🚀 Key Features & Modules
The project consists of six distinct modules, each handling a specific aspect of laboratory management:

1. Equipment Selection System (electionApp.java)
Function: Allows users to select specific laboratory apparatus sets based on their experiment needs.

Sets Available: Titration, TLC (Thin Layer Chromatography), and Analysis sets.

Details: Displays the specific tools included in the kit (e.g., Burettes, Pipettes) and the physical location of the kit in the lab.

2. Chemical Inventory Manager (ChemicalDetails.java)
Function: A database tool to check the details and safety of chemical substances.

Features: Categorizes chemicals as Acid, Base, or Neutral. It provides the Chemical ID and vital Expiry Date information to ensure safety.

Supported Chemicals: HCL, H2SO4, NaOH, KOH, Table Salt, Distilled Water, etc..

3. Student Verification (Main.java)
Function: Validates student access to the laboratory system.

Logic: Checks input against a database of valid Student IDs (e.g., "2021/002"). If valid, it returns the student's current Year of Study.

4. Lab Scheduler (LabSchedule.java)
Function: Manages the weekly timetable for practical sessions.

Logic: Users select a day (Monday, Tuesday, or Wednesday), and the system retrieves the specific student group (e.g., "PS Student"), course name, and time slot.

5. Course Information System (CourseSelectionApp.java)
Function: Provides detailed descriptions of available academic tracks.

Courses: Physical Science, Biological Science, Applied Chemistry, and Environmental Management.

Details: Information includes the course description, safety privileges (guidance requirements), and the relevant office location.

6. Tutor Selector (TutorSelection.java)
Function: A utility to view available teaching assistants and select a tutor for the session.

🛠️ Technical Concepts Used
This project demonstrates core Object-Oriented Programming (OOP) principles:

Inheritance: Used in electionApp.java (extending Chemicalet) and CourseSelectionApp.java (extending Course) to share attributes like location and descriptions.

Polymorphism & Abstraction: Used in ChemicalDetails.java via the abstract Chemical class and its subclasses (Acid, Base, Neutral).

Data Structures: Extensive use of HashMap for efficient lookups of student IDs, schedules, and chemical inventories.

Encapsulation: Used in StudentNumber class to protect student data.

