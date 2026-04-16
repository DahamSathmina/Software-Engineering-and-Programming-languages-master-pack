# Lesson 02: .NET Setup
## Full Study Notes (Beginner to Professional)

---

# 1. Introduction

.NET is a **software development platform** created by Microsoft that allows developers to build, run, and manage applications using C# and other languages.

C# always runs on the .NET platform, so understanding .NET is essential for software development.

---

# 2. What is .NET?

.NET is a complete development ecosystem that includes:
- Runtime environment
- Libraries
- Development tools
- Frameworks for different application types

It provides everything needed to build modern software systems.

---

# 3. Why .NET is Important

.NET is important because:

- It allows C# applications to run
- It handles memory management automatically
- It provides built-in libraries for faster development
- It supports web, desktop, mobile, and cloud applications
- It ensures performance and security

---

# 4. Core Components of .NET

## 4.1 CLR (Common Language Runtime)

CLR is the **execution engine of .NET**.

It is responsible for:
- Running C# programs
- Memory management (Garbage Collection)
- Exception handling
- Thread management

---

## 4.2 BCL (Base Class Library)

BCL contains pre-built code for common tasks:

- Console input/output
- File handling
- String manipulation
- Collections (List, Dictionary)
- Math operations

---

## 4.3 SDK (Software Development Kit)

The .NET SDK includes:
- Compiler (converts code to IL)
- CLI tools (`dotnet`)
- Libraries
- Project templates

---

# 5. Types of .NET

## 5.1 .NET Framework (Old Version)
- Windows-only
- Used in legacy applications
- Not recommended for modern development

## 5.2 .NET Core
- Cross-platform
- Faster and lightweight
- Open-source

## 5.3 .NET 5 / 6 / 7 / 8
- Unified platform
- Industry standard
- Used for modern software engineering

---

# 6. Installing .NET SDK

## Steps:
1. Download .NET 8 SDK from Microsoft
2. Install it on your system
3. Restart your computer (recommended)

---

# 7. Verify Installation

Open Command Prompt and run:

```bash id="verifydotnet"
dotnet --version
```

# 8. Creating a C# Console Application
## Step 1

Open Command Prompt

## Step 2

Create project:
```bash
dotnet new console -n MyFirstApp
```
## Step 3

Navigate into project:
```bash
cd MyFirstApp
```
## Step 4

Run application:
```bash
dotnet run
```
# 9. Project Structure

After creation:
```bash
MyFirstApp/
│
├── Program.cs
├── MyFirstApp.csproj
```
# 10. Program Execution Flow

When you run a C# program:

- Code is written in .cs file
- Compiler converts it to Intermediate Language (IL)
- CLR executes the IL code
- Output is displayed
# 11. Example Program
```bash
using System;

class Program
{
    static void Main()
    {
        Console.WriteLine("Welcome to .NET Programming!");
    }
}
```
# 12. Key Concepts Learned

After this lesson, you should understand:

- What .NET is
- Why .NET is required for C#
- How .NET executes applications
- How to install .NET SDK
- How to create and run a console application