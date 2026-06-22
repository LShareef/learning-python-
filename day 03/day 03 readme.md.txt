     #Day 03

# TOPICS COVERED 
#   BOOLEAN & IF ELSE STATEMENT 

Student_Shareef = False

if Student_Shareef == True:
    print("Shareef is a student")
else:
    print("Shareef is not a student")
#----------
  #TYPECASTING = the process of converting a variable from one data to another
                 #str(), int(), float(), bool() 

name = "Shareef"
age = 25
gpa = 3.2
is_student = True 

gpa = float(age)



name = input("what is your name: ")
age = input("what is your age: ") 
age = int(age)
age += 1

print(f"happy birthday {name} you are {age} years old")

Birthday Age Calculator

This is one of my first Python programs. In this program, I learned how to take input from the user and use variables to store that information.

First, the program asks the user for their name and age. The age entered by the user is received as text, so I converted it into a number using int().

After converting the age into a number, I increased it by 1 using age += 1. This was done to simulate a birthday where the user’s age becomes one year older.

Finally, I used an f-string to display a message that includes the user’s name and updated age.

This small project helped me understand:

* How to use input()
* How to store values in variables
* How to convert text into numbers using int()
* How to perform basic arithmetic operations
* How to display output using f-strings

Sample Output:

What is your name: Shareef

What is your age: 21

Happy Birthday Shareef, you are 22 years old.