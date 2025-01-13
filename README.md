# Hangman Game (Java Edition)

This is a graphical Hangman game built using Java Swing. The game randomly selects a word from a predefined dataset, hides it, and allows the player to guess letters to reveal the hidden word. The goal is to guess the word before making too many incorrect guesses.

## Features

- User-friendly graphical interface.
- Dynamic word categories and challenges.
- Custom fonts, colors, and images.
- Supports reset and restart functionality.

## Prerequisites

- Java Development Kit (JDK) 8 or later.
- A text editor or IDE (e.g., IntelliJ IDEA, Eclipse, or VS Code).

## Setup Instructions

1. **Clone the repository** or download the source code.

2. **Resources Folder**:
   Ensure the following folder structure exists in your project directory:
   ```
   resources/
   ├── data.txt            # Contains categories and words for the game.
   ├── 1.png               # Initial Hangman image.
   ├── 2.png               # Second Hangman image (for incorrect guesses).
   ├── 3.png               # Third Hangman image.
   ├── ...                 # Additional images as needed.
   ├── Cartoonero.ttf      # Custom font used in the game.
   ```

3. **Add resources to classpath**:
   Ensure the `resources/` folder is on your classpath so that the application can access the files correctly.

4. **Run the application**:
   - Compile the project using your IDE or the command line.
   - Execute the `App` class to start the game.

## File Descriptions

### `App.java`
The entry point of the application that initializes and displays the game window.

### `CommonConstant.java`
Contains configuration constants such as file paths, colors, and dimensions.

### `CustomTools.java`
Utility class for handling fonts, images, and word masking.

### `Hangman.java`
Main game logic and graphical user interface.

### `WordDB.java`
Handles word categories and challenges by reading from `data.txt`.

## Running the Game

1. Launch the application by running the `App` class.
2. Use the letter buttons to guess the word.
3. You have six chances to guess incorrectly before the game ends.
4. Use the **Reset** or **Restart** button to play again.

## Screenshots

Include screenshots of the application here if needed.

## Notes

- The `data.txt` file must follow the format: `Category,Word1,Word2,...`.
- Ensure all resource paths are correct, especially for custom fonts and images.

---

For questions or contributions, feel free to reach out or fork the repository.
