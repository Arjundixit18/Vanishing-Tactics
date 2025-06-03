#  Vanishing Tactics - A Dynamic Tic Tac Toe Twist with Fading Strategy

**Vanishing Tactics** is a reimagined, animated version of the classic Tic Tac Toe game, built using **Python** and **Pygame**. This isn't your ordinary grid battle—every move comes with a cost. Each player can only have **3 active moves** at a time, with older ones **fading into oblivion**. It’s fast, visual, strategic, and wrapped in a polished UI with immersive sound effects.

> 🧠 Outsmart your opponent not just by placing the right move—but by managing what stays on the board.

---

## 🔮 Preview

<p align="center">
  <img src="https://github.com/Arjundixit18/Vanishing-Tactics/blob/main/Result1.png" alt="Vanishing Tactics Preview" width="500"/>
</p>

<p align="center">
  <img src="https://github.com/Arjundixit18/Vanishing-Tactics/blob/main/Result2.png" alt="Vanishing Tactics Preview" width="500"/>
</p>

---

## 🎯 Game Highlights

* 🕹️ **Two-Player 3x3 Grid Battle** – Take turns placing `X` or `O`
* 💨 **Disappearing Moves** – Each player can only maintain 3 visible marks at a time
* 🎭 **Fading Effects** – Oldest moves fade visually before vanishing
* 🔊 **Immersive Sound Effects** – Audio for both moves and game-over moments
* 🧠 **Winner Detection** – Visual line animation shows the winning strike
* 🔄 **Easy Reset** – Hit `SPACE` to reset the board anytime

---

## ⚙️ Requirements

* Python 3.x
* Pygame (`pip install pygame`)

---

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/arjundixit18/Vanishing-Tactics.git
cd Vanishing-Tactics
```

### 2️⃣ Install Dependencies

```bash
pip install pygame
```

### 3️⃣ Verify Resources

Ensure the following are present in your `resources/` folder or correct paths in code:

| File            | Description           |
| --------------- | --------------------- |
| `field.png`     | Game board background |
| `x.png`         | Player X icon         |
| `o.png`         | Player O icon         |
| `game_over.wav` | Sound for game over   |
| `move.wav`      | Sound for moves       |

> 🗂 You can change paths in the code if your files are stored elsewhere.

---

## 🎮 How to Play

```bash
python game.py
```

### Controls:

* 👆 Click to place a move (X or O)
* ⌨️ Press `SPACE` to restart the game
* ❌ Close window to quit

---

## 💡 Behind the Magic

This game uses:

* **Pygame Surface Manipulation** for scaling and alpha fading
* **Stateful Logic** for move history per player
* **Randomized Starting Player**
* **Vector math** for positioning and animations
* **Smooth UI** with scalable images and transition effects

---

## 👤 Author

**Arjun Dixit**
🔗 GitHub: [arjundixit18](https://github.com/arjundixit18)

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

