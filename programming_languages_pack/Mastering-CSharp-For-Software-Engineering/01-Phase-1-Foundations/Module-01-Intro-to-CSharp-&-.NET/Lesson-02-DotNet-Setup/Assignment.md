# Assignment: Lesson 02 – .NET Setup
## Mastering C# for Software Engineering

---

# Objective

This assignment will help you understand how .NET works, how to set up your development environment, and how to create and run your first C# project using the .NET CLI.

---

# Part 1: Theory Questions

Answer in your own words:

1. What is .NET?
2. Why do we need .NET to run C# programs?
3. What is CLR and what is its role?
4. What is BCL (Base Class Library)?
5. What is the difference between .NET Framework and .NET 8?

---

# Part 2: Practical Tasks

## Task 1: Check .NET Installation

Open Command Prompt and run:

```bash id="taskdotnet01"
dotnet --version
```

## Task 2: Create First Console Application

Use .NET CLI to create a project:
```bash
dotnet new console -n MyFirstApp
```
Then go into the folder:
```bash
cd MyFirstApp
```
Run the application:
```bash
dotnet run
```
## Task 3: Modify Program.cs

Edit Program.cs and change the output to display:

1. Your Name
2. Your University or School
3. Your Country

Example output: 
```bash id="taskoutput02"
Name: John Doe  
University: XYZ Institute  
Country: Sri Lanka
```
---

## Task 4: Experiment Task

Modify your program to:
- Print at least 5 different lines
- Use proper formatting
- Make output look clean and structured

---

# Rules

- Do not copy answers without understanding
- Write your own code
- Run and test your program before submission
- Keep code clean and readable
- Follow proper indentation

---

# Submission Instructions

Upload your work to GitHub:

```bash id="submit02"
git add .
git commit -m "Completed Lesson 02 Assignment"
git push origin main