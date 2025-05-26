Before running the game, make sure you have the following environment setup:

1. Python

2. Tkinter (usually comes pre-installed with Python)

This Tetris game includes FOUR additional fun and challenging modes that put a creative twist on the classic gameplay.

You can also try running the AI versions in the AI folder to see how well the automated player performs — watch it rack up scores without human input!

## File Guide
| File Name            | Description                                                                                          |
| -------------------- | ---------------------------------------------------------------------------------------------------- |
| `game.py`            | Classic Tetris game using Tkinter – the base version.                                                |
| `01_damage mode.py`  | "Endgame" mode – blocks fill the bottom half of the board initially, increasing difficulty.          |
| `02_Float mode.py`   | "Floating" mode – blocks left on the board shift left after a piece lands.                           |
| `03_Up mde.py`       | "Upward float" mode – garbage rows rise from the bottom at intervals.                                |
| `04_Hidden mode.py`  | "Hidden bottom" mode – blocks at the bottom are hidden and only shown briefly after landing a piece. |
| `tetris_by_class.py` | AI-controlled Tetris – generates pieces and calculates best placements using scoring heuristics.     |
| `multi_tetris.py`    | Multi-block AI Tetris – spawns multiple pieces and automates placement with planning.                |
| `util.py`            | Utility functions and shared AI logic, including scoring, movement, and collision checks.            |
