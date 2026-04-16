# Lesson 03: Variables in C#
## Notes – Mastering C# for Software Engineering

---

# 1. Introduction

Variables are one of the most important concepts in programming.  
They are used to **store data in memory** so that we can use and manipulate it in a program.

In C#, every variable must have a **data type** and a **name**.

---

# 2. What is a Variable?

A variable is a **named storage location in memory** that holds a value.

Think of it like a box:
- The box has a name
- The box holds a value
- You can change the value anytime

---

# 3. Syntax of Variables

```csharp id="varsyntax01"
dataType variableName = value;
```

# 4. Example of Variables
```bash
int age = 20;
string name = "Daham";
double salary = 50000.50;
bool isActive = true;
```

# 5. Types of Variables
5.1 Local Variables

Declared inside a method.
```bash
static void Main()
{
    int age = 20;
}
```
5.2 Global Variables (Class-level)
```bash
class Program
{
    static int age = 20;
}
```
# 6. Rules for Naming Variables
- Must start with a letter or underscore _
- Cannot start with a number
- Cannot use keywords (like int, class)
- Case-sensitive (Age and age are different)
- Should be meaningful
# 7. Good vs Bad Naming
Good
```bash
int studentAge = 18;
string studentName = "John";
```
Bad
```bash
int a = 18;
string x = "John";
```

# 8. Common Data Types Used with Variables
| Type   | Example      | Description      |
| ------ | ------------ | ---------------- |
| int    | 10           | Whole numbers    |
| double | 10.5         | Decimal numbers  |
| char   | 'A'          | Single character |
| string | "Hello"      | Text             |
| bool   | true / false | Logical values   |

# 9. Changing Variable Values
Variables can be updated:
```bash
int age = 20;
age = 25;
```

# 10. Constants (Fixed Variables)
If a value should NOT change:
```bash
const double PI = 3.14;
```
# 11. Variable Scope

Scope means where a variable can be accessed.

**Local Scope**
Inside method only.

**Class Scope**
Accessible throughout the class.

# 12. Real-World Example
```bash
using System;

class Program
{
    static void Main()
    {
        string name = "Daham";
        int age = 21;
        string country = "Sri Lanka";

        Console.WriteLine(name);
        Console.WriteLine(age);
        Console.WriteLine(country);
    }
}
```
# 13. Common Mistakes
Forgetting semicolon ;
Using wrong data types
Duplicate variable names
Using undeclared variables

# 14. Practice Tasks
**Beginner**
- Create variables for name, age, and country
- Print them
**Intermediate**
- Create a student profile system
- Store marks and print them
**Advanced**
Create a mini system that stores:
- Student name
- Age
- Marks
- Result (Pass/Fail)
# 15. Summary

**After this lesson, you should understand:**

- What variables are
- How to declare variables
- Different types of variables
- Variable naming rules
- Real-world usage of variables