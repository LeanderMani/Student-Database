Student Data Management System

A Java Swing-based GUI application for managing student records with MySQL database integration. This application allows users to add, update, delete, and search student records efficiently through a simple and intuitive interface.

Features
•	Add New Student: Insert new records into the database with USN, Name, Branch, and Semester.
•	Update Student Details: Modify existing student information using USN as the identifier.
•	Delete Student Records: Remove student data from the database.
•	Search Student: Quickly search for a student by USN, automatically populating their details in the form.
•	Reset and Exit: Clear form fields or close the application with confirmation.
•	Interactive GUI: User-friendly interface built with Java Swing components like JTextField, JTable, JPanel, and JButton.

Technologies Used
•	Java for GUI and application logic.
•	Java Swing for graphical interface.
•	MySQL as the database backend.
•	JDBC for database connectivity.

Improvements / Future Enhancements
•	Fetch and display all records from the database on startup.
•	Implement proper input validation to prevent SQL injection.
•	Separate database logic and GUI using MVC pattern.
•	Modernize JDBC driver usage (com.mysql.cj.jdbc.Driver).
