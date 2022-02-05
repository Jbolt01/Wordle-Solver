# Wordle-Solver
---
### Vijay Shanmugam

This is a basic cli tool that attempts to solve a [Wordle](https://www.powerlanguage.co.uk/wordle/) puzzle.

## Running
The program is written in Haskell and uses Cabal for building.
You should be able to run it with:
```
cabal run
```

## Usage
The program will display a word for you to enter into the wordle puzzle.  Once the puzzle gives you the colors for each letter, you need to tell the program those colors using a key where gray is represented by a `.`, yellow is represented by a lowercase character, and green is represented by an uppercase character.

![Wordle Guess](wordle_guess.png)
In order to tell the program these colors and letters, you would input `.RI.e`.

## Strategy
Starts with frequency list of letters and words in the wordle wordlist.  Creates restrictions on suggested words as more information is gained during the puzzle.  I will add a more in-depth explanation here in the future.