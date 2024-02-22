# Guess-the-Number-Game_C

This is a simple number guessing game written in C. The program generates a random number between 1 and 100, and the player has to guess that number. The game provides hints whether the guessed number is higher or lower than the actual number.

## How to Play
1. Run the program.
2. The program will generate a random number between 1 and 100.
3. Guess the number and input your guess.
4. If your guess is higher than the actual number, the program will prompt you to guess a lower number.
5. If your guess is lower than the actual number, the program will prompt you to guess a higher number.
6. Keep guessing until you correctly guess the number.

#### Running the Program
Ensure you have a C compiler installed on your system. You can compile and run the program using a C compiler like GCC.

```bash
gcc -o guessthenumber.c
```

#### Requirements
- C compiler (e.g., GCC)

#### File Structure
- `guessthenumber`: Contains the source code of the number guessing game.

#### Note
- The game uses `srand()` and `rand()` functions to generate random numbers. These functions rely on the system time to seed randomness, making the generated numbers somewhat unpredictable.
- The game uses a do-while loop to continue prompting the user for guesses until they guess the correct number.

Enjoy playing the game and have fun guessing the number!
