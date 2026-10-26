# Student Registration System (C#)

A simple C# console application that collects student information, calculates total and average marks, and displays a formatted registration summary.

**Topics covered:** Introduction to C#, variables and data types, operators, and input and output.


## Scenario

A school wants a simple C# console application that collects student information, calculates their total marks and average, and displays a summary of their registration details.

---

## Requirements

The program must:

1. Display the school name and a welcome message.
2. Ask the user to enter their full name, age, course name, and registration number.
3. Ask the user to enter marks for three subjects.
4. Calculate the total marks and average marks.
5. Display all the student details, total marks, and average marks in a well-formatted output.

---

## Instructions

Your program must:

- Use appropriate variables and data types.
- Use `Console.WriteLine()` to display messages.
- Use `Console.ReadLine()` to receive user input.
- Convert input into the correct data types where necessary.
- Use arithmetic operators to calculate the total and average.
- Use meaningful variable names.

---

## Expected Output

```text
GREENWOOD HIGH SCHOOL

Welcome to Student Registration!

Enter your full name: Brian Otieno
Enter your age: 19
Enter your course: Software Engineering
Enter registration number: SE2026/015

Enter marks for Mathematics: 80
Enter marks for English: 75
Enter marks for Programming: 90

STUDENT SUMMARY

Name: Brian Otieno
Age: 19
Course: Software Engineering
Registration Number: SE2026/015
Total Marks: 245
Average Marks: 81.67
```

---

## Getting Started

### Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download) installed

### Run the project

```bash
dotnet new console -n StudentRegistration
cd StudentRegistration
# Add your code to Program.cs
dotnet run
```
