# Lesson 04: Operators & Type Casting in C#
## Notes – Mastering C# for Software Engineering

---

# 1. Introduction

In this lesson, you will learn:
- How operators work in C#
- How to perform calculations and comparisons
- How to convert data types (Type Casting)

These are essential for building logic in any C# program.

---

# 2. What are Operators?

Operators are symbols used to **perform operations on variables and values**.

Example:
- Add numbers
- Compare values
- Combine conditions

---

# 3. Types of Operators in C#

---

# 3.1 Arithmetic Operators

Used for mathematical operations.

| Operator | Meaning        | Example |
|----------|----------------|---------|
| +        | Addition       | a + b   |
| -        | Subtraction    | a - b   |
| *        | Multiplication | a * b   |
| /        | Division       | a / b   |
| %        | Modulus        | a % b   |

---

## Example

```csharp id="arith01"
int a = 10;
int b = 5;

Console.WriteLine(a + b);
Console.WriteLine(a - b);
Console.WriteLine(a * b);
Console.WriteLine(a / b);
Console.WriteLine(a % b);
```
# 3.2 Comparison Operators
Used to compare values.
| Operator | Meaning          |
| -------- | ---------------- |
| ==       | Equal to         |
| !=       | Not equal to     |
| >        | Greater than     |
| <        | Less than        |
| >=       | Greater or equal |
| <=       | Less or equal    |

Example

```csharp id="arith02"
int x = 10;
int y = 20;

Console.WriteLine(x == y);
Console.WriteLine(x != y);
Console.WriteLine(x > y);
Console.WriteLine(x < y);
```
# 3.3 Logical Operators
Used to combine conditions.
| Operator | Meaning |   |    |
| -------- | ------- | - | -- |
| &&       | AND     |   |    |
| ||       |         |   | OR |
| !        | NOT     |   |    |


Example
```csharp id="arith03"
bool a = true;
bool b = false;

Console.WriteLine(a && b);
Console.WriteLine(a || b);
Console.WriteLine(!a);
```
# 4. Type Casting in C#
Type Casting means converting one data type into another.

# 4.1 Implicit Casting (Automatic)

Smaller type → Larger type
```csharp id="arith04"
int num = 10;
double result = num;
```
# 4.2 Explicit Casting (Manual)
Larger type → Smaller type
```csharp id="arith05"
double num = 10.5;
int result = (int)num;
```
# 5. Converting Using Methods
```csharp id="arith06"
Convert.ToInt32()
string text = "100";
int number = Convert.ToInt32(text);
Convert.ToDouble()
string text = "99.99";
double number = Convert.ToDouble(text);
```
# 6. Real World Example
```csharp id="arith07"
using System;

class Program
{
    static void Main()
    {
        string input1 = "10";
        string input2 = "20";

        int num1 = Convert.ToInt32(input1);
        int num2 = Convert.ToInt32(input2);

        int sum = num1 + num2;

        Console.WriteLine("Sum: " + sum);
    }
}
```
# 7. Common Mistakes
- Dividing integers and expecting decimals
- Forgetting to cast types
- Mixing string and numbers without conversion
- Wrong operator usage

