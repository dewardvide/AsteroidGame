# AsteroidGame
Browser Based Asteroid Based Game Purely Vibe Coded

![](https://github.com/dewardvide/AsteroidGame/blob/main/Screenshot%202025-04-04%20at%2013.50.31.png)

## 🎮 Overview

Asteroid Hunter is a simple, yet engaging, browser-based game where you take the helm of a nimble spaceship, tasked with collecting asteroids amidst the vast expanse of space. 🌌

**Key Features:**

* **🕹️ Gameplay:** Intuitive controls! Use arrow keys or WASD to navigate your ship and collect those pesky asteroids.
* **🏆 Scoring:** Rack up points! Smaller asteroids yield higher rewards, adding a strategic twist.
* **👾 Dynamic Asteroids:** These aren't your average space rocks! They'll try to evade you, ramping up the challenge.
* **⏱️ Timer Challenge:** A thrilling 60-second countdown puts your skills to the test.
* **🥇 High Score Hall of Fame:** Compete for glory! The top 10 scores are immortalized with player names.
* **📊 Leaderboard View:** Check out the competition! A dedicated screen showcases the top players.
* **🏁 Game Over Glory:** Your score is displayed, and if you've made history, you'll be prompted to enter your name!
* **📱 Responsive UI:** Designed with CSS for a sleek, adaptable experience.

**⚠️ Note:** High scores are stored for the duration of your current browser session.

## 🕹️ How to Play

1.  **🚀 Launch the Adventure:** Open `index.html` in your favorite web browser.
2.  **▶️ Start the Hunt:** Click the "Start Game" button on the launch screen.
3.  **🛸 Control Your Ship:** Use arrow keys or WASD to maneuver through space.
4.  **💎 Collect Asteroids:** Snag those space rocks to boost your score.
5.  **⏳ Beat the Clock:** Survive and score as many points as possible within 60 seconds.
6.  **🏆 Achieve Glory:** If you set a new high score, enter your name and click "Submit Score".
7.  **📊 View the Legends:** Check out the leaderboard by clicking "View Leaderboard" or "Leaderboard" after game over.
8.  **↩️ Return to Action:** Click "Back to Game" to dive back into the hunt.
9.  **🔄 Play Again:** Click "Play Again" after a game over to try for a better score.

## 📂 Files

* **`index.html`:** The heart of the game! Contains all the HTML, CSS, and JavaScript magic.

## ⚙️ Game Mechanics

* **🛸 Spaceship Controls:**
    * Arrow keys (Left, Right, Up, Down) or WASD for seamless navigation.
* **☄️ Asteroid Generation:**
    * Randomly generated asteroids populate the canvas, providing a unique challenge each time.
    * Asteroids exhibit evasive maneuvers as you approach.
* **💰 Scoring System:**
    * Points are awarded based on asteroid size – smaller is better!
* **⏱️ Time Challenge:**
    * A 60-second timer adds urgency to your asteroid hunting.
* **🥇 High Score Tracking:**
    * The top 10 scores are saved, allowing you to compete for the top spot.
    * New high scores prompt for player name entry.

## 🛠️ Implementation Details

* **<canvas> HTML5 Canvas:** The cosmic playground where the game unfolds.
* **📜 JavaScript:** The engine that drives the game logic and interactivity.
* **🎨 CSS:** Styles the game elements for an immersive experience.
* **🔄 Game Loop (`gameLoop()`):** Manages the game's update and rendering cycles.
* **📊 Leaderboard Table:** Displays the high scores in an organized HTML table.
* **👂 Event Listeners:** Captures keyboard inputs and button clicks for seamless interaction.
* **🏃 Asteroid Avoidance:** Asteroids dynamically alter their paths to avoid the player, increasing the challenge.
* **💥 Visual Effects (Hit Effects):** Dynamic visual feedback when asteroids are collected.
* **✨ Starry Background:** A randomly generated starfield adds to the cosmic atmosphere.

## 📦 Dependencies

* **None!** This game is a standalone experience, running entirely within your browser using `index.html`.

## ⚠️ Known Limitations

* **Session-Based High Scores:** High scores are only retained for the current browser session.
* **Simplified Gameplay:** The game features basic asteroid generation and difficulty.
* **Aural Absence:** No sound effects are implemented.
* **Mobile Unoptimized:** The game is not specifically designed for mobile devices.

-   High scores are only saved for the current browser session.
-   The game's difficulty and asteroid generation are relatively simple.
-   The game lacks sound effects and more advanced visual effects.
-   The game is not optimized for mobile devices.
