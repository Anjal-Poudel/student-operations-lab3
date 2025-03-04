# student-operations-lab3
# Student Management System

## Overview
This is a simple Java-based Student Management System that allows users to perform CRUD (Create, Read, Update, Delete) operations on student data. The system uses an `ArrayList` to store student information and provides an interactive command-line interface to manage student records.

## Features
- Add a new student
- Display all students
- Update student details
- Remove a student
- Exit the program

## Technologies Used
- Java
- Object-Oriented Programming (OOP) concepts
- Collections (ArrayList)
- Scanner for user input

## File Structure
- `Main.java` - Contains the main method and user interaction logic.
- `Student.java` - Defines the `Student` class with attributes and methods.
- `StudentOps.java` - Handles CRUD operations on student records.

## How to Run
1. Ensure you have Java installed on your system.
2. Compile all Java files:
   ```sh
   javac Main.java Student.java StudentOps.java
   ```
3. Run the program:
   ```sh
   java Main
   ```

## Usage
When you run the program, you will be presented with a menu:
```
Choose an option:
1. Add Student
2. Display Students
3. Update Student
4. Remove Student
5. Exit
```

Follow the on-screen instructions to perform operations.

## Example
### Adding a Student
```
Enter Name: John Doe
Enter PRN: 123456789
Enter GPA: 3.8
Enter Batch: 2023-2027
Enter Branch: AIML
Student Added Successfully
```

### Displaying Students
```
The Name of Student is: John Doe
The Prn of Student is: 123456789
The GPA of Student is: 3.8
The Batch of Student is: 2023-2027
The Branch of Student is: AIML
```

