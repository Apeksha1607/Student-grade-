
# Student Grades Management in C

This C program allows you to input details for multiple students, calculates their total and average marks across three subjects, and then displays the results.

---

## Features

* Store student information including name and marks for 3 subjects
* Calculate total marks and average for each student
* Display student details in a clear format

---

## How to Use

1. Clone or download the source file `student_grades.c`.

2. Compile the program using a C compiler:

   ```bash
   gcc student_grades.c -o student_grades
   ```

3. Run the executable:

   ```bash
   ./student_grades
   ```

4. Enter the number of students when prompted.

5. For each student, input their name and marks for 3 subjects.

6. View the calculated total and average marks for each student.

---

## Sample Run

```
Enter number of students: 2
Enter name of student 1: Alice Johnson
Enter marks of 3 subjects for Alice Johnson:
85
90
78
Enter name of student 2: Bob Smith
Enter marks of 3 subjects for Bob Smith:
92
88
95

Student Grades:
Name: Alice Johnson
Marks: 85, 90, 78
Total: 253
Average: 84.33
------------------------
Name: Bob Smith
Marks: 92, 88, 95
Total: 275
Average: 91.67
------------------------
```

---

## Code Overview

* `struct Student`: Defines student information including name, marks, total, and average.
* `calculateGrades()`: Calculates total and average marks for a student using pointers.
* `displayStudent()`: Prints the student's details to the console.
* `main()`: Handles input/output for multiple students and displays results.

---

## Requirements

* Standard C compiler (supports C99 or later)
* Standard C library



---

