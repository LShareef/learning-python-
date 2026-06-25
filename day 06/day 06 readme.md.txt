         #  DAY 06
       # MADLIBS GAME
 # WORD GAME WHERE YOU CREATE A STORY
 # BY FILLING IN  BLANKS WITH RANDOM WORDS 

adjective1 = input("enter an adjective (description): ")
noun1 = input("enter a noun (person, place, thing): ")
adjective2 = input("enter an adjective (description): ")
verb1 = input("enter a verb ending with 'ing': ")
adjective3 = input("enter an adjective (description): ")


print(f"today i went to a {adjective1} zoo. ")
print(f"in an exhibit, i saw a {noun1}")
print(f"{noun1} was {adjective2} and {verb1}")
print(f"i was {adjective3}")
-----------------------------------

*Mad Libs Game – Project Explanation*

This program is a simple Mad Libs game created using Python. The user is asked to enter different types of words such as adjectives, a noun, and a verb ending with “ing”. These words are stored in variables and then inserted into a short story.

The program uses the input() function to collect words from the user and saves them in variables like adjective1, noun1, and verb1.

After collecting all the inputs, the program uses f-strings (f"") to combine the user’s words with predefined sentences. This creates a unique and often funny story every time the program runs.

Concepts Used

* Variables
* User Input (input())
* String Formatting (f-strings)
* Printing Output (print())

How It Works

1. The user enters three adjectives, one noun, and one verb ending with “ing”.
2. The program stores these words in variables.
3. The stored words are inserted into a story template.
4. The completed story is displayed on the screen.

Example Output
Code:-

Enter an adjective: beautiful
Enter a noun: tiger
Enter an adjective: playful
Enter a verb ending with ing: dancing
Enter an adjective: excited

Today I went to a beautiful zoo.
In an exhibit, I saw a tiger.
Tiger was playful and dancing.
I was excited.

This project helped me understand how to take input from users, store data in variables, and create dynamic text output using Python.
