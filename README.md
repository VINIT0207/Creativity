# Echo Puzzle Interactive Site - README

## Author: Vinit Sharma

Welcome to **Echo Puzzle**, an interactive website blending web design with progressive puzzles and achievements. This project is built entirely with **HTML5, CSS3, and Vanilla JavaScript** — no external libraries required.

---

## 🚀 Features
- **10 Puzzle Levels** — each level increases in difficulty and type (sequence, memory, sliding, cipher, maze, math, reflex).  
- **Achievement System** — badges pop up when levels are solved.  
- **Hints Available** — each puzzle provides context-sensitive hints.  
- **Local Progress Save** — progress and achievements are stored in browser `localStorage`.  
- **Scoring System** — solving without hints earns more points.  
- **Single Page App (SPA)** — fully contained in one HTML file.

---

## 🕹️ Gameplay
1. Open `echopuzzles_advanced.html` in a modern browser.  
2. Select a level from the **sidebar**.  
3. Solve the puzzle in the main game area.  
4. Earn **achievements and points** when successful.  
5. Progress is saved automatically.

---

## 📖 Levels Overview
- **Level 1:** Find the Sequence  
- **Level 2:** Memory Match  
- **Level 3:** Slide Puzzle  
- **Level 4:** Pattern  
- **Level 5:** Maze  
- **Level 6:** Cipher  
- **Level 7:** Logic Math  
- **Level 8:** Assemble  
- **Level 9:** Reflex  
- **Level 10:** Final  

---

## 🏆 Achievements
- **First Steps:** Solve Level 1  
- **Memory Keeper:** Solve Level 2  
- **Code Breaker:** Solve Level 6  
- **Explorer:** Solve the Maze (Level 5)  
- **Puzzle Master:** Complete all 10 levels  

Achievements are shown as popups and persist across sessions.

---

## ⚡ Tech Stack
- **HTML5** — structure & content  
- **CSS3** — styling, animations, transitions  
- **JavaScript (ES6)** — game logic, hints, scoring, localStorage  

---

## 🔮 Future Enhancements
- Add sound effects & background music  
- More levels & mini-games  
- Online leaderboard with backend integration  
- Multiple hint tiers (basic → detailed)  
- Mobile optimization  

---

## 🛠️ Installation
1. Clone or download the repository  
2. Open `echopuzzles_advanced.html` in your preferred browser  
3. Enjoy playing!  

---

## 🧩 Solutions / Walkthrough

**Level 1: First Steps (Sequence Mastery)**  
- **Hint:** Follow gradient colors of the logo: teal → cyan → pink → yellow  
- **Solution:** Click tiles in `data-index` order:  
- **0 (Teal) → 1 (Cyan) → 2 (Pink) → 3 (Yellow)**

**Level 2: Echo Pairs (Memory Challenge)**  
- **Hint:** Memorize high-value symbols first  
- **Solution:** Flip two cards at a time, match identical symbols (⭐, 🚀, etc.), continue until all pairs are matched

**Level 3: Slide Shift (Spatial Reasoning)**  
- **Hint:** Solve row by row: top → middle → bottom  
- **Solution:** Arrange tiles 1–8 in ascending order, empty space (0) at bottom-right:  
- **1 2 3** 
  **4 5 6**
  **7 8 0**
  
**Level 4: Trace Echo (Pattern Recognition)**  
- **Hint:** Diagonal cross pattern  
- **Solution:** Click nodes in this sequence:  
**1 → 2 → 3 → 4 → 5 → 6 →**

**Level 5: Silent Maze (Navigation)**  
- **Hint:** Exit is bottom-right; use pings wisely  
- **Solution:** Path avoiding walls:  
- **Start (0,0) → Down → Down → Right → Right → Down → Down → Right → Right → Exit (4,4)**

**Level 6: Caesar Clue (Cryptography)**  
- **Hint:** Common shifts: 3 (ROT3) or 13 (ROT13)  
- **Solution:** Encrypted `"khoor zruog"` → shift 3 → `"hello world"`

**Level 7: Echo Math (Mathematical Logic)**  
- **Hint:** Remember order of operations; fractions may help  
- **Solution:** Target 24, numbers `[2, 3, 4, 5, 8, 10]`  
- Examples:  
- (10 - 2) * 3
- (5 + 3) * (10 / 5) + 8
- 8 * 3
- (4 * 5) + (10 / 5) + 2

**Level 8: Assemble Echo (Spatial Assembly)**  
- **Hint:** Match color gradients; rotate pieces if needed  
- **Solution:** Drag pieces A,B,C,D to targets with `data-target-id` matching 0–3 (top-left → bottom-right)

**Level 9: Pulse (Reflex Training)**  
- **Hint:** Green zone is at top; speed changes after mistakes  
- **Solution:** Click the glowing indicator when inside the green section

**Level 10: Full Echo (Grand Finale)**  
- **Hint:** Decode Caesar cipher then solve math  
- **Solution:**  
Part 1 Cipher: `"wkh ilqdo dqvzhu lv brxu qdph"` → shift 3 → `"the final answer is your name"`  
Part 2 Math: Solve `"What is 4 * 6?"` → `24`

---

## 🙌 Credits
Created as a fun experimental mix of **interactive web design + puzzle gaming**.
