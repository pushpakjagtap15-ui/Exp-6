## Experiment 6: Study of Conditional Statements in Python

## Author
- **Name:** Pushpak J  
- **PRN:** 25070123148  
- **Branch:** F.Y. E&TC (2025-29)  
- **Batch:** A1  
- **Subject:** Exploratory Data Analysis With Python  

---

## Title
Study of Conditional Statements in Python

---

## Aim
To study and implement conditional control structures in Python, specifically focusing on the if-else statement.

---

## Objectives
- Understand the logic of conditional execution  
- Learn the syntax of if and else blocks in Python  
- Implement decision-making logic in programs  
- Apply relational and logical operators within conditions  

---

## Theory: Conditional Statements
Conditional statements allow a program to execute specific blocks of code based on whether a condition evaluates to **True** or **False**.

### The if-else Structure
- **if Statement:** Executes code inside the block only if the specified condition is met (True).  
- **else Statement:** Provides an alternative path, executing only when the if condition is not met (False).  
- **Indentation:** Python uses indentation to define the scope of these blocks, which is crucial for correct execution.  

### Common Operators Used
- **Relational:** `==` (equal to), `!=` (not equal to), `>` (greater than), `<` (less than), `>=`, `<=`  
- **Logical:** `and`, `or`, `not`  

---

## Practical Implementation

### Example 1: Even or Odd Number
```python
num = int(input("Enter a number: "))

if num % 2 == 0:
    print("The number is Even.")
else:
    print("The number is Odd.")
Example 2: Grade Evaluation
python
marks = 85

if marks >= 75:
    print("Distinction")
elif marks >= 60:
    print("First Class")
elif marks >= 40:
    print("Pass")
else:
    print("Fail")
Example 3: Logical Operators
python
age = 20
has_id = True

if age >= 18 and has_id:
    print("Entry Allowed")
else:
    print("Entry Denied")

























Conclusion
Conditional statements are fundamental to programming as they allow the code to make decisions.
By using if-else blocks, we can handle different scenarios effectively and ensure the program responds correctly to various inputs.
Relational and logical operators further enhance decision-making, making conditional structures a core part of Python programming.

