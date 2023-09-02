# Attendance Management System

## Description

The Attendance Management Program is a command-line application that helps teachers and educators manage student attendance. This program allows you to:

- Record attendance for a specific subject and date.
- Store teacher information, subject details, and student data.
- Generate attendance reports in text files for easy reference.

## Features

- Input teacher's name and subject.
- Specify the number of students in the class.
- Enter student names and roll numbers.
- Record student attendance (Present/Absent) and save it to a text file.
- Automatically generates a unique text file for each subject with attendance data.

## Installation

To use this program, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/megh-bari/Attendance-Management-System.git
   ```

2. Compile the program (if required):

   ```bash
   gcc attendance.c -o attendance
   ```

3. Run the program:

   ```bash
   ./attendance
   ```
   
## How It Works:

1. **Enter Teacher Name and Subject:**
   - Start by providing the teacher's name and the subject for which you want to take attendance.

2. **Specify Number of Students:**
   - Input the number of students in your class.

3. **Enter Student Information:**
   - Enter the full name and roll number for each student.

4. **Take Attendance:**
   - For each student, specify if they are present (P) or absent (A).

5. **Save Attendance Data:**
   - The program will save the attendance data in a text file named after the subject and add details about the teacher and date.

6. **Repeat or Exit:**
   - You can choose to continue taking attendance for different subjects or exit the program.

##  Example:
Here's an example of how the program works:

- **Enter the teacher's name:** Code With Harry
- **Enter the subject:** C Programming
- **Enter the number of students in the class:** 3



- Enter full name of student 1: Megh Bari
- Enter roll number for Megh Bari: 101



- Enter full name of student 2: Bob Davis
- Enter roll number for Bob Davis: 102



- Enter full name of student 3: Carol Brown
- Enter roll number for Carol Brown: 103



- Megh Bari [101] is present (P) or absent (A) for C Programming ? P
- Bob Davis [102] is present (P) or absent (A) for C Programming? A
- Carol Brown [103] is present (P) or absent (A) for C Programming? P



- Attendance data for C Programming has been recorded in C Programming_attendance.txt.


- Do you want to continue (1 for Yes, 0 for No)? 0

## Contact Us:
If you have any questions, suggestions, or encounter any issues, please feel free to reach out to us:

- Email: meghbari01@gmail.com
- GitHub Issues: [GitHub repository](https://github.com/megh-bari/Attendance-Management-System/issues)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

