# 2048 Game

A browser-based implementation of the popular 2048 puzzle game, built with HTML, CSS, and JavaScript.


## Description

This is a clone of the addictive sliding tile puzzle game 2048, originally created by Gabriele Cirulli. The objective is to combine tiles with the same numbers to create a tile with the value 2048.

## How to Play

1. Use your arrow keys (←, →, ↑, ↓) to move all tiles in the specified direction.
2. When two tiles with the same number touch, they merge into one tile with twice the value.
3. After each move, a new tile with a value of 2 appears in a random empty spot on the board.
4. The game continues until you either:
   - Create a tile with the value 2048 (win)
   - Fill the entire board with no possible moves left (lose)

## Features

- Responsive design that works on both desktop and mobile devices
- Clean, modern UI with smooth animations
- Score tracking
- Game over and win condition detection

## Project Structure

```
2048-game/
├── index.html      # Main HTML structure
├── style.css       # CSS styling
├── script.js       # Game logic
└── README.md       # This file
```

## Technical Implementation

- The game board is represented as a 4x4 grid of div elements.
- Tile movement and combinations are handled with array manipulations.
- Game controls are implemented using keyboard event listeners.
- CSS is used for responsive design and tile styling based on their values.

## Future Enhancements

- Add local storage to save high scores
- Implement touch swipe controls for mobile devices
- Add undo functionality
- Add animation for tile movement and merging
- Create a proper restart button instead of page refresh

