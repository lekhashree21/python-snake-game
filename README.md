#  Python Snake Game — Gamified Coding Platform

> Learn Python by **playing** — Replace game controls with a Python terminal!

---

##  About The Project

This is not just a Snake game — it's a **gamified coding platform** that replaces traditional keyboard controls with a Python terminal. Players must write Python code to control the snake, making programming learning interactive, visual, and fun. Built with React and Pyodide (Python running directly in the browser).

---

##  Key Features

-  **Python Terminal Controls** — Type Python code to move the snake
-  **10 Progressive Difficulty Levels** — From beginner to advanced
-  **Python-in-Browser** using Pyodide (no backend needed!)
-  **Canvas API** for smooth game rendering
-  **Instant Feedback** — See your code affect the game in real-time
-  **Responsive Design** — Works on all screen sizes

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| React.js | Frontend UI & game logic |
| Pyodide | Python runtime in the browser |
| Vite | Build tool & dev server |
| Canvas API | Game rendering |
| HTML5/CSS3 | Structure & styling |

---

##  Project Structure

```
python-snake-game/
├── src/
│   ├── components/
│   │   ├── GameCanvas.jsx     # Canvas rendering
│   │   ├── PythonTerminal.jsx # Code input terminal
│   │   └── LevelSelector.jsx  # Difficulty levels
│   ├── utils/
│   │   ├── gameLogic.js       # Snake game logic
│   │   └── pyodideLoader.js   # Python runtime setup
│   ├── App.jsx
│   └── main.jsx
├── public/
├── index.html
├── vite.config.js
└── package.json
```

---

## How To Run

```bash
# Clone the repository
git clone https://github.com/lekhashree21/python-snake-game.git
cd python-snake-game

# Install dependencies
npm install

# Start development server
npm run dev

# Open browser at http://localhost:5173
```

---

 How To Play

1. Open the game in your browser
2. Select a difficulty level (1-10)
3. Type Python commands in the terminal:
   ```python
   move("up")    # Move snake up
   move("down")  # Move snake down
   move("left")  # Move snake left
   move("right") # Move snake right
   ```
4. Watch your code control the snake in real-time!

---

##  Developer

**Lekhashree B** — [LinkedIn](https://linkedin.com/in/lekhashree-b) | [GitHub](https://github.com/lekhashree21)
