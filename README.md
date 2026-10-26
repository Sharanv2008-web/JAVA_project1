# KEC Student Academic & Continuous Evaluation System

### Development using Java JDBC and MySQL

A console-based Java application developed to manage student academic records, course enrollment, assessment marks, attendance, internal marks, and final results for the Kongu Engineering College (R2024) academic system project.

---

## 1. Project Overview

The **KEC Student Academic & Continuous Evaluation System** is a database-driven application developed using Java, JDBC, and MySQL. The system provides a simple way to store, retrieve, and manage student academic information through a terminal-based menu.

The project demonstrates Java database connectivity, SQL operations, object-oriented programming, and database management. It aims to reduce manual record management and improve the organization of academic information.

## 2. Objectives

- To maintain student details in a centralized database.
- To manage course information and student enrollment.
- To record and retrieve assessment marks.
- To calculate attendance percentages.
- To calculate internal marks based on configured assessment rules.
- To display student marks and final results.
- To demonstrate Java JDBC connectivity with MySQL.
- To provide a simple menu-driven interface for academic record management.

## 3. Technologies Used

| Technology | Purpose |
|---|---|
| Java | Application development |
| JDBC | Connecting Java with MySQL |
| MySQL Server | Storing academic records |
| MySQL Workbench | Creating and managing database tables |
| Eclipse IDE | Writing and executing Java programs |
| Windows Terminal | Running and testing the application |
| Git and GitHub | Version control and project hosting |

## 4. Main Features

### Student Management
- Add student records.
- Store student details in the database.
- Retrieve student information.

### Course Management
- Add course details.
- Maintain course information for academic records.

### Student Enrollment
- Enroll students in courses.
- Maintain student-course relationships.

### Assessment Marks
- Enter assessment marks.
- Store assessment information.
- Retrieve student marks.

### Attendance Management
- Update attendance records.
- Calculate attendance percentages.
- Identify students based on configured attendance thresholds.

### Internal Marks
- Calculate and display internal assessment marks using the implemented rules.

### Final Results
- Display student academic results.
- Combine available assessment information according to the implemented evaluation logic.

## 5. Database Design

The project uses the MySQL database `kec_academic`.

The main tables are:

| Table | Description |
|---|---|
| `students` | Stores student details |
| `courses` | Stores course information |
| `enrollments` | Maintains student enrollment in courses |
| `assessment_marks` | Stores assessment marks |

These tables help organize academic information and establish relationships between students, courses, enrollments, and assessments.

## 6. Application Menu

The application provides the following menu options:

1. Add Student
2. Add Course
3. Enroll Student
4. Add Assessment Marks
5. View Student Marks
6. Update Attendance
7. View Attendance Percentage
8. View Internal Marks
9. View Final Result
0. Exit

## 7. Project Structure

```text
KEC_Student_Academic/
│
├── src/
│   ├── DBConnection.java
│   ├── StudentDAO.java
│   ├── CourseDAO.java
│   ├── EnrollmentDAO.java
│   ├── AssessmentDAO.java
│   ├── ViewMarksDAO.java
│   ├── AttendanceDAO.java
│   ├── AttendancePercentageDAO.java
│   ├── InternalMarksDAO.java
│   ├── FinalResultDAO.java
│   └── MainMenu.java
│
├── bin/
├── .classpath
├── .project
├── .gitignore
└── README.md
```

*Note: The file list above describes the intended project organization. Adjust it if your actual source files differ.*

## 8. Requirements

Before running the project, install:

- Java Development Kit (JDK)
- MySQL Server
- MySQL Connector/J
- Eclipse IDE or another Java development environment
- Windows Terminal or Command Prompt

## 9. Database Configuration

1. Start the MySQL Server.
2. Open MySQL Workbench.
3. Create or select the database named `kec_academic`.
4. Create the required tables: `students`, `courses`, `enrollments`, and `assessment_marks`.
5. Open `DBConnection.java`.
6. Configure the database URL, username, and password for your local MySQL installation.
7. Ensure that the MySQL Connector/J library is included in the Java classpath.

**Security note:** Do not upload your real database password to GitHub. Use a local configuration or environment variable for credentials.

## 10. How to Run the Project

Open Command Prompt or Windows Terminal and navigate to the project directory.

```cmd
cd /d "C:\Users\pavit\eclipse-workspace\KEC_Student_Academic"
```

Compile the Java source files using the MySQL Connector/J library:

```cmd
javac -cp "C:\path\to\mysql-connector-j.jar" -d bin src\*.java
```

Replace `C:\path\to\mysql-connector-j.jar` with the actual path to your downloaded connector JAR file.

Run the application:

```cmd
java -cp "bin;C:\path\to\mysql-connector-j.jar" MainMenu
```

Make sure MySQL is running and the database connection settings are correct before starting the application.

## 11. Project Demo Video

The project demonstration video explains the application, its features, and the execution process.

**Video file:** `Video/project_explain.mp4`

[▶ View or download the project demonstration video](Video/project_explain.mp4)

The video demonstrates the terminal-based application and its main academic management operations.

## 12. Project Documentation

The complete project report contains the project explanation, objectives, procedure, database details, implementation information, screenshots, and results.

**Documentation file:** `Documents/JDBC Mini Project.docx`

[📄 View or download the project documentation](Documents/JDBC%20Mini%20Project.docx)

## 13. Expected Output

When the application runs successfully, the terminal displays the main menu. Users can select options to add students, add courses, enroll students, record assessment marks, update attendance, view internal marks, and display final results.

The application retrieves and updates information through JDBC connections to the MySQL database.

## 14. Advantages

- Centralized storage of academic information.
- Reduced manual record maintenance.
- Faster retrieval of student marks and attendance details.
- Organized course enrollment records.
- Practical demonstration of Java and database integration.
- Easier testing and maintenance of academic data.

## 15. Limitations

- The application uses a console-based interface.
- Database access requires a running MySQL Server.
- Results depend on the data entered and the evaluation rules implemented.
- The configured evaluation rules should not be assumed to represent official institutional regulations unless verified.

## 16. Future Enhancements

- Develop a graphical user interface or web application.
- Add student and administrator login.
- Introduce data validation and improved error handling.
- Generate downloadable academic reports.
- Add automated backups and improved security.
- Configure verified institutional grading and attendance rules.

## 17. Conclusion

The KEC Student Academic & Continuous Evaluation System was developed using Java JDBC and MySQL to manage student details, courses, enrollments, assessment marks, attendance, internal marks, and final results. The application demonstrates database connectivity and common database operations through a terminal-based menu. It provides a foundation for a more comprehensive academic record management system.

## 18. Repository

**GitHub Repository:**  
https://github.com/Sharanv2008-web/JAVA_project1

The repository contains the project source code and supporting materials, including the documentation and demonstration video.

---

**Developed as an academic mini project using Java JDBC and MySQL.**
