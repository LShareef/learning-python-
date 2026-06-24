          #DAY 05
  #EXERCISE-1 SIMPLE CALCULATOR


num1 = float(input("Enter your first number: "))
num2 = float(input("Enter your secound number: "))

operator = input("choose an operator: ( +, -, *, /: )")

if operator == "+":
    print(num1 + num2)

elif operator == "-":
    print(num1 - num2)

elif operator == "*":
    print(num1 * num2)

elif operator == "/":
    print(num1 / num2)

else :
    print("this is an invalid operation")

-----------------------------------------

      #EXPLAINATION OF SIMPLE CALCULATOR 

Simple Calculator in Python

This is a beginner-friendly calculator program built using Python. The program takes two numbers and an arithmetic operator (+, -, *, /) as input from the user and performs the selected operation.

The calculator first asks the user to enter two numbers and then choose an operator. Based on the operator entered, the program uses if, elif, and else statements to decide which calculation to perform.

* + performs addition
* - performs subtraction
* * performs multiplication
* / performs division

If the user enters an operator other than the supported ones, the program displays an error message indicating that the operation is invalid.

This project was created as a practice exercise to understand Python basics such as:

* Variables
* User input with input()
* Type conversion using float()
* Conditional statements (if, elif, else)
* Arithmetic operators

It is a simple project that helped me learn how to take user input, process data, and make decisions in a Python program.
    
