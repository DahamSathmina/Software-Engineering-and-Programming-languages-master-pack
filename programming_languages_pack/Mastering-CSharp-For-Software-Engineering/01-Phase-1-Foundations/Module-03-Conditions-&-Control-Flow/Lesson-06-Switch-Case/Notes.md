# Lesson 06: Switch Case in C#
## Notes – Mastering C# for Software Engineering

---

# 1. Introduction

In C#, the **switch statement** is used for decision-making when you have multiple possible values for a single variable.

Instead of writing long `if-else` chains, switch provides a cleaner and more structured way to handle multiple conditions.

---

# 2. What is Switch Case?

A switch statement compares the value of a variable against multiple cases and executes the matching block of code.

---

# 3. Basic Syntax

```csharp id="switchsyntax01"
switch (variable)
{
    case value1:
        // code
        break;

    case value2:
        // code
        break;

    default:
        // code
        break;
}
```
# 4. Simple Example
```csharp id="switchsyntax02"
int day = 3;

switch (day)
{
    case 1:
        Console.WriteLine("Monday");
        break;

    case 2:
        Console.WriteLine("Tuesday");
        break;

    case 3:
        Console.WriteLine("Wednesday");
        break;

    default:
        Console.WriteLine("Invalid Day");
        break;
}
```
# 5. How Switch Works
- The expression is evaluated
- It matches with a case value
- Matching block executes
- break stops execution
- If no match is found, default runs

# 6. Default Case
The default block runs when no case matches.
```csharp id="switchsyntax03"
int number = 10;

switch (number)
{
    case 1:
        Console.WriteLine("One");
        break;

    default:
        Console.WriteLine("No Match Found");
        break;
}
```
# 7. Switch with Strings
Switch can also work with text values.
```csharp id="switchsyntax04"
string role = "Admin";

switch (role)
{
    case "Admin":
        Console.WriteLine("Full Access");
        break;

    case "User":
        Console.WriteLine("Limited Access");
        break;

    default:
        Console.WriteLine("Unknown Role");
        break;
}
```
# 8. Switch vs If-Else
| Switch Case           | If-Else                     |
| --------------------- | --------------------------- |
| Best for fixed values | Best for complex conditions |
| Cleaner code          | More flexible               |
| Easier to read        | Can become long             |

# 9. Common Mistakes
- Forgetting break statement
- Missing default case
- Using switch for complex logic
- Duplicate case values

# 10. Real-World Example
ATM Menu System:
```csharp id="switchsyntax05"
int option = 2;

switch (option)
{
    case 1:
        Console.WriteLine("Deposit");
        break;

    case 2:
        Console.WriteLine("Withdraw");
        break;

    case 3:
        Console.WriteLine("Check Balance");
        break;

    default:
        Console.WriteLine("Invalid Option");
        break;
}
```
