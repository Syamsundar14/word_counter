# word_counter
# Word Counter Program

This Python program counts the number of words in a given text input (sentence or paragraph). It provides a user-friendly command-line interface.

## Project Overview

This project was developed to demonstrate core Python programming concepts, including:

* Input Handling
* String Manipulation
* Function Creation
* Basic Control Flow (loops and conditional statements)
* Output Display
* Error Handling
* User-Friendly Interface

## Features

* **Counts Words:** Accurately counts the number of words in a given string.
* **Handles Empty Input:** Gracefully handles cases where the user provides empty or whitespace-only input.
* **Error Handling:** Includes a `try...except` block to catch and handle potential errors during input or processing.
* **Multiple Inputs:** Allows the user to count words for multiple inputs without rerunning the program.
* **Exit Option:** Provides a way for the user to exit the program by typing 'exit'.
* **Clear Output:** Displays the word count in a user-friendly format.
* **Well-Commented Code:**  The code is thoroughly commented to explain each step.

## How to Use

1. **Save the Code:** Save the Python code as a `.py` file (e.g., `word_counter.py`).
2. **Run from the Command Line:** Open a terminal or command prompt and navigate to the directory where you saved the file.
3. **Execute the Script:** Run the script using the command: `python word_counter.py`
4. **Enter Text:** The program will prompt you to enter a sentence or paragraph.
5. **View the Count:** The program will display the word count.
6. **Multiple Inputs:** You can enter multiple texts to count.
7. **Exit:** To exit the program, type `exit` (case-insensitive) when prompted for input.


Test Cases
The program has been implicitly tested with various inputs, including:

Empty strings
Strings with only whitespace
Single words
Multiple words
Sentences
Paragraphs
Input with leading/trailing spaces (handled correctly)
Future Improvements (Optional)
Punctuation Handling: The current implementation treats words with punctuation attached (e.g., "word!") as a single word. Future versions could be improved to handle punctuation separately if needed.
Unit Tests: Adding formal unit tests would improve the reliability of the code.
GUI: A graphical user interface could be developed to make the program even more user-friendly.
