# hangman
The Hangman game
## Key Goals
Create a program for the Hangman guessing game that:
* Takes user input
* The computer randomly selects a secret word.
* A display for the number of remaining player chances.
* The game continues when the player provides an incorrect guess. 
* Feedback needs to be given for when the player makes a guess.
* Statement for when the game ends. 
## The Result
The computer chooses a random word from a word listing. 
A hint is given through a display that shows the number of blank letters in the secret word. 

The game continues as long as there are blank characters or the player runs out of chances. 

Ascii art is used to visualize the number of chances the player has remaining after each guess. 

Prior guesses are also updated and displayed after each new guess.

Finally, a statement is made when the player wins by getting all the letters in the secret word or when they run out of chances. 

## The Process
The random module and two user defined modules containing ascii art and the word list are imported.

The computer selects a random word from the imported wordlist. 

A variable is then created containing a list of the total number of blank letters in the selected word. 

This list is designed to be displayed each time the player makes a guess. 

It is also updated and a letter is filled in each time the user makes a correct guess. 

A while loop is used to continue the game until the player has correctly guessed all the letters in the secret word or has run out of chances.

Each time the player makes an incorrect guess. 

A display utilizing the ascii art is shown to remind the player of how many lives they have remaining.
