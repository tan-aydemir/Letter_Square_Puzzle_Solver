# LetterSquare Puzzle Solver

**Description:**

LetterSquare is a Java program that solves a word puzzle represented as a 3x3 square of letters on four sides. The goal is to find valid words using these letters, connecting them either horizontally or vertically, without reusing any letter. The program uses recursive backtracking to find solutions to the puzzle.

**Usage:**

1. Compile the code:

   ```bash
   javac LetterSquare.java
   ```

2. Run the program:

   ```bash
   java LetterSquare
   ```

3. Follow the prompts to enter the sides of the square:

   - Enter the top side (3 letters).
   - Enter the left side (3 letters).
   - Enter the right side (3 letters).
   - Enter the bottom side (3 letters).

4. The program will attempt to find valid words that can be formed using the letters on the sides. If it succeeds, it will display the solution(s).

**Word List File:**

The program uses a "word_list.txt" file as a dictionary to check the validity of words. You need to provide this file for the program to function. The "word_list.txt" file should contain a list of valid words, with one word per line.

Please make sure you have this file in the same directory as the program. This file is also provided in this repository. 

**Note:**

- Ensure that you have Java installed on your system to run the program.
- The program may find multiple solutions, so keep an eye on the output.

Feel free to reach out if you encounter any issues or have questions about the program. 
