# Number-Guessing-Game
This repo consists of a number guessing game.

To play the game:
- Clone this Repo.
- Make sure you have Visual Studio installed.
- Open the .sln file in: ...\Number-Guessing-Game\NumberGuessingGame ("..." being where you saved the Repo).
- Click Build > Build NumberGuessingGame.

- In File Explorer, navigate to where you cloned the Repo
- Go to : ...\Number-Guessing-Game\NumberGuessingGame\NumberGuessingGame\bin\Debug\netcoreapp3.1
- Run the .exe to play.

Alternatively, after opening the .sln file in Visual Studio, just click Ctrl + F5.

# Playing the Game

- The game will select a number between 0 and 100.
- Your goal is to guess what this number is.
- The game will ask you to choose a number between 0 and 100.
- Type your answer.
- The computer will tell you if your number was too high, too low, or the correct choice.
- If you did not guess the number correctly, you will then be given the opportunity to choose a new number.
- The computer will again compare this with the originally chosen number.
- You will continue to be given clues until you choose the correct number.
- When you choose the correct number, you win!
- You can then close the game.

# Project Notes
This project uses C# in a ConsoleApplication.
I make use of a Random Number Generator to choose a random number for the player to guess.
The computer does a comparative analysis using a nested if statment inside of a do-while loop to determine the player's success.
