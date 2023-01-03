INTRODUCTION:
E-Learning System is a desktop-based Windows application developed in Java with Swing and AWT. This project aims at serving Students and Teachers in Online based learning. Admins can add subjects, Teachers can add courses in a particular subject and Students can Enroll courses and study them, and also Students can message other participants in a particular course except the Teacher teaching that course.

Hardware and software tools:
The system services and goals are established by consultation with system user. They are then defined in details and serve as a system specification. System requirement are those on which the system runs.


⚙️ Hardware Requirements:

Computer with either Intel Pentium processor or AMD processor.
1GB+ DDR RAM
1GB hard disk drive
💻 Software Requirements:

Windows Operating system.
JRE and JDK.
MySQL server (WAMP)
DESIGN
Database Design is a collection of processes that facilitate the designing, development, implementation and maintenance of enterprise data management systems.
It helps produce database systems:

That meet the requirements of the users
Have high performance.
Architecture Description
The design of a DBMS depends on its architecture. It can be centralized or decentralized or hierarchical. The architecture of a DBMS can be seen as either single tier or multi-tier.

ER Diagram image.png

Fig 1: ER Diagram

An entity–relationship model describes interrelated things of interest in a specific domain of knowledge (Refer Fig 1). It is composed of entity types and specifies relationships that can exist between instances of those entity types.

Relational Schema Diagram

image_1.png

Fig 2: Relational Schema

Relational schema is a collection of meta-data. Database schema describes the structure and constraints of data representing in a particular domain (Refer Fig 2).

IMPLEMENTATION
Description on Implementation
The goal of this application is to manage the Students, Teachers, Courses and various functions of E-Learning System.

List of modules with use cases:
This Java project consists of 3 major modules

Admin
Admin Login with Username & Password
View Profile
View Account Information
Delete Account
Manage Account (Change email, change name, change profile, change password)
Admin Adds Subject
Admin Deletes Subject
View All Teachers Details and Delete Teacher
View All Students Details and Delete Student
View All Courses Details
Add New Admin
Logout
Teacher
Signup
Teacher Login with Username & Password
View Profile
View Account Information
Delete Account
Manage Account (Change email, change name, change profile, change password)
Teacher Adds Course
View My Students in a Particular course.
View My Courses
Update My Course
Logout
Student
Signup
Student Login with Username & Password
View Profile
View Account Information
Delete Account
Manage Account (Change email, change name, change profile, change password)
Student Enrols Courses
Student Study Courses
Student Withdraw Courses
Student Views Participants in a particular course.
Student can Message any participant in a particular course except Teacher.
Logout
