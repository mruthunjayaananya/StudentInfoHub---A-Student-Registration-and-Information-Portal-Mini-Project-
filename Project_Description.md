# Student Registration and Information System

This is a web-based Student Registration and Information System developed using Core Java, Hibernate, Servlets, and Maven. It allows users to register students, store their data in a MySQL database, and view the registered records. The frontend is built using HTML, CSS, Bootstrap, and JavaScript, making the application responsive and user-friendly.

## Features

- Student registration form  
- Save and manage student data using Hibernate ORM  
- Display all registered students in a table  
- Responsive UI using Bootstrap  
- Maven-based project structure for dependency management  

## Tech Stack

| Layer       | Technologies Used               |
|-------------|----------------------------------|
| Frontend    | HTML, CSS, Bootstrap, JavaScript |
| Backend     | Core Java, Servlets, Hibernate   |
| Database    | MySQL                            |
| Build Tool  | Maven                            |
| Server      | Apache Tomcat                    |
| IDE         | Eclipse or IntelliJ IDEA         |

## Database Structure (MySQL)

```sql
CREATE DATABASE studentdb;

USE studentdb;

##Project Structure

StudentInfoProject/
├── src/
│   └── com/student/
│       ├── SaveRecord.java
│       ├── DisplayRecord.java
│       └── Student.java
├── WebContent/
│   ├── register.jsp
│   ├── disp.jsp
│   └── css/
│       └── style.css
├── pom.xml
└── web.xml

How to Run

1. Clone this repository:
git clone https://github.com/your-username/student-info-system.git
2. Import the project as a Maven Project in your IDE.
3. Configure your MySQL credentials in hibernate.cfg.xml.
4. Ensure MySQL is running and the studentdb database is created.
5. Deploy the project to Apache Tomcat.
6. Access the application at:
http://localhost:8080/StudentInfoProject/register.jsp

## Future Enhancements
Add update and delete functionality

Add login and role-based access control

Implement search and filter options

Export student data to PDF or Excel

Add client-side form validations
