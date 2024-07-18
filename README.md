# CODTECH-Task-1

**Name:** Sannapaneni Venkat
**Company:** CODTECH IT SOLUTIONS
**ID:** CT6WDS680
**Domain:** Python Programming
**Duration:** June 25th to August 10th.

# Simple Calculator Program 

The basic calculator program is designed to perform arithmetic operations based on user inputs. It guides the user through a series of steps to enter numbers and choose an operation, then performs the selected operation and displays the result.

## Steps of the Program

### Welcome Message
The program starts by printing a welcome message to the user, indicating that they are using a basic calculator.

### Input First Number
The program prompts the user to enter the first number. It uses `input()` to get the user's input and `float()` to convert it to a floating-point number. This allows the calculator to handle both integer and decimal numbers.

### Input Second Number
Similarly, the program prompts the user to enter the second number, converting it to a floating-point number as well.

### Choose Operation
The program displays a list of arithmetic operations:

- Addition (+)
- Subtraction (-)
- Multiplication (*)
- Division (/)

The user is asked to enter the number corresponding to the desired operation.

### Perform the Operation
The program uses a series of `if-elif` statements to check which operation the user selected:

- **Addition (1):** Adds the two numbers and displays the result.
- **Subtraction (2):** Subtracts the second number from the first and displays the result.
- **Multiplication (3):** Multiplies the two numbers and displays the result.
- **Division (4):** Divides the first number by the second and displays the result. The program includes a check to ensure the second number is not zero to prevent division by zero errors.

### Display Result
The program prints the result of the arithmetic operation in a user-friendly format, indicating the operation performed and the resulting value.

### Error Handling
- If the user selects an invalid operation (any input other than 1, 2, 3, or 4), the program prints an error message indicating that the operation is invalid.
- If the user attempts to divide by zero, the program prints an error message indicating that division by zero is not allowed.
