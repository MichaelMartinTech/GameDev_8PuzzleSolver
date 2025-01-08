# 8 Puzzle Solver

A classic 8 Puzzle problem game, utilizing the Breadth-First Search (BFS) algorithm for assistance to find the optimal solution. 

---

## About the 8 Puzzle

The 8 Puzzle is a sliding puzzle consisting of a 3x3 grid with tiles numbered 1 through 8 and one empty space. 
The goal is to rearrange the tiles to match a specified goal state by sliding the tiles into the empty space.

---

## Features

- **Breadth-First Search (BFS) based assistance**:
  - Explores all possible moves level-by-level to ensure program-given solution.
  - Tracks the number of moves made to solve the puzzle.
  - Provides hints (Computer performed moves) for users who need assistance.
- **User-Friendly Output**:
  - Displays the sequence of moves leading to the solution.
  - Clearly visualizes the board's state during the solving process.
    
---

## How It Works

1. **Breadth-First Search (BFS)**:
   - Explores the puzzle's state space by visiting all neighboring states at the current depth before proceeding deeper.

  ![image](https://github.com/user-attachments/assets/83004fa6-b91a-4c84-a825-907e6f03504d)

2. **Move Tracking**:
   - Each move is stored in a list, enabling the program to reconstruct the sequence of actions leading to the solution.
3. **Hint System**:
   - Performs recommended move, helping users understand optimal strategies while counting the move towards 'Hints'.

---

## Usage

1. **Run the Solver**:
   - The program will start with the solution displayed.
![image](https://github.com/user-attachments/assets/38094e33-a6b1-44aa-b650-419385e2f688)
   
2. **Shuffle**:
   - Click the shuffle button, which will shuffle the puzzle. The user now can either solve the puzzle or ask for hints.
![image](https://github.com/user-attachments/assets/532c4af3-db8e-48c3-ab7b-24e3458f5db8)

     
3. **Solving, Hints, and Solutions**:
   - To move a piece, click it to move it to the nearest empty space. For a single hint, press the 'hint' button.
   - For solving the puzzle, press the 'Solve' button for the solution.

https://github.com/user-attachments/assets/54478f73-5865-4ddd-967e-0538906496ba

---

## Tools & Frameworks
**Language:** C#

**Engine:** Unity

---

## License

## All rights reserved. This code is proprietary and may not be copied, distributed, or used without explicit permission from the owner.

---
