# 🐍 Snack Game

A fun, browser-based snake game built with HTML5 Canvas, styled for a retro arcade feel. Guide your snake to eat food, grow in length, and rack up points—while avoiding walls and self-collision!

---

## 🎮 How to Play

- Use **arrow keys** to navigate the snake (up, down, left, right).  
- Eat red squares (food) to **increase your score and grow**.  
- Game ends if your snake hits the **wall or its own body**.  
- Click **Reset 🐍** to start a new game anytime.

---

## 🧩 Features

- **Responsive Canvas**: 400×400 grid with smooth 25px unit movement  
- **Score Display**: Bold, stylized counter using "Permanent Marker" font  
- **Reset Button**: Custom-styled for quick restarts  
- **Collision Detection**: Game over when hitting walls or snake’s own body  
- **Classic Game Loop**: Built with `setTimeout` for smooth ticks every ~75ms

---

## 📂 Project Structure

```
├── index.html # Game markup and canvas container
├── style.css  # Visual styling (board, score, button)
└── script.js  # Game logic & mechanics
```

---

## 🛠️ How It Works

1. **Game Initialization**  
   Sets initial snake position, food placement, scoreboard, and starts the game loop.

2. **Game Loop (`nextTick`)**  
   - Clears screen  
   - Draws food  
   - Moves snake  
   - Captures input  
   - Checks for game over  
   - Repeats every 75ms

3. **Snake Movement & Growth**  
   - Snake moves by adding a head in the current direction  
   - If food is eaten, score increases and snake grows; otherwise tail is removed

4. **Food Generation**  
   - Randomly places food in multiples of the grid size (25px)  
   - Ensures valid coordinates within the canvas boundaries

5. **Collision Detection**  
   - Hitting the wall or colliding with itself stops the game and shows **GAME OVER**

---

## 🚀 Quick Start

1. Clone or download the repo.  
2. Open `index.html` in your browser to play!  
3. Use **arrow keys** to move. Click **Reset** to play again.

---

## 📚 Inspired By

Classic minimalist implementations of Snake on HTML5 Canvas, similar to early tutorials and nostaigic browser editions.

---

## 📫 Contact

- GitHub: [@Mithun0017](https://github.com/Mithun0017)  
- Email: mithun200617@gmail.com  

> Enjoy a simple retro game with room to grow—have fun coding your own Snake twist!
