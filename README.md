# Conways Game of Life in Python 3

The Game of Life, also known simply as *Life*, is a cellular automaton. Based on simple rules, cells can live, die, or revive their neighbors.
![simmulation](https://github.com/user-attachments/assets/91290d45-d57a-4012-93bd-0f38d4d54ab2)

## Rules

Cells in *Life* are elements of $\mathbb{Z}^2$, and their *neighbors* are the eight adjacent points, horizontally, vertically, or diagonally. Each cell can be either *alive* or *dead*. At each step in time, the state of a cell can change based on the following rules:


- Any live cell with fewer than two live neighbours dies, as if by underpopulation.
- Any live cell with two or three live neighbours lives on to the next generation.
- Any live cell with more than three live neighbours dies, as if by overpopulation.
- Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.

Generation 0 is known as the *seed* of the system, and each new generation is created by applying these rules to the previous generation. As new generations arise, different types of patterns may appear. For further information, you can refer to [this article](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life).

## Getting Started

### Prerequisites

- Python3
- Tkinter

### Installation

1. Clone the repository:
```
git clone https://github.com/your-username/conways-game-of-life.git
```
2. Grant run permission to 'run.sh':
```
chmod +x run.sh
```
3. Execute 'run.sh' to start:
```
./run.sh
```

### Controls:
- *Right click* to toggle a cell in the grid
- *Left-click drag* to pan
- *Mouse wheel* to zoom
- *Double left click* to start simulation
- *Ctrl + left click* to restart simulation
- *Shift + left click* to pause simulation

**Warning:** Tkinter window will not close if the simmulation is running.
