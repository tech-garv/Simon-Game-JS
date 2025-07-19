# Simon Game 🎮

A web-based version of the classic **Simon Game** built using **HTML**, **CSS**, **JavaScript**, and **jQuery**.

---

## 🧠 How to Play

Simon Game is a memory game where the player needs to **repeat a sequence of colors and sounds** in the correct order. The sequence grows longer with each round, testing your memory and reaction!

### 🔹 Instructions:
- Press any key to start the game.
- Watch the pattern shown by the game (flashing colors + sounds).
- Click the buttons in the **same order**.
- The sequence will grow by one each round.
- If you click the wrong color, the game resets.

---

## 🚀 Tech Stack

- ✅ HTML5
- ✅ CSS3
- ✅ JavaScript
- ✅ jQuery (for DOM manipulation)
- ✅ Audio playback using `Audio()` objects

---

## 🔊 Sounds Used

Each color has an associated sound:
- `green.mp3`
- `red.mp3`
- `yellow.mp3`
- `blue.mp3`
- `wrong.mp3` (played on mistake)

Make sure these files are stored in a folder named `sounds/` in the root directory.

---

## 📁 Project Structure

```bash
simon-game-js/
│
└── sounds/            # Folder containing sound files
    ├── blue.mp3
    ├── green.mp3
    ├── red.mp3
    ├── yellow.mp3
    └── wrong.mp3
├── index.html         # Main HTML file
├── styles.css         # Styling for the game
├── game.js            # Game logic using jQuery
├── README.md          # Project documentation

