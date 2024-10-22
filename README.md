# Chess Browser Game

## Overview
Welcome to the Chess Browser Game! This is a simple implementation of chess that can be played in a web browser. The game features a functional chessboard, a reset button to restart the game, and a display to indicate whose turn it is.

## Features
- **Interactive Chessboard**: Play chess with functional pieces and moves.
- **Turn Indicator**: Always know which player’s turn it is (White or Black).
- **Reset Button**: Quickly reset the game at any point.

## How to Play
1. Load the game in your browser.
2. Make moves by clicking on pieces and their destination squares.
3. White moves first, followed by Black. The game will indicate whose turn it is.
4. Click the Reset button to start a new game anytime.

## Project Structure

### HTML
In the HTML file, you will find the following elements:
- **Title**: Displays the name of the game.
- **Chessboard**: A grid representing the chessboard with clickable squares.
- **Reset Button**: A button to reset the game and start over.
- **Turn Indicator**: Text showing which player's turn it is (White/Black).

### CSS
In the CSS, the chessboard and game are styled to give it a classic look:
- **Chessboard Styling**: Styles for the grid, alternating colors for squares, and responsive design.
- **Game Styling**: Layout for the game interface, including the reset button and turn display.

### JavaScript
The JavaScript file contains the game logic:
- **Chessboard Setup**: Initializes the pieces and places them on the board.
- **Turn Management**: Keeps track of whose turn it is and alternates between White and Black.
- **Piece Movement**: Handles the movement of pieces based on valid chess moves.
- **Reset Functionality**: Resets the board to the starting position when the reset button is clicked.

#### Game Logic Includes:
- Valid moves for each chess piece (king, queen, rook, knight, bishop, and pawn).
- Basic game rules such as alternating turns and moving pieces.
- Reset functionality to start a new game.

## Installation

Clone this repository to your local machine:

```bash
git clone https://github.com/AleksBulajic/chess-browser-game
