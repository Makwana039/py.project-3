# py.project-3

# Student Data Organisation

A simple Python console-based application to manage student records. This project demonstrates the use of Python data structures such as **lists**, **tuples**, **dictionaries**, and **sets** along with loops, conditional statements, and string formatting.

---

## Features

- Add a new student
- Display all student records
- Update student details
- Delete a student record
- Display unique subjects
- Menu-driven interface
- Exit the program

---

## Technologies Used

- Python 3.x

---

## Data Structures Used

| Data Structure | Purpose |
|---------------|---------|
| List | Stores all student records |
| Dictionary | Stores individual student information |
| Tuple | Stores Student ID and Date of Birth |
| Set | Stores unique subjects |

---

## Menu

```
======|MENU|======
1. Add Student
2. Display All Students
3. Update Student
4. Delete Student
5. Display Unique Subject
6. Exit
```

---

## Sample Output

```
=========|WELCOME TO STUDENT DATA ORGANISATION|=========
This program helps you manage student records efficiently.

======|MENU|======
1. Add Student
2. Display All Students
3. Update Student
4. Delete Student
5. Display Unique Subject
6. Exit

Enter your choice: 1

Enter Name: John
Enter Age: 18
Enter Grade: A
Enter Student ID: 101
Enter Date of Birth: 10-05-2007
Enter Subjects (comma-separated): Math, Science, English

Student Added Successfully!
Name: John, Age: 18
Grade:A | ID: 101
DOB: 10-05-2007
```

### Display Student Records

```
=======STUDENT RECORDS=======

-----------------------------------------
Student ID : 101
DOB        : 10-05-2007
Name       : John
Age        : 18
Grade      : A
Subjects   : Math, Science, English
-----------------------------------------
```

### Display Unique Subjects

```
Unique Subjects:
English
Math
Science
```

---

## How to Run

1. Install Python 3.
2. Save the program as `student_data.py`.
3. Open a terminal or command prompt.
4. Run the program:

```bash
python student_data.py
```

---

## Learning Concepts

- Lists
- Dictionaries
- Tuples
- Sets
- Loops
- Conditional Statements
- User Input
- String Formatting
- CRUD Operations (Create, Read, Update, Delete)

---

## Project Structure

```
student-data-organisation/
│
├── student_data.py
└── README.md
```

---

## Future Improvements

- Store data permanently using a file or database.
- Validate user input.
- Search students by ID or name.
- Sort student records.
- Generate reports.

---

## License

This project is created for educational and learning purposes.
