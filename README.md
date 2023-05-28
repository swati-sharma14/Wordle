# Wordle :abc:

The Wordle game recreated with Python, with an AI competing against the user. 

Made by Viviana Longjam, Siddhant Rai Viksit, and Swati Sharma as a part of their Introduction to Programming course under Professor Pankaj Jalote.

---

## :computer: Project Overview

Wordle is a Python-based implementation of the popular word-guessing game. It allows users to play against an AI opponent, testing their vocabulary and deduction skills. The game randomly selects a word from a pre-defined list, and the user needs to guess the word within a limited number of attempts. The AI opponent also attempts to guess the user's chosen word.

## :books: Dependencies

The game requires the following dependencies:

- Python 3.x
- `ai` module (provided)

## :floppy_disk: Installation

1. Clone the repository: `git clone https://github.com/your-username/wordle.git`
2. Navigate to the project directory: `cd wordle`
3. Run the game: `python wordle.py`

## :memo: Usage

1. When the game starts, you will see a series of underscores representing the hidden word.
2. Enter a letter to make a guess.
3. The AI will also make a guess.
4. If a letter is present in the word, it will be revealed in the correct position(s).
5. If a letter is not present, it will be marked as a wrong guess.
6. Keep guessing until you find the word or run out of attempts.
7. The AI will also keep guessing until it finds the word or runs out of attempts.
8. The game will end with a win or loss message.

## :open_file_folder: Word List

The game uses a pre-defined word list stored in a file called `words.txt`. The words in the list are randomly selected for each game session. You can modify the `words.txt` file to add or remove words as desired.

## :bulb: Tips

- Use your knowledge of common English words and letter frequency to make intelligent guesses.
- Pay attention to the revealed letters and adjust your strategy accordingly.
- Try to eliminate possibilities by avoiding redundant guesses.
- Enjoy the challenge and have fun!

---

Have fun playing Wordle! If you encounter any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.
