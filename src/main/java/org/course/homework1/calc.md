# Calculator
# The task is

Write a simple console-based calculator program in Java that allows the user to perform basic arithmetic operations. The program should take two numbers and an operator as input and output the result of the operation. The supported operations should include:

`Addition (+)`
`Subtraction (-)`
`Multiplication (*)`
`Division (/)`
#### Requirements:
The program should ask the user to input:

Two numbers (integers or decimal values).
An operator (`+`, `-`, `*`, `/`).
The program should calculate and display the result of the chosen operation.

The program should have a method calculate(`double` num1, `double` num2, char operator) that takes two numbers and an operator as arguments and returns the result of the operation.

If the user inputs a division operation and the second number is 0, the program should display an error message saying that division by zero is not allowed.

The program should handle invalid operator input and prompt the user again if an unsupported operator is entered.

The program should continuously prompt the user for calculations until they choose to exit by entering "exit" instead of a number.

**Use switch-case and separated methods for arithmetic operations, like `addNumbers(double mun1, double num2)`**