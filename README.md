# 📘 Basic Calculator Program

This is a basic Python program that performs arithmetic operations: addition, subtraction, multiplication, and division.

## Input

The program prompts the user to enter two numbers.  
These values are read as strings and then converted to floats using `float()`.  
This allows the calculator to handle both whole and decimal numbers.

## Operation Selection

After receiving the numbers, the user is asked to choose an operation.  
The accepted symbols are: `+`, `-`, `*`, or `/`.

## Logic and Execution

The program uses conditional statements (`if`, `elif`, `else`) to determine which operation to perform.

If the user selects:
- `+`: the two numbers are added.
- `-`: the second number is subtracted from the first.
- `*`: the numbers are multiplied.
- `/`: the program first checks if the second number is not zero. If it’s not, division is performed.

If the user enters `/` and the second number is zero, the program displays an error message to avoid division by zero.

## Invalid Input Handling

If the user enters a symbol other than the four allowed operations, the program prints an error message.  
It reminds the user to choose a valid operation.

## Purpose

This calculator helps demonstrate:
- User input handling
- Type conversion
- Conditional logic
- Basic error handling
- Functional program design for beginners
