# **Tic-Tac-Toe in Prolog** 🎮  

A simple **Tic-Tac-Toe** game implemented in **Prolog**, where two players take turns playing until a winner is determined or the game ends in a draw.

---

## **Features** ✨  
- Playable **2-player** Tic-Tac-Toe.  
- Board displayed in a **human-readable format**.  
- Automatic win/draw detection.  
- Simple **text-based user interface**.  

---

## **How to Play** 🎲  

### **1. Load the Game**  
Run the following command in your **Prolog interpreter** (e.g., SWI-Prolog):  
```prolog
?- [tic_tac_toe].   % Load the file (assuming it's named tic_tac_toe.pl)
```

### **2. Start the Game**  
```prolog
?- start.
```
The game will print the board and ask **Player X** to enter a move.

### **3. Enter Moves**  
Players take turns entering positions **(0-8)** corresponding to the board:  
```
 0 | 1 | 2  
---+---+---  
 3 | 4 | 5  
---+---+---  
 6 | 7 | 8  
```
For example, if Player **X** wants to play at position `0`, they enter:
```prolog
Player X, enter your move (0-8): 0.
```
The board updates, and **Player O** takes a turn.

---

## **Winning & Draw Conditions** 🏆  
- A player **wins** if they complete a row, column, or diagonal with their symbol (`X` or `O`).  
- If the board is **full** and no one wins, the game ends in a **draw**.  

---

## **Code Overview** 🛠  
The game logic is implemented in **Prolog** using the following key predicates:  

| Predicate      | Description |
|---------------|-------------|
| `start/0`    | Initializes the game. |
| `play/2`     | Handles player turns and checks game state. |
| `display_board/1` | Prints the board in a readable format. |
| `make_move/4` | Updates the board after a move. |
| `win/2`      | Checks if a player has won. |
| `draw/1`     | Checks if the board is full (game is a draw). |
| `switch_player/2` | Alternates between players (X and O). |

---

## **Future Improvements** 🚀  
✅ Add an **AI opponent** (Minimax algorithm).  
✅ Improve UI with a **graphical interface**.  
✅ Support **different board sizes** (e.g., 4x4).  

---

## **Contributing** 🤝  
Feel free to fork, modify, and submit pull requests! Contributions are welcome.  

---

## **License** 📜  
This project is open-source and licensed under the **MIT License**.  

---

Enjoy playing **Tic-Tac-Toe in Prolog**! 🎉🔴❌
