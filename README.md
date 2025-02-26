# Online Mentoring Management System

## Overview
The **Online Mentoring Management System** is a web-based application designed to efficiently manage and streamline mentoring activities. It facilitates seamless communication between administrators, mentors, and mentees, ensuring an organized mentoring process.

## Features

### 1. Admin Module
- Manage user details, including administrators, mentors, and mentees.
- Add, modify, or delete mentor and mentee records.
- Assign mentees to mentors based on predefined criteria.
- Monitor mentoring activities, including submitted reports and mentee queries.

### 2. Mentor Module
- Submit periodic reports on mentees’ progress.
- Provide guidance and feedback to assigned mentees.
- Respond to mentee queries through the platform.
- Track the performance of assigned mentees over time.

### 3. Mentee Module
- View mentor reports related to their progress.
- Ask questions or seek clarifications from mentors.
- Receive guidance and personalized feedback based on their queries.

### 4. Communication and Coordination
- Seamless interaction between mentors and mentees.
- Admin moderation ensures structured mentoring activities.
- Maintains a centralized database of mentor-mentee interactions.

## Technologies Used

### Frontend
- **HTML** – Structure of web pages.
- **CSS** – Styling and layout.
- **JavaScript** – Client-side interactivity.

### Backend
- **Java (JDK 8 or later)** – Core backend logic.
- **Servlets** – Handling server-side processing and requests.

### Database & Server
- **MySQL** – Database management.
- **Apache Tomcat** – Web server for deploying the application.
- **JDBC (Java Database Connectivity)** – Connecting Java with MySQL.

## System Requirements
To set up and run the **Online Mentoring Management System**, ensure you have:

- **Java Development Kit (JDK) 8 or later**
- **Apache Tomcat Server** (for deployment)
- **MySQL Server** (for database storage)
- A modern web browser (**Google Chrome, Firefox, Edge, etc.**)

## Installation & Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Renu-telugu/Online-Mentoring-Management-System.git
   ```
2. **Import the project into your IDE** (e.g., Eclipse or IntelliJ IDEA).
3. **Configure the database:**
   - Create a MySQL database named `mentoring_system`.
   - Import the provided SQL scripts from the `database` folder to set up the tables and data.
   - Update the database connection details in the JDBC configuration files.
4. **Compile and run the project:**
   ```bash
   javac -d build/classes src/main/java/com/app/*.java
   ```
5. **Deploy on Apache Tomcat:**
   - Place the WAR file in the Tomcat `webapps` directory.
   - Start Tomcat and access the application via `http://localhost:8080/OnlineMentoringSystem/`

## How It Works
- **Admins:** Manage users, including mentors and mentees, by adding or modifying details.
- **Mentors:** Submit periodic reports, answer queries from mentees, and provide personalized feedback.
- **Mentees:** View reports submitted by mentors and ask queries to seek guidance.

## Folder Structure
```
OnlineMentoringSystem/
│── src/
│   ├── main/
│   │   ├── java/com/app/  # Java source files
│   │   ├── webapp/        # HTML, CSS, and JavaScript files
│── build/
│   ├── classes/           # Compiled Java classes
│── database/              # SQL scripts to set up the MySQL database
```
