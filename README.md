# python-oops
Python-based Student Management System using OOP and CSV file handling to perform CRUD operations, manage student records, and calculate grades.
# Student Management System

## Overview
The Student Management System is a menu-driven Python application designed to manage student records efficiently. It uses Object-Oriented Programming (OOP) concepts and CSV file handling to store and manage student information.

## Features
- **Add Student:** Add new student records with ID, name, and marks.
- **View Students:** Display all registered student records with percentages and grades.
- **Search Student:** Find student details using their unique ID.
- **Update Student:** Modify existing student names and marks.
- **Delete Student:** Remove student records using their ID.
- **Grade Calculation:** Automatically calculate percentages and assign grades.
- **Duplicate ID Validation:** Prevent duplicate student IDs.
- **Data Storage:** Save student records permanently in a CSV file.

## Technologies Used
- Python
- CSV Module
- ABC Module
- Object-Oriented Programming (OOP)

## OOP Concepts Used
- **Abstraction:** Uses an abstract Student class with an abstract get_grade() method.
- **Inheritance:** RegularStudent inherits from the Student class.
- **Encapsulation:** Student details are managed through class attributes and methods.
- **Polymorphism:** The get_grade() method provides grade calculation through the student class hierarchy.

## Grading System

| Percentage | Grade |
|---|---|
| 90% and above | A |
| 75% – 89% | B |
| 50% – 74% | C |
| Below 50% | Fail |

## Project Structure

```text
Student-Management-System/
│
├── oops.py
├── students.csv
└── README.md
```

## How to Run

1. Install Python on your system.
2. Clone or download this repository.
3. Open the project folder in VS Code.
4. Run the following command:

```bash
python oops.py
```

5. Choose an option from the menu to manage student records.

## CSV File
The `students.csv` file stores student information in the following format:

| ID | Name | Marks |
|---|---|---|
| 101 | Rahul | 450 |
| 102 | Priya | 380 |

## Future Enhancements
- Add student attendance management.
- Generate student performance reports.
- Add a graphical user interface (GUI).
- Export student reports.

## Author
**Sakshi Shimpi**
