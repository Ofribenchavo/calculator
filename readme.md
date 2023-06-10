# Simple Calculator Project

## Overview

This is a simple calculator project developed in Python. It allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division. The project consists of a single script, `calculator.py`, that asks the user for two numbers and an operator, and then performs the requested operation.

## Usage

To use the calculator, run the `calculator.py` script in a Python environment. The script will prompt you for two numbers and an operator. Enter the numbers and operator as prompted. The calculator supports the following operations:

- Addition (`+`)
- Subtraction (`-`)
- Multiplication (`*`)
- Division (`/`)

Here is an example of the calculator in operation:
python
Enter your first number: 10
Enter your operator: +
Enter your second number: 20


The script will then print the result of the operation. In this case, the output would be `30`.

If you enter an operator that is not supported, the script will print "Error".

## Project Structure

The project consists of the following files:

- `calculator.py`: The main script for the calculator.
- `main.py`: A duplicate of `calculator.py`.
- `exportToHTML/main.py.html`: An HTML version of the `calculator.py` script.

In addition, the project includes a `.idea` directory, which contains settings for the PyCharm IDE and is not relevant to the functionality of the project.

## Code

The main logic of the calculator is contained in the following lines of code:

```python
num1 = float(input("Enter your first number :"))
op = input("Enter your operator:")
num2 = float(input("Enter your second number :"))
if op == "*":
  print(num1 * num2)
elif op == "/":
  print(num1 / num2)
elif op == "-":
  print(num1 - num2)
elif op == "+":
  print(num1 + num2)
else:
  print("Error")
```

This code first asks the user to input two numbers and an operator. It then uses a series of if and elif statements to determine which operation to perform based on the operator entered by the user. If the operator is not recognized, it prints "Error".

## Future Work
Potential future improvements for this project could include adding support for more complex mathematical operations, improving error handling, and adding a graphical user interface.
