Student Data Organizer

A simple Python menu-driven program for managing student information. The program allows users to add, display, update, delete student records, and view all subjects offered.

Features

The Student Data Organizer provides the following options:

Add Student – Add a new student's information.
Display All Students – Display all stored student records.
Update Student Information – Update a student's age and grade using their Student ID.
Delete Student – Delete a student record using their Student ID.
Display Subjects Offered – Display all unique subjects offered by the students.
Exit – Exit the program.
Data Structures Used

This project demonstrates the use of different Python data structures:

List – Used to store all student records.
Dictionary – Used to store individual student information.
Tuple – Used to store the Student ID and Date of Birth.
Set – Used to store subjects and automatically remove duplicate subjects.
Student Record Structure

Each student is stored as a dictionary:

student = {
    "info": (id, dob),
    "name": name,
    "age": age,
    "grade": grade,
    "subjects": subjects
}

Requirements
Python 3.x

No external libraries are required.

How to Run
Make sure Python 3 is installed on your computer.
Save the program as:
student_data_organizer.py

Open a terminal or command prompt in the project directory.
Run the program:
python student_data_organizer.py

How to Use

After running the program, the following menu will appear:

1. Add Student
2. Display All Students
3. Update Student Information
4. Delete Student
5. Display Subjects offered
6. Exit


Enter the number corresponding to the operation you want to perform.

Example: Adding a Student
Enter choice: 1
Student ID: 101
Name: Rahul
Age: 16
Grade: 10
Date of Birth: 15-08-2010
Subjects: Math,Science,English

Student added!

Example: Displaying Students
--- All Students ---

ID: 101, Name: Rahul, Age: 16, Grade: 10,
Subjects: {'Math', 'Science', 'English'}, DOB: 15-08-2010

Example: Displaying Subjects
Subjects Offered:

Math
Science
English

Program Flow
Start
  |
  v
Display Menu
  |
  +----> 1. Add Student
  |
  +----> 2. Display Students
  |
  +----> 3. Update Student
  |
  +----> 4. Delete Student
  |
  +----> 5. Display Subjects
  |
  +----> 6. Exit
  |
  v
Repeat Until Exit

Important Notes
Student information is stored temporarily in memory.
The data will be lost when the program is closed.
Student IDs are used to identify students during update and delete operations.
Subjects are stored in a set, so duplicate subjects are automatically removed.
Future Improvements

Possible improvements include:

Add input validation.
Prevent duplicate Student IDs.
Allow updating the student's name, DOB, and subjects.
Save student data to a file or database.
Add a search student option.
Display students in a more organized table format.
Handle invalid menu choices without crashing.
License

This project is intended for educational and learning purposes.
