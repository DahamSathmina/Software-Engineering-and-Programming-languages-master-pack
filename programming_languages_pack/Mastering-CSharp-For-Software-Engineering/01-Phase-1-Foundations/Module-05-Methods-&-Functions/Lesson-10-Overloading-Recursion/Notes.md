# Lesson 10: Method Overloading & Recursion in C#
## Notes – Mastering C# for Software Engineering

---

# 1. Introduction

In this lesson, you will learn two advanced method concepts in C#:

- Method Overloading
- Recursion

These help you write more flexible and powerful programs.

---

# 2. Method Overloading

## 2.1 What is Method Overloading?

Method overloading means:
👉 Having multiple methods with the same name but different parameters.

It allows you to perform similar actions with different inputs.

---

## 2.2 Why Use Overloading?

- Improves code readability
- Reduces method name confusion
- Supports different input types
- Makes code flexible

---

## 2.3 Syntax Example

```csharp id="overload01"
static int Add(int a, int b)
{
    return a + b;
}

static double Add(double a, double b)
{
    return a + b;
}
```
# 2.4 Example Usage
```bash
Console.WriteLine(Add(5, 10));
Console.WriteLine(Add(5.5, 2.5));
```
# 2.5 Rules of Overloading
- Method name must be same
- Parameters must be different
- Return type alone is NOT enough
# 3. Recursion
# 3.1 What is Recursion?
Recursion is when a method calls itself.

It is used to solve problems that can be broken into smaller sub-problems.

# 3.2 Why Use Recursion?
- Simplifies complex problems
- Useful for mathematical problems
- Used in algorithms (sorting, searching)
# 3.3 Basic Syntax
```bash
static void Method()
{
    Method(); // self call
}
```
⚠️ Warning: This causes infinite loop if no stopping condition is added.

# 3.4 Base Case (Very Important)
A base case stops recursion.
```bash
static void CountDown(int i)
{
    if (i == 0)
        return;

    Console.WriteLine(i);
    CountDown(i - 1);
}
```
# 3.5 Example: Factorial
```bash
static int Factorial(int n)
{
    if (n == 1)
        return 1;

    return n * Factorial(n - 1);
}
```
# 3.6 Example Usage
```bash
Console.WriteLine(Factorial(5)); // Output: 120
```
# 4. Overloading vs Recursion
| Concept     | Description                            |
| ----------- | -------------------------------------- |
| Overloading | Same method name, different parameters |
| Recursion   | Method calling itself                  |

# 5. Common Mistakes
- Overloading
- Same parameters (not valid)
- Confusing return type difference
- Recursion
- Missing base case
- Infinite recursion
- Stack overflow error
# 6. Real World Example
Overloading Example: Calculator
```bash
static int Add(int a, int b) => a + b;
static double Add(double a, double b) => a + b;
```
Recursion Example: Countdown
```bash
static void Count(int n)
{
    if (n == 0) return;

    Console.WriteLine(n);
    Count(n - 1);
}
```
