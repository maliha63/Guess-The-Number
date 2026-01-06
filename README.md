# 🎯 Guess The Number

## 🧩 About The Project

Guess The Number is a sleek, logic-based web application where players try to identify a hidden number. It focuses on smooth user experience and instant feedback. The game tracks performance through a scoring system and session-based high scores.

---

## 🎮 Preview
<img width="1366" height="768" alt="Guess_The_Number" src="https://github.com/user-attachments/assets/bcc1acf7-2d17-4081-963e-cbc384f6d3d4" />

--- 

## 🚀 Key Features

* **Dynamic Logic:** Real-time feedback for "Too High," "Too Low," or invalid inputs
* **Session Persistence:** High scores preserved across refresh using `sessionStorage`
* **Optimized UX:** Supports Enter key submission and quick visual feedback
* **Responsive Design:** Fully playable on mobile, tablet, and desktop
* **Reset Functionality:** Restart the game instantly without page reload

---

## 💻 Tech Stack

| Layer      | Technology                         |
| ---------- | ---------------------------------- |
| Frontend   | HTML5, CSS3                        |
| Logic      | Vanilla JavaScript (ES6+)          |
| Deployment | Firebase Hosting                   |
| Storage    | Web Storage API (`sessionStorage`) |

---

## 🛠️ Getting Started

### ✅ Prerequisites

A modern web browser is enough to run the project.

### 📥 Installation & Local Setup

**Clone the repository:**

```bash
git clone https://github.com/your-username/guess-the-number.git
```

**Navigate to the folder:**

```bash
cd guess-the-number
```

**Open the project:**
Open `index.html` directly in your browser or use the **Live Server** extension in VS Code.

---

## 🧠 Game Logic & Mechanics

The app follows a simple state management flow:

1. **Initialization:** Random secret number generated using `Math.random()`
2. **Validation:** Input checked to ensure it is a valid number
3. **Comparison:**

   * ✔️ Correct → Success screen and high score update
   * ❌ Incorrect → Score decreases with hint (too high/too low)
4. **Termination:** Game ends when score is zero or number guessed

---

## 📁 Project Structure

```
Guess-The-Number
├── Public/             # Static assets
├── index.html          # Main game entry point
├── practice.html       # Development sandbox
├── style.css           # Custom styling
├── script.js           # Core game logic
├── firebase.json       # Deployment configuration
└── README.md
```

---

## 🔮 Roadmap & Future Enhancements

* [ ] Persistent storage using `localStorage` for long-term highscores
* [ ] Difficulty modes: Easy (1–20), Medium (1–50), Hard (1–100)
* [ ] Accessibility updates with ARIA labels and sound feedback
* [ ] Global leaderboard using Firebase Realtime Database

---

## 📄 License

Distributed under the **MIT License**.
