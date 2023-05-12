# Grading-students-javascript

This JavaScript code reads input from standard input, grades students' exam scores and writes the result to standard output.

Getting Started
To use this code, you need to have Node.js installed on your machine. You can download and install it from the official website - https://nodejs.org.

Installation
Clone the repository or download the file gradingStudents.js.

Usage
To run the program, execute the following command in your terminal:

Copy code
node gradingStudents.js
The program will prompt you to enter the number of grades followed by each grade on a new line. After entering all grades, the program will print the rounded grades for each student to the console.

Functionality
The gradingStudents function takes an array of integers as input. Each integer represents the grade of a student. The function then rounds each grade according to the following rules:

If the difference between the grade and the next multiple of 5 is less than 3, round the grade up to the next multiple of 5.
If the grade is less than 38, do not round it.
The function returns an array of the rounded grades.

The main function reads input from standard input, calls the gradingStudents function to grade the students' exams, and writes the result to standard output.

Contributing
If you would like to contribute to this project, feel free to submit a pull request or open an issue.

License
This code is licensed under the MIT License. See the LICENSE file for more information.
