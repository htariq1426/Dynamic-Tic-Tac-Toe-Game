# Dynamic Tic-Tac-Toe Game

A simple yet customizable Tic-Tac-Toe game built in Python while learning the language. Inspired by [Sentdex's YouTube series](https://www.youtube.com/playlist?list=PLQVvvaa0QuDeAams7fkdcwOGBpGdHpXln), this version includes additional features, such as handling game termination in the event of a draw, which was missing in the original code.

## Features
- Dynamic board size (not limited to 3x3)
- Enhanced game logic for detecting a draw
- Command-line interface with colored output (via `colorama`)

## Prerequisites
Ensure you have **Python 3.12.2** installed on your system. You can download it from [python.org](https://www.python.org/downloads/release/python-3122/).

## Installation

### 1. Clone the Repository
```sh
git clone https://github.com/htariq1426/Dynamic-Tic-Tac-Toe-Game.git
cd Dynamic-Tic-Tac-Toe-Game
```

### 2. Install Required Packages
This project requires `itertools` (which is included in Python's standard library) and `colorama`. To install `colorama`, run:
```sh
pip install colorama
```

## Running the Game
Execute the following command in your terminal:
```sh
python tic_tac_toe.py
```
Follow the on-screen prompts to set the board size and play the game.

## Improvements Over Sentdex's Version
- **Fixed missing draw condition**: The original code did not handle game termination when there was a draw. This has been added.
- **Refactored and optimized some parts**: Improved code readability and modularization.

## Credits
- Inspired by Sentdex’s tutorial series: [Learning to program with Python 3 (py 3.7)](https://www.youtube.com/playlist?list=PLQVvvaa0QuDeAams7fkdcwOGBpGdHpXln)

