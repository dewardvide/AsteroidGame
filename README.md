# AsteroidGame
Browser Based Asteroid Based Game Purely Vibe Coded

https://github.com/dewardvide/AsteroidGame/blob/main/Screenshot%202025-04-04%20at%2013.50.31.png

## Overview

Asteroid Hunter is a simple, browser-based game where the player controls a spaceship to collect asteroids. The game features:

-   **Gameplay:** Use arrow keys or WASD to move the spaceship and collect randomly generated asteroids.
-   **Scoring:** Points are awarded for each asteroid collected. Smaller asteroids give more points.
-   **Dynamic Asteroid Behavior:** Asteroids try to avoid the player, making the game more challenging.
-   **Timer:** A 60-second timer adds a time-based challenge.
-   **High Score System:** Keeps track of the top 10 scores with player names.
-   **Leaderboard:** A dedicated screen to view high scores.
-   **Game Over Screen:** Displays the player's final score and prompts for a name if it's a new high score.
-   **Responsive User Interface:** Uses CSS for layout and styling.

**Note:** High scores are only saved for the current browser session.

## How to Play

1.  **Open the `index.html` file** in a web browser.
2.  **Click the "Start Game" button** on the start screen.
3.  **Use the arrow keys or WASD keys** to move the spaceship.
4.  **Collect the asteroids** to score points.
5.  **The game ends after 60 seconds.**
6.  If you achieve a high score, enter your name when prompted and click "Submit Score".
7.  **View the leaderboard** by clicking "View Leaderboard" from the start screen or “Leaderboard” after game over.
8.  **Return to the game** from the leaderboard screen by clicking "Back to Game".
9.  **Play again** by clicking "Play Again" from the game over screen.

## Files

-   **`index.html`:** Contains the HTML structure, CSS styling, and JavaScript logic for the game.

## Game Mechanics

-   **Spaceship Controls:**
    -   Arrow keys (Left, Right, Up, Down) or WASD keys are used to move the spaceship.
-   **Asteroid Generation:**
    -   Asteroids are randomly generated and move across the canvas.
    -   Asteroids avoid the player when they get close.
-   **Scoring:**
    -   Points are awarded for each asteroid collected.
    -   Smaller asteroids give more points.
-   **Timer:**
    -   The game ends when the 60-second timer reaches zero.
-   **High Scores:**
    -   The top 10 high scores are stored in an array.
    -   Players are prompted to enter their name if they achieve a high score.

## Implementation Details

-   **HTML Canvas:** The game is rendered on an HTML5 canvas element.
-   **JavaScript:** The game logic is implemented using JavaScript.
-   **CSS:** The game's layout and styling are handled using CSS.
-   **Game Loop:** The `gameLoop()` function handles the game's update and render cycles.
-   **Leaderboard:** The leaderboard is displayed in an HTML table.
-   **Event Listeners:** Event listeners are used to handle keyboard input and button clicks.
-   **Avoidance behavior:** Asteroids change their direction based on the player location, and their speed is increased when the player is close.
-   **Visual Effects:** hit effects are created when the player hits an asteroid.
-   **Starry Background:** a randomly generated starry background is drawn on the canvas.

## Dependencies

-   None. The game is self-contained within the `index.html` file and runs in any modern web browser.

## Known Limitations

-   High scores are only saved for the current browser session.
-   The game's difficulty and asteroid generation are relatively simple.
-   The game lacks sound effects and more advanced visual effects.
-   The game is not optimized for mobile devices.
