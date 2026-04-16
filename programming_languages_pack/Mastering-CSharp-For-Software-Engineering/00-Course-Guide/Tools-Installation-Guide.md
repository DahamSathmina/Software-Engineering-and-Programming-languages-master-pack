# Tools Installation Guide
## Mastering C# for Software Engineering (Beginner to Professional)

This guide explains how to install all required tools to follow the C# course properly.  
Please complete all installations before starting Phase 1.

---

# 1. Install Visual Studio 2022 (Recommended IDE)

## Download
Download Visual Studio Community Edition from the official Microsoft website.

## Recommended Workloads
During installation, select these workloads:

- .NET Desktop Development  
- ASP.NET and Web Development  
- Data Storage and Processing  

These workloads include everything needed for:

- Console applications  
- Windows Forms / WPF applications  
- ASP.NET Core MVC projects  
- ASP.NET Core Web API development  
- SQL integration  

## Recommended Components
Make sure these components are installed:

- .NET SDK (latest)  
- C# compiler  
- MSBuild tools  
- NuGet package manager  

---

# 2. Install .NET 8 SDK

## Why You Need It
The .NET SDK is required to compile and run C# applications using modern .NET.

## Verify Installation
After installing, open Command Prompt and run:

```bash
dotnet --version
```

## 3. Install SQL Server (Database Engine)
Why You Need It
SQL Server is required for database development in Phase 4 and beyond.

Recommended Version
- SQL Server 2019
- SQL Server 2022
Installation Notes

During installation:

- Choose "Database Engine Services"
- Select authentication mode:
    -  Windows Authentication (recommended)
    -  Mixed Mode (optional)

If using Mixed Mode, save your login credentials.

## 4. Install SQL Server Management Studio (SSMS)
Why You Need It
SSMS is used to manage databases and write SQL queries easily.

After Installation
Open SSMS and connect using:
- Server Name: localhost or your PC name
- Authentication: Windows Authentication

5. Install Git (Version Control Tool)
Why You Need It
Git is required for:

- Tracking code changes
- Managing versions
- Uploading assignments to GitHub

**Verify Installation**

Open Command Prompt and run:

```bash
git --version
```
If installed correctly, it will show a version number.

## 6. Create a GitHub Account
Why You Need It
GitHub is required for:

Uploading assignments
Building your portfolio
Storing projects professionally
**Setup Steps**
- Create an account on GitHub
- Create your first repository
- Add a profile photo and bio (recommended)
- Learn basic Git workflow

## 7. Install Postman (API Testing Tool)
Why You Need It**
Postman is used in Phase 5 for testing APIs.

You will use it for:

- GET requests
- POST requests
- PUT requests
- DELETE requests
- JWT authentication testing

## 8. Install Visual Studio Code (Optional)
Why Use It
VS Code is optional but useful for:

- Quick code editing
- Viewing project files
- Writing documentation
- Editing JSON/config files
**Recommended Extensions**
- C#
- C# Dev Kit

## 9. Install Docker (Optional)
Why You Need It
Docker is optional but useful for:

- Running SQL Server containers
- Deploying ASP.NET Core applications
- Learning DevOps basics

Recommended for advanced learners after Phase 5.
**Recommended Folder Structure**

Create a dedicated folder for your course:
```bash
C:\CSharpCourse\
```
Inside it:
```bash
C:\CSharpCourse\Phase-1\
C:\CSharpCourse\Phase-2\
C:\CSharpCourse\Projects\
```
This helps keep your work organized and professional.

# System Requirements
**Minimum Requirements**
```bash
8 GB RAM
Intel i3 / Ryzen 5 or above
50 GB free storage
Windows 10 / Windows 11
```
**Recommended Requirements**
```bash
16 GB RAM
SSD storage
Windows 11
```

**Installation Checklist**
Before starting the course, make sure you installed:
```bash
Visual Studio 2022
.NET 8 SDK
SQL Server
SQL Server Management Studio (SSMS)
Git
GitHub Account
Postman
```
Optional:
```bash
Visual Studio Code
Docker
```