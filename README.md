# Tic-Tac-Toe-Assembly
This project is a simple implementation of the Tic Tac Toe game written in **8086 Assembly Language**. It allows two players to play the game in a terminal, where the board updates dynamically, and the winner is declared based on the standard Tic Tac Toe rules.

#Features

- Two-player Tic Tac Toe game.
- Dynamic board update.
- Win condition checks for rows, columns, and diagonals.
- Displays the winner or a draw when the game ends.
- Written entirely in assembly for educational purposes.

#How to Run

1. Install an 8086 emulator, such as [EMU8086](https://emu8086.com/) or [DOSBox](https://www.dosbox.com/).
2. Copy the code into a file with the `.asm` extension (e.g., `tictactoe.asm`).
3. Compile and run the file using the emulator:
   - For EMU8086:
     - Open the `.asm` file in EMU8086.
     - Assemble and run the program.
   - For DOSBox:
     - Assemble the program using a tool like MASM:
       ```bash
       masm tictactoe.asm
       ```
     - Link the file:
       ```bash
       link tictactoe.obj
       ```
     - Run the program:
       ```bash
       tictactoe.exe
       ```

---

## File Description

- **`tictactoe.asm`**: The main assembly program containing the game logic.
- **`README.md`**: Documentation for the project.

---

## Game Instructions

1. The game starts by displaying the welcome screen and the Tic Tac Toe board.
2. Players take turns to choose a position on the board (1-9).
3. The board updates dynamically after each move.
4. The game ends when a player wins or the board is full.

---

## Contribution

Feel free to contribute to this project by:
- Adding more features (e.g., better UI or AI opponent).
- Improving the code structure.
- Fixing bugs.

To contribute:
1. Fork this repository.
2. Create a new branch for your feature or fix:
   ```bash
   git checkout -b feature-name
