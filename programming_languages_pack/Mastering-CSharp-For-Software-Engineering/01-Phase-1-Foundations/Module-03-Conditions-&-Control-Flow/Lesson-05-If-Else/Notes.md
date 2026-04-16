# Lesson 05: If-Else in C#
## Notes – Mastering C# for Software Engineering

---

# 1. Introduction

In programming, we often need to make decisions.  
The **if-else statement** is used to control the flow of a program based on conditions.

It helps the program answer questions like:
- Is the user old enough?
- Is the number positive or negative?
- Did the student pass or fail?

---

# 2. What is If-Else?

If-else is a **conditional statement** that executes different blocks of code depending on whether a condition is true or false.

---

# 3. Basic Syntax

```csharp id="ifelse01"
if (condition)
{
    // runs if condition is true
}
else
{
    // runs if condition is false
}
```
# 4. Simple Example
```csharp id="ifelse02"
int age = 18;

if (age >= 18)
{
    Console.WriteLine("You are an adult");
}
else
{
    Console.WriteLine("You are a minor");
}
```
# 5. If-Else If-Else Ladder
Used when there are multiple conditions.
```csharp id="ifelse03"
int marks = 75;

if (marks >= 75)
{
    Console.WriteLine("Grade A");
}
else if (marks >= 50)
{
    Console.WriteLine("Grade B");
}
else
{
    Console.WriteLine("Fail");
}
```
# 6. Nested If Statement
If statement inside another if statement.
```csharp id="ifelse04"
int age = 20;
bool hasID = true;

if (age >= 18)
{
    if (hasID)
    {
        Console.WriteLine("Allowed to enter");
    }
}
```
# 7. Real World Example
Login System Logic:

```csharp id="ifelse05"
string username = "admin";
string password = "1234";

if (username == "admin")
{
    if (password == "1234")
    {
        Console.WriteLine("Login Successful");
    }
    else
    {
        Console.WriteLine("Wrong Password");
    }
}
else
{
    Console.WriteLine("User not found");
}
```
# 8. Comparison Operators Used in If-Else
| Operator | Meaning          |
| -------- | ---------------- |
| ==       | Equal to         |
| !=       | Not equal to     |
| >        | Greater than     |
| <        | Less than        |
| >=       | Greater or equal |
| <=       | Less or equal    |

# 9. Logical Operators in If-Else
| Operator | Meaning | Description |
|----------|---------|-------------|
| &&       | AND     | Both conditions must be true |
| \|\|     | OR      | At least one condition must be true |
| !        | NOT     | Reverses the condition |

**Example**
```csharp id="ifelse06"
int age = 20;
bool hasID = true;

if (age >= 18 && hasID)
{
    Console.WriteLine("Allowed");
}
```
# 10. Common Mistakes
- Forgetting braces { }
- Using = instead of ==
- Wrong condition logic
- Missing else block when needed