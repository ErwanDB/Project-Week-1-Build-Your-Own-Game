<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Mastermind
*Erwan de Boisjolly*

*Data Analytics - June, Barcelona*

## Content
- [Project Description](#project-description)
- [Rules](#rules)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
I choose to create a Mastermind game because it's a game I know well for having played often when I was a kid.

## Rules
The Mastermind is a code breaking game for two players: one player becomes the codemaker, the other the codebreaker.

The codemaker chooses a pattern of four colour code/marks. Duplicates and blanks are allowed depending on player choice, so the player could even choose four code pegs of the same color or four blanks. In the instance that blanks are not elected to be a part of the game, the codebreaker may not use blanks in order to establish the final code. The chosen pattern is hidden from the codebreaker but visible by the codemaker.

The codebreaker tries to guess the pattern, in both order and color, within eight to twelve turns.

Each guess is made by placing a row of code pegs on the decoding board. Once placed, the codemaker provides feedback by indicating from zero to four key pegs in the small holes of the row with the guess. A red key peg is placed for each code peg from the guess which is correct in both color and position. A white key peg indicates the existence of a correct color code peg placed in the wrong position.

If there are duplicate colours in the guess, they cannot all be awarded a key peg unless they correspond to the same number of duplicate colours in the hidden code. For example, if the hidden code is blue-blue-green-green and the player guesses blue-blue-blue-green, the codemaker will award two red key pegs for the two correct blues, nothing for the third blue as there is not a third blue in the code, and a red key peg for the green. No indication is given of the fact that the code also includes a second green.

Once feedback is provided, another guess is made; guesses and feedback continue to alternate until either the codebreaker guesses correctly, or twelve (or ten, or eight) incorrect guesses are made.

## Workflow
1. Create a list of colours available

2. Define max number of rounds

3. Define a variable for one round

4. Generate random hidden combination

5. Create a function to ask the player his guess of the combination

6. Create a function to provide challenger feedback

7. Create a function for round execution and update the round result

8. Iterate rounds until player wins or max number of rounds reached

## Organization
I used a Trello board to organize my project. A screenshot of the Trello board is available in the repository.

The repository is composed of the below list of file:

- Jupiter Notebook with python code of the game: *Mastermind.ipynb*
- The current README file: *README.md*
- The presentation of the project: *Presentation_Mastermind-project.pdf*
- An image of the game board: *Mastermind-For-Kids_02.jpg*
- A screenshot of my Trello board: *Trello_board.png*

## Links


[Repository](https://github.com/ErwanDB/Project-Week-1-Build-Your-Own-Game.git)  