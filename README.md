# Terminal Tetris in Python

A fully featured, colorful Tetris clone that runs directly in the Windows terminal using the curses library. 

## Features
* **Modern Mechanics:** 7-bag randomizer, Ghost pieces, and Wall kicks.
* **UI Elements:** Hold piece queue, Next piece preview, and Score/Level tracking.
* **Visuals:** Solid color-coded blocks and terminal border rendering.
* **Speed Scaling:** Game speeds up progressively as you clear lines and level up.

## Prerequisites
If running on Windows, you must install the Windows port of the curses library:
\\\ash
pip install windows-curses
\\\

## How to Play
Run the script in your terminal:
\\\ash
python tetris.py
\\\

## Controls
* **Left / Right Arrows:** Move piece
* **Up Arrow:** Rotate piece
* **Down Arrow:** Soft Drop
* **Spacebar:** Hard Drop
* **C or H:** Hold piece
* **Q:** Quit game
