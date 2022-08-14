# snake-game

Snake in Lua using LOVE2D. Code and instructions provided by https://simplegametutoarials.github.io/love/snake/18.html. 

The intention is to create a proof-of-concept game from which to build on and explore the use of A.I. to train a snake algorithm.

## Setup
Ensure Lua 5.4.x and LOVE2D are installed.

Clone and enter the repository:
```
git clone https://github.com/patrickm663/snake-game.git
cd snake-game
```

Run the `.lua` files found in `src/` using `love`:
```lua
love src/
```

## How to Play
The snake is controlled by either WASD or directional keys. Eating an apple (marked in red) grows the snake by one segment. If the snake crosses its own path, the snake dies and the game is reset.

## TODO
[] - Add sound
[] - Add a main menu
[] - Add varying difficulties
[] - Fix aspect ratio
[] - Add levels
[] - Add splash screen following win/loss
[] - Add scoreboard
[] - Add A.I. mode
[] - Add two-player mode
