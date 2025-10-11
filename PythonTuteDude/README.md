# tutedude-Assignments
This repository is created to submit the tasks for the assignments of tutedude

# 🧮 Task 1: Perform Basic Mathematical Operations

## 📌 Problem Statement

Write a Python program that:

1. Takes **two numbers** as input from the user.
2. Performs the following **basic mathematical operations**:
   - ➕ Addition
   - ➖ Subtraction
   - ✖️ Multiplication
   - ➗ Division
3. Displays the **results** of each operation on the screen.

## 🚀 How to Run

1. Clone this repository or download the Python file.
2. Open a terminal or run the script in your IDE.
3. Enter two numbers when prompted.
4. View the results of all four operations.

```bash
python module2_task1.py


# 👋 Task 2: Create a Personalized Greeting

## 📌 Problem Statement

Write a Python program that:

1. Takes a user's **first name** and **last name** as input.
2. Concatenates them to form the **full name**.
3. Prints a **personalized greeting message** using the full name.

---

## 🚀 How to Run

1. Clone this repository or download the Python file.
2. Open a terminal or run the script in your IDE.
3. Enter your first and last name when prompted.
4. View the personalized greeting.

```bash
python module2_tas2.py

# Python Fundamentals Tasks

This repository contains Python solutions for two fundamental programming tasks: checking if a number is even or odd, and calculating the sum of a range of integers using a loop.

***

## 🚀 Task 1: Check if a Number is Even or Odd

This program takes an integer from the user and determines whether it is an even or an odd number using the modulo operator (`%`).

### Problem Statement

Write a Python program that:
1. Takes an integer input from the user.
2. Checks whether the number is even or odd using an `if-else` statement.
3. Displays the result accordingly.

### Python Solution (`Task1_Even_Odd.py`)

```python
num = int(input('Enter a number: '))

if (num % 2) != 0:
    print(num, ' is an odd number')
else:
    print(num, ' is an even number')

# Python Task: Sum of Integers from 1 to 50 Using a Loop

This program demonstrates how to use a `for` loop in Python to calculate the cumulative sum of a fixed range of integers.

***

## 🔢 Task: Sum of Integers from 1 to 50

### Problem Statement

Write a Python program that:
1. Uses a **`for` loop** to iterate over numbers from **1 to 50** (inclusive).
2. Calculates the sum of all integers in this range.
3. Displays the final sum.

### Python Solution (`sum_calculator.py`)

The code initializes a total sum to zero and then uses the `range(1, 51)` function to iterate through the numbers 1, 2, 3, ... up to 50.

```python
sum_total = 0
for i in range(1, 51):
    sum_total += i

print('The sum of numbers from 1 to 50 is:', sum_total)