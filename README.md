# The Pong Game 🏓

A two-player Pong game built with Python's Turtle graphics module. Each player controls a paddle and tries to get the ball past their opponent. The first player to reach 10 points wins.

## Features

- Two-player gameplay on one keyboard
- Paddle movement using keyboard controls
- Ball movement and bouncing off the top and bottom walls
- Score tracking for both players
- Ball speed increases after paddle collisions
- Automatic winner announcement when a player reaches 10 points

## Built With

- **Python** — game logic
- **Turtle** — graphics, movement, and keyboard input
- **Time** — controls the delay between ball movements

## Getting Started

### Requirements

- Python 3 installed on your computer
- No additional packages required; the project uses Python's built-in `turtle` and `time` modules.

### Run the Game

1. Clone or download this repository.
2. Open a terminal in the project folder.
3. Run:

   ```bash
   python3 main.py
   ```

## How to Play

**Left player**
- `W` — Move up
- `S` — Move down

**Right player**
- `Up Arrow` — Move up
- `Down Arrow` — Move down

Each time the ball passes a player's side, the other player earns a point. The first player to reach 10 points wins.

## Project Structure

- **`main.py`** — Creates the game window, handles keyboard controls, runs the game loop, checks collisions, and determines the winner.
- **`ball.py`** — Controls ball movement, bouncing, speed changes, and resetting the ball after a point.
- **`paddle.py`** — Creates the paddles and defines their up-and-down movement.
- **`scoreboard.py`** — Tracks and displays both players' scores and announces the winner.
- **`.gitignore`** — Specifies files and folders Git should ignore, including Python cache files.

## What I Learned

Building this project helped me practise Python classes, object-oriented programming, keyboard event handling, game loops, collision detection, and score management. It also helped me understand how to split a program into multiple files, with each class responsible for a specific part of the game.
