               #DAY 09
         # PYTHON CALCULATER 

operater = input("enter the operater + - * / ): ")
num1 = float(input("enter the 1st number: ")) 
num2 = float(input("enter the 2nd number: "))

if operater == "+":
    result = num1 + num2
    print(round(result, 3))
elif operater == "-":
    result = num1 - num2
    print(round(result, 3))
elif operater == "*":
    result = num1 * num2
    print(round(result, 3))
elif operater == "/":
    result = num1 / num2
    print(round(result, 3))
else:
    print(f"{operater} is not a valid operator")

  #------------------------------------------------------------  
    
                                            #Python Calculator

# This project is a simple calculator built using Python to practice the basics of programming. 
# It allows the user to perform four basic arithmetic operations: addition, subtraction, multiplication, and division.
# The program starts by asking the user to enter an operator (+, -, *, or /) and then takes two numbers as input. 
# Using if, elif, and else statements, it checks which operator was selected and performs the corresponding calculation.
# Instead of printing the calculation directly, the answer is first stored in a variable called result. 
# The round() function is then used to display the output with up to three decimal places, making the result cleaner and easier to read.
# If the user enters an operator other than the supported ones, the program displays an error message to let them know the input is invalid.

# This project helped me practice:

#* Taking user input with input()
#* Converting input into numbers using float()
#* Using variables to store data
#* Writing conditional statements (if, elif, else)
#* Performing basic arithmetic operations
#* Formatting output using the round() function

#Overall, this project gave me a better understanding of how Python programs accept input, make decisions, process data, and produce meaningful output.
    
    





