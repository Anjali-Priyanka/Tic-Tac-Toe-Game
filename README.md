# Tic-Tac-Toe-Game

# 🎮 Tic-Tac-Toe Game

A simple and interactive **Tic-Tac-Toe** game built using **HTML**, **CSS**, and **JavaScript**. This two-player game allows players to alternate turns, detect wins or draws automatically, and reset the game with a single click. It features a responsive design and real-time feedback for smooth gameplay.

---

## 📌 Objective

To create a web-based Tic-Tac-Toe game where:
- Two players take turns marking X and O
- The game automatically detects wins and draws
- Players can reset the game to play again

---

## 📷 Output Preview

- ✅ Real-time turn display
- ✅ Automatic win/draw detection
- ✅ Reset button for new games
- ✅ Responsive 3x3 grid layout

---

## ✅ Features

### 🎯 Core Functionality

1. **Grid Layout**  
   - A 3x3 board created using HTML and styled with CSS

2. **Turn-Based Play**  
   - Alternates turns between Player **X** and Player **O**

3. **Win Detection**  
   - Checks all possible winning combinations (rows, columns, diagonals)

4. **Draw Condition**  
   - Displays a message if all cells are filled and no winner

5. **Reset Button**  
   - Clears the board and restarts the game

---

## 💻 Tech Stack

- **HTML**: Structures the game grid and controls
- **CSS**: Styles the board, ensures responsiveness and highlights
- **JavaScript**: Handles the game logic and interactivity

---

## 🛠 Implementation Guide

### Step 1: Build the Game Layout (HTML)
- Create a 3x3 grid using `div` elements
- Add a status display (`"Player X's turn"`, etc.)
- Include a **Reset** button

### Step 2: Style the Game (CSS)
- Use **CSS Grid** or **Flexbox** for the layout
- Highlight winning cells
- Make the board responsive for mobile and desktop

### Step 3: Add Functionality (JavaScript)
- Track whose turn it is (`X` or `O`)
- On click:
  - Update the cell with the current symbol
  - Check for a win or draw
  - Switch player turn
- Display messages like "Player X Wins!" or "It's a Draw!"
- Reset the board and game state on button click

---

## 📦 Sample JavaScript Snippet

```javascript
function checkWin() {
  // Check all possible winning combinations
}

function handleClick(event) {
  // Mark the cell, check for win/draw, and switch turn
}

function resetGame() {
  // Clear the board and reset state
}
