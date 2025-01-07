Guess the Number Game (C++)


A simple console-based game written in C++ where the player has to guess a randomly generated number within a given range. The game provides feedback on whether the guess is too high, too low, or correct.

Features
Random Number Generation: The program generates a random number between a specified range (e.g., 1 to 100).
User Input: The player inputs their guesses.
Feedback: The game gives feedback on whether the guess is too high, too low, or correct.
Attempts Counter: The game tracks and displays the number of attempts it took to guess the number correctly.
Replay Option: After guessing the correct number, the player can choose to play again.
Requirements
C++ Compiler: A C++ compiler (e.g., GCC, Clang, or MSVC) to compile the program.
Operating System: Works on Windows, Linux, and macOS systems.
Standard Libraries: Uses the C++ standard library (iostream, cstdlib, etc.).
How to Play
The game generates a random number between a predefined range (e.g., 1-100).
The player guesses a number.
After each guess, the game tells the player if their guess is too high, too low, or correct.
The player is asked if they want to play again after guessing the correct number.
Running the Game
1. Clone this repository or download the source code.
bash
Copy code
git clone https://github.com/your-username/guess-the-number.git
cd guess-the-number
2. Compile the code using a C++ compiler.
For GCC (Linux/macOS):

bash
Copy code
g++ -o guess_the_number guess_the_number.cpp
For MSVC (Windows):

bash
Copy code
cl guess_the_number.cpp
3. Run the compiled program.
On Linux/macOS:

bash
Copy code
./guess_the_number
On Windows:

bash
Copy code
guess_the_number.exe
Example Game Flow
vbnet
Copy code
Welcome to 'Guess the Number'!
I have selected a number between 1 and 100. Can you guess what it is?

Enter your guess: 50
Too high! Try again.

Enter your guess: 30
Too low! Try again.

Enter your guess: 40
Congratulations! You've guessed the correct number in 3 attempts.

Do you want to play again? (yes/no)
Code Overview
Here’s a brief overview of how the program works:

Random Number Generation: rand() function is used to generate a random number between the range (e.g., 1 to 100).
User Input: The program asks for user input using cin and compares it with the randomly generated number.
Feedback: After each guess, the program checks if the guess is higher, lower, or correct, and provides appropriate feedback.
Replay: After guessing the number, the player is prompted to decide if they want to play again.
