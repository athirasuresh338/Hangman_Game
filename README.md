# 🌸 Hangman Game - Floral Edition 🌸

## Overview  
This is a fun, interactive **Hangman Game** where the hidden word is a type of **flower**. Players must guess the letters of the word, with each incorrect guess bringing the hangman closer to being fully drawn. You have a limited number of attempts to guess the word before the game ends.

## Features  
- 🌸 **Floral Vocabulary**: The hidden words are names of various flowers like **rose**, **lily**, **tulip**, and more.  
- ⚖️ **Visual Hangman Display**: A hangman figure is progressively drawn with each wrong guess.  
- 🎮 **Interactive Gameplay**: Players guess letters to reveal the word, with real-time feedback on each guess.

## How to Play  
1. Start the game and guess one letter at a time.  
2. If the guessed letter is part of the word, it will be revealed.  
3. If the letter is not part of the word, the hangman figure will be drawn, and you lose one attempt.  
4. The game ends when you either guess the word correctly or run out of attempts.

## Game Rules  
- You have **6 attempts** to guess the word.
- The word is related to a **type of flower**.
- **Incorrect guesses** lead to the progressive drawing of the hangman.

## Code Breakdown  
- **flowers**: A list of flower names used as potential hidden words.  
- **hangman_display(attempt)**: A function that returns a visual representation of the hangman based on the remaining attempts.  
- **Game Loop**: Manages the game flow, including player input, updating game state, and providing feedback.

## Example of Gameplay  
When you start the game, you'll be asked to guess letters. If you make an incorrect guess, you'll see the hangman figure progressively drawn:

```
Guess a letter: t
Good guess! Keep going.

Word: t _ _ _ _

Guess a letter: r
Wrong guess! Try again.
```

The game continues until you either guess the word correctly or the hangman is fully drawn.

## Installation  
To play this game, simply run the Python script on your machine.

---  

Enjoy the game and good luck guessing those flowers! 🌸
