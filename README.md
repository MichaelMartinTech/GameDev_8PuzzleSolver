# 8 Puzzle Solver
**Author:** Michael R. Martin

**Uploaded:** Sep 18, 2023

Solver for the classic 8 Puzzle problem, utilizing **Breadth-First Search (BFS)** and the **Manhattan Distance heuristic**. 
This program tracks user and Computer-Performed moves, offering hints to guide players towards solving the puzzle.

---

## About the 8 Puzzle

The 8 Puzzle is a sliding puzzle consisting of a 3x3 grid with tiles numbered 1 through 8 and one empty space.  
The objective is to rearrange the tiles to match a specified goal state by sliding tiles into the empty space.

---

## Features

- **Breadth-First Search (BFS) Assistance**:
  - Explores all possible moves level-by-level to ensure the shortest solution.
  - Incorporates **Manhattan Distance** as a heuristic to evaluate board states, optimizing traversal by prioritizing moves closer to the goal.
  - Tracks number of moves made to solve the puzzle and displays hints when needed.

- **Hint System**:
  - Computer uses the Manhattan Distance heuristic to suggest optimal moves to help players progress when stuck.
  - Hints count as moves toward solving the puzzle.

- **User-Friendly Output**:
  - Displays the current board state and tracks move history.
  - Visualizes the sequence of moves leading to the solution.

---

## How It Works

1. **Breadth-First Search (BFS)**:
   - Explores the puzzle's state space by visiting all neighboring states at the current depth before proceeding deeper.
   - Prioritizes moves using **Manhattan Distance**, which calculates the total distance of tiles from their goal positions to guide search.

   ![BFS Example](https://github.com/user-attachments/assets/83004fa6-b91a-4c84-a825-907e6f03504d)

2. **Move Tracking**:
   - Each move is stored in a list, allowing the program to reconstruct the sequence of actions leading to the solution.

3. **Hint System**:
   - Performs a recommended move based on Manhattan Distance.

---

## Usage

1. **Run the Solver**:
   - The program will start with the solution displayed.
![Initial solution](https://github.com/user-attachments/assets/38094e33-a6b1-44aa-b650-419385e2f688)
   
2. **Shuffle**:
   - Click the shuffle button, which will shuffle the puzzle. The user now can either solve the puzzle or ask for hints.
![Shuffle ](https://github.com/user-attachments/assets/532c4af3-db8e-48c3-ab7b-24e3458f5db8)

     
3. **Solving, Hints, and Solutions**:
   - To move a piece, click it to move it to the nearest empty space. For a single hint, press the 'hint' button.
   - For solving the puzzle, press the 'Solve' button for the solution.

[Solving demo](https://github.com/user-attachments/assets/54478f73-5865-4ddd-967e-0538906496ba)



---

## Tools & Frameworks

- **Language**: C#  
- **Engine**: Unity

---

## License
## All rights reserved. This code is proprietary and may not be copied, distributed, or used without explicit permission from the owner.
