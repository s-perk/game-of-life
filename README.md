# game-of-life

Inspired by NeuralNine's video:
https://youtu.be/cRWg2SWuXtM

# Rules for Game of Life

## Definitions

**0** = Dead (black)
**1** = Alive (white)
**neighbors** = cell immediately next to it in every direction, including diagonals

- up, down, left, right
- up-left, up-right, down-left, down-right

1. **Birth Rule:** Any _dead cell_ with _exactly 3 live neighbors_ will become live in next generation
2. **Death Rule:**

- _Isolation:_ Any _live cell_ with _<=1 live neighbors_ will die
- _Overcrowding:_ any _live cell_ with _4+ live neighbors_ will die next generation

3. **Survival Rule:** Any _live cell_ with _2-3 live neighbors_ will remain alive in next generation

# Instructions

**Activate VM:** source .venv/bin/activate
**Run:** python app.py

# Controls

**Pause:** spacebar
**Clear screen**: c
