# KEC Student Academic & Continuous Evaluation System

### Development using Java JDBC and MySQL

A console-based Java application for managing student details, courses, enrollments, assessment marks, attendance, internal marks, and final results.

---

## 1. Project Resources

### 🎥 Project Demonstration Video

Watch the project demonstration to understand the application, its features, and how it runs in the terminal.

**[▶ Watch Project Demo Video](Video/project_explain.mp4)**

### 📄 Project Documentation

The complete project report includes the aim, objectives, procedure, database design, implementation details, output screenshots, and conclusion.

**[📄 View Project Documentation](Documents/JDBC%20Mini%20Project.docx)**

---

## 2. Project Overview

The **KEC Student Academic & Continuous Evaluation System** is developed using Java, JDBC, and MySQL to simplify the management of student academic records.

The application provides a menu-driven interface through which users can add student details, manage courses, enroll students, enter assessment marks, update attendance, calculate internal marks, and view final results.

This project demonstrates Java database connectivity, SQL operations, object-oriented programming, and relational database management.

## 3. Objectives

- To maintain student details in a centralized database.
- To manage course information and student enrollment.
- To record and retrieve assessment marks.
- To calculate and display attendance percentages.
- To calculate internal marks using the implemented evaluation rules.
- To display student academic performance and final results.
- To demonstrate database connectivity using Java JDBC and MySQL.
- To reduce manual work in academic record management.

## 4. Technologies Used

| Technology | Purpose |
|---|---|
| Java | Application development |
| JDBC | Java–MySQL connectivity |
| MySQL Server | Database management |
| MySQL Workbench | Database creation and administration |
| Eclipse IDE | Java coding and execution |
| Windows Terminal | Running and testing the application |
| Git and GitHub | Version control and project hosting |

## 5. Main Features

### Student Management
- Add student details.
- Store and retrieve student records.

### Course Management
- Add courses and maintain course information.

### Student Enrollment
- Enroll students in courses.
- Maintain student-course relationships.

### Assessment Marks
- Enter assessment marks.
- Store and retrieve marks from the database.

### Attendance Management
- Update attendance records.
- Calculate attendance percentages.
- Identify students based on configured attendance thresholds.

### Internal Marks
- Calculate and display internal marks according to the implemented rules.

### Final Results
- Display student academic results.
- Evaluate results based on the configured assessment logic.

## 6. Application Menu

The application provides the following console menu:

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

## 7. Database Design

The project uses a MySQL database named `kec_academic`.

The main database tables are:

| Table | Description |
|---|---|
| `students` | Stores student details |
| `courses` | Stores course information |
| `enrollments` | Maintains student enrollment records |
| `assessment_marks` | Stores assessment marks |

These tables organize academic information and maintain relationships between students, courses, enrollments, and assessment records.

## 8. Project Structure

```text
JAVA_project1/
│
├── KEC_Student_Academic/
│   ├── src/
│   │   ├── DBConnection.java
│   │   ├── StudentDAO.java
│   │   ├── CourseDAO.java
│   │   ├── EnrollmentDAO.java
│   │   ├── AssessmentDAO.java
│   │   ├── ViewMarksDAO.java
│   │   ├── AttendanceDAO.java
│   │   ├── AttendancePercentageDAO.java
│   │   ├── InternalMarksDAO.java
│   │   ├── FinalResultDAO.java
│   │   └── MainMenu.java
│   ├── bin/
│   ├── .classpath
│   ├── .project
│   └── README.md
│
├── Documents/
│   └── JDBC Mini Project.docx
│
├── Video/
│   └── project_explain.mp4
│
└── README.md
```

*Note: This is the intended folder structure. Adjust the file names or locations if your actual repository differs.*

## 9. System Requirements

The following software is required to run the project:

- Java Development Kit (JDK)
- MySQL Server
- MySQL Connector/J
- Eclipse IDE or another Java development environment
- Windows Terminal or Command Prompt

## 10. Database Configuration

1. Start the MySQL Server.
2. Open MySQL Workbench.
3. Create or select the database `kec_academic`.
4. Create the required tables: `students`, `courses`, `enrollments`, and `assessment_marks`.
5. Open `DBConnection.java` in the Java project.
6. Configure the database URL, username, and password for your local MySQL installation.
7. Add the MySQL Connector/J JAR file to the Java project's classpath.

**Security:** Never upload your actual database password to GitHub. Use a local configuration or environment variable to store credentials.

## 11. How to Run the Project

### Step 1: Open the project directory

Open Command Prompt or Windows Terminal and execute:

```cmd
cd /d "C:\Users\pavit\eclipse-workspace\KEC_Student_Academic"
```

### Step 2: Compile the Java files

Replace the example JAR path below with the actual location of your MySQL Connector/J file.

```cmd
javac -cp "C:\path\to\mysql-connector-j.jar" -d bin src\*.java
```

### Step 3: Run the application

```cmd
java -cp "bin;C:\path\to\mysql-connector-j.jar" MainMenu
```

Ensure that MySQL Server is running and the database credentials are correct before executing the application.

## 12. Expected Output

When the application executes successfully, the terminal displays the main menu. Users can select the required options to manage students, courses, enrollments, assessment marks, attendance, internal marks, and final results.

The application communicates with MySQL through JDBC to insert, update, and retrieve academic records.

## 13. Advantages

- Centralized academic record management.
- Reduced manual data entry and record maintenance.
- Faster retrieval of student information.
- Organized course enrollment and assessment records.
- Improved accessibility of attendance and marks information.
- Practical demonstration of Java database connectivity.

## 14. Limitations

- The application uses a console-based interface.
- MySQL Server must be available for database operations.
- Results depend on the entered data and implemented evaluation rules.
- Institutional grading and attendance rules should be verified before real-world use.

## 15. Future Enhancements

- Develop a graphical user interface or web application.
- Add student and administrator authentication.
- Generate downloadable academic reports.
- Improve input validation and error handling.
- Add secure user roles and access control.
- Implement verified institutional grading rules.

## 16. Conclusion

The KEC Student Academic & Continuous Evaluation System was developed using Java JDBC and MySQL to manage student details, courses, enrollments, assessment marks, attendance, internal marks, and final results. The application demonstrates database connectivity and academic record management through a terminal-based menu. It provides a foundation for future improvements to academic information management.

## 17. GitHub Repository

**Repository:** [JAVA_project1 on GitHub](https://github.com/Sharanv2008-web/JAVA_project1)

The repository is intended to contain the Java source code, project report, demonstration video, and supporting files.

---

**Developed as an academic mini project using Java JDBC and MySQL.**
