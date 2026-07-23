# 🎮 2048 Game using Python & Tkinter

A simple implementation of the popular **2048 Puzzle Game** developed using **Python** and **Tkinter**.

The game allows players to combine numbered tiles by moving them in four directions until they create the **2048 tile**.

---

## 📸 Screenshot

![image alt](https://github.com/tushar18-2006/2048-Python-Tkinter-Game/blob/80d2695e8e8dcc24bdc2d0b0c944d80b68986758/2048-Game.png)

---

## ✨ Features

- Clean graphical interface using Tkinter
- 4 × 4 game board
- Arrow key movement
- WASD support
- IJKL support
- Automatic tile generation
- Tile merging logic
- Win detection (2048)
- Lose detection
- Undo previous move (Press **B**)
- Escape key to quit

---

## 📂 Project Structure

```
2048-Python-Tkinter-Game/
│
├── constants.py
├── logic.py
├── puzzle.py
├── images/
│   └── game.png
├── README.md
└── LICENSE
```

---

## 🛠 Technologies Used

- Python 3.x
- Tkinter (GUI)
- Random Module

---

## 🎮 Controls

| Key | Action |
|------|---------|
| ↑ | Move Up |
| ↓ | Move Down |
| ← | Move Left |
| → | Move Right |
| W A S D | Alternative Controls |
| I J K L | Alternative Controls |
| B | Undo Last Move |
| Esc | Exit Game |

---

## ▶️ How to Run

### Clone Repository

```bash
git clone https://github.com/tushar18-2006/2048-Python-Tkinter-Game.git
```

### Open Project

```bash
cd 2048-Python-Tkinter-Game
```

### Run

```bash
python puzzle.py
```

---

## 🧠 Game Rules

- Every move creates a new tile (2).
- Merge identical tiles to create larger numbers.
- Reach **2048** to win.
- If no moves remain, the game ends.

---

## 📁 Files Description

### constants.py
Contains:
- Colors
- Fonts
- Window Size
- Keyboard Controls

### logic.py
Contains all game logic:
- New Game
- Tile Generation
- Movement
- Merge
- Reverse
- Transpose
- Win/Lose Detection

### puzzle.py
Contains:
- Tkinter GUI
- Keyboard Event Handling
- Grid Updates
- Game Window

---

## 🚀 Future Improvements

- Score Counter
- High Score Saving
- Restart Button
- Sound Effects
- Animations
- Dark Mode
- AI Auto Player
- Responsive Window

---

## 👨‍💻 Author

**Tushar Harihar**

Bachelor of Computer Applications (BCA)

---

⭐ If you like this project, don't forget to Star the repository!
