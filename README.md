# How-to-play
Here's how to play the Treasure Hunt Game:

### **Objective:**
Navigate a grid to find treasures (`T`), avoid traps (`X`), and collect power-ups (`+`). You need to do this while managing your health and moves. You win if you find all the treasures, or your score is calculated based on your performance when the game ends.

### **Game Setup:**
- The game takes place on a 5x5 grid.
- There are 3 treasures, 3 traps, and 2 power-ups randomly placed on the grid.
- You start with 3 health points and a total of 20 moves.
- The game runs in turns, with both you and the computer taking moves.

### **Game Controls:**
1. **Move Your Character (Player)**: 
   - Use the following keys to move:
     - `W` or `w` → Move **Up** (North).
     - `A` or `a` → Move **Left** (West).
     - `S` or `s` → Move **Down** (South).
     - `D` or `d` → Move **Right** (East).

2. **Actions When Moving**:
   - If you land on a treasure (`T`), you'll collect it and gain points.
   - If you land on a trap (`X`), you'll lose health. If you have a power-up (`+`), you can use it to avoid losing health.
   - If you land on a power-up (`+`), you collect it, which you can later use to survive traps.
   - If you land on an empty space (`.`), nothing happens.

3. **Computer Moves**:
   - The computer moves randomly after your turn and interacts with the grid (either finding a treasure, triggering a trap, or finding a power-up).

### **During the Game:**
- After each move, the grid is updated and displayed. You can see your current location, the computer's location, and which cells you have revealed.
- You'll be informed of what happens when you move:
  - You find a treasure or power-up.
  - You hit a trap, losing health or using a power-up to survive.
  - You land on an empty cell (nothing happens).
  
- The game continues for 20 moves or until you lose all your health.

### **Winning & Scoring**:
- **Win Condition**: If you find all 3 treasures, you win early and the game ends with a victory.
- **Scoring**: 
   - **Each treasure** you find gives you 10 points.
   - **Each power-up** gives you 5 points.
   - **Remaining health** gives you 10 points for each health point left.

### **End of the Game**:
- The game ends either when you find all the treasures or run out of moves or health. At the end, your score is displayed based on how many treasures you found, how many power-ups you collected, and how much health you had left.

---

### **Example of a Turn**:
1. The game shows the current state of the grid, your health, treasures found, and remaining moves.
2. You input your move (e.g., press `W` to move up).
3. The game updates the grid and tells you what happened (e.g., "You found a treasure!" or "You hit a trap!").
4. The computer makes its move, and the game continues.

---

### **Tips for Success**:
- **Move cautiously**: Keep track of where traps and treasures are based on what you've revealed.
- **Use power-ups wisely**: Power-ups can help you survive traps, so save them for critical situations.
- **Maximize your moves**: Make every move count to uncover more of the grid, find treasures, and avoid traps.

Now, go ahead and play! Have fun navigating the grid and collecting treasures!
