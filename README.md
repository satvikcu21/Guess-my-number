# Guess-my-number

**Project Report: Guess My Number Game**

**Objective**

The objective of this project is to create a number guessing game where the user tries to guess a secret number between 1 and 20. The game provides feedback on whether the guess is too high, too low, or correct. The user's score is updated based on their guesses, and they can restart the game using the "Again!" button.

**Functionality Overview**
The application includes:

A header with the game title and information about the number range.

An input field for the user to enter their guesses.

Buttons to submit a guess ("Check!") and to restart the game ("Again!").

Display areas for the current message, score, and high score.

**Implementation Details**

1.**HTML Structure**:

   Header: Contains the game title and the current secret number display.
   
   Main Sections: Divided into left and right sections:
   
   Left Section: Contains the input field for guesses and the "Check!" button.
   
   Right Section: Displays the game message, current score, and high score.
   
2.**CSS (style.css):**

    Basic styling to format the game layout and appearance.
   
    Ensures readability and user-friendly interface.
   
3.**JavaScript (script.js):**

 **Event Listeners:**
 
   Listens for clicks on the "Again!" button to reset the game.
   
   Listens for clicks on the "Check!" button to validate the user's guess.
   
**Game Logic:**
  
   Initializes the game with a random secret number between 1 and 20.
   
  Tracks the user's score and updates it based on correct or incorrect guesses.
   
   Provides feedback to the user on their guesses (too high, too low, or correct).
   
   Updates the display dynamically to reflect changes in the game state (score, high score, message).

**Previews**

![Screenshot 2024-02-04 122305](https://github.com/satvikcu21/Form-validation/assets/150938638/fa62d381-904d-457b-a5a7-163e3f692df2)


![Screenshot 2024-06-25 193840](https://github.com/satvikcu21/Form-validation/assets/150938638/77d1a669-4406-491c-9358-aed4ea7b713b)
