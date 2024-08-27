# Prerequisites

# Python Installation:
Make sure you have Python installed on your system. You can download Python from the official website.
Verify the installation by opening a terminal or command prompt and running:
python --version
or
python3 --version

# Basic Understanding of Python:
Familiarize yourself with basic Python concepts such as classes, methods, and handling user input if you’re not already comfortable with them.

# IDE or Text Editor:
Use an IDE (like PyCharm, VSCode) or a simple text editor (like Notepad++, Sublime Text) to edit and run the Python code.

# Steps to Run the Code

Create a Python File:
Open your text editor or IDE.
Copy the provided code into a new file.
Save the file with a .py extension, e.g., student_management_system.py.

# Run the Python Script:
Open a terminal or command prompt.
Navigate to the directory where you saved your Python file.

# Execute the script using Python by running:
python student_management_system.py
or
python3 student_management_system.py

# Interacting with the System:
After running the script, you should see the menu of the Student Management System displayed in the terminal.
Follow the prompts to add, remove, update, or display students.

Example Commands
Here’s a step-by-step example of what you might see and how you might interact with the system:

# Start the Script:
python student_management_system.py

# Menu Options:

# Student Management System Menu
1. Add New Student
2. Remove Student
3. Update Student Info
4. Show All Students
5. Exit
   
# Adding a New Student:
Enter 1 to add a new student.
Input the student ID, name, age, and major as prompted.

# Removing a Student:
Enter 2 to remove a student.
Provide the student ID of the student you want to remove.

# Updating Student Information:
Enter 3 to update student info.
Provide the student ID and the new details (or leave them blank if no change).

# Displaying All Students:
Enter 4 to display all students in the database.

# Exiting the Program:
Enter 5 to exit the system.

# Troubleshooting
Syntax Errors: If you encounter any syntax errors, ensure that the code is copied correctly and matches the formatting of the provided code.
Python Version Compatibility: Make sure you're using a compatible Python version (Python 3.x). The code may not work with Python 2.x.
Input Validation: The code assumes valid input. Adding more comprehensive input validation can make the script more robust.


# Code Changes Documentation
Student Class:

Attributes: id, name, age, major
Methods:
__init__(self, student_id, name, age, major): Initializes a student object.
update(self, name=None, age=None, major=None): Updates student details.
display(self): Displays student details.
StudentDatabase Class:

# Attributes: students (dictionary)
Methods:
__init__(self): Initializes the database with an empty dictionary.
add_student(self, student): Adds a student to the database.
remove_student(self, student_id): Removes a student from the database by ID.
update_student(self, student_id, name=None, age=None, major=None): Updates a student's information.
display_all_students(self): Displays all students in the database.
StudentManagementSystem Class:

# Attributes: database (instance of StudentDatabase)
Methods:
__init__(self, database): Initializes the management system with a database.
show_menu(self): Displays the menu and handles user input.
add_new_student(self): Handles adding a new student.
delete_student(self): Handles removing a student.
update_student_info(self): Handles updating student information.
