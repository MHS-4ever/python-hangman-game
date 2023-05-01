# python-hangman-game
This respiratory contain a .py file containing the complete python code of Hangman Game and a .ppt file containing the complete step-by-step description of the code.
Make a function named hangman.

Make a list of words.

A random word from the list is selected using a function random.choice() from random library

Store the random word in the variable word

Turn variable is used to keep the track of the number of chances the player has to guess the words

Initialize empty string to store the letters the player has already guessed

Specify a set of valid entries

Start a loop that will continue until the “word” length is greater than 0

“main_word” store the word that is displayed to the player, with unguessed letters replaced by underscores

Start a for loop that will iterate over each letter in “word” 

Apply if condition to check whether the letter in loop has already been guessed by the player

If letter has alredy been guessed, it is added to the “main _word” string.

If not else block execute and add underscore and a space to the “main_word”

This if condition will check whether the “main_word” string is equal to”word”

If both are equal print line will print “main_word” and congrats msg

Break will cause the exit from the loop

Take input from the player and store it in an variable “guess”

First if condition will check whether the player made valid entry if yes it is added to the “guessmade” string 

If not else block will execute and print the statement

Second input prompt the player to enter another guess

Second if condition will check whether the guess made by the player us not present in the word

If guess is not present the number of remaining turns is decremented by 1

Use nested if in place of elif

The block check if the number of remaining turns is 9. if it is the hangman ASCII art is printed along with the msg “9 turns left”

The block check if the number of remaining turns is 8. if it is the hangman ASCII art is printed along with the msg “8 turns left”

The block check if the number of remaining turns is 7. if it is the hangman ASCII art is printed along with the msg “7 turns left”

The block check if the number of remaining turns is 6. if it is the hangman ASCII art is printed along with the msg “6 turns left”

The block check if the number of remaining turns is 5. if it is the hangman ASCII art is printed along with the msg “5 turns left”

The block check if the number of remaining turns is 4. if it is the hangman ASCII art is printed along with the msg “4 turns left”

The block check if the number of remaining turns is 3. if it is the hangman ASCII art is printed along with the msg “3 turns left”

The block check if the number of remaining turns is 2. if it is the hangman ASCII art is printed along with the msg “2 turns left”

The block check if the number of remaining turns is 1. if it is the hangman ASCII art is printed along with the msg “1 turns left”

The block check if the number of remaining turns is 0. if it is the hangman ASCII art is printed along with the msg “you loose” and “you let a good man die

Infinite while loop starts

Take user name as input

Print some statements

Call the hangman() function

Take user_input whether he wants to play again

 if not farewell msg printed 

And function breaks

Import openpyxl (python library for reading and writing excel files)

Import os (for interaction with operating system)

Give a path to make an excel workbook

If condition will check whether the file specified by “filepath” exist or not

If not than it will make the file using openpyxl.Workbook() function

Sheet variable get the active sheet of the workbook

Create a list with two strings “Name” and “Status”

Add heading list as a new row to the end of active sheet

This line save the workbook to the specified filepath

Open excel workbook from the file specified by the path

Get active sheet of the workbook

Create a list (a) contains the player name and string “you won”

Append list a as a new row to the end of the sheet

Save the workbook

Open excel workbook from the file specified by the path

Get active sheet of the workbook

Create a list (b) contains the player name and string “you lose”

Append list (b) as a new row to the end of the sheet

Save the workbook
