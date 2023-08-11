# Calculator

This Python code is a simple calculator that performs basic arithmetic operations on two numbers. The code first connects to a PostgreSQL database and creates a table called casio. The table has four columns:

* num1: The first number
* oper: The arithmetic operator (+, -, *, /)
* num2: The second number
* result: The result of the calculation

The code then prompts the user to enter two numbers and an arithmetic operator. The code then checks if the given numbers and operator are already in the casio table. If they are, the code retrieves the result from the table. Otherwise, the code inserts the new numbers and operator into the table and sets the result to 0.

The code then calculates the result of the arithmetic operation and prints it to the console. The code finally updates the casio table with the new result.

## Usage

To use the calculator, you will need to have Python and PostgreSQL installed on your computer. You can then run the code by typing the following command in your terminal:


python calculator.py


The code will prompt you to enter two numbers and an arithmetic operator. After you have entered the numbers and operator, the code will calculate the result and print it to the console.

## Example

The following is an example of how to use the calculator:


Enter num1: 10
Enter operator: +
Enter num2: 20

The result is 30
