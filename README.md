# Arcade Racer

Welcome to Arcade Racer, a classic top-down 2D car racing game built entirely with HTML5 Canvas, CSS (Tailwind CSS), and vanilla JavaScript. Dodge incoming traffic, increase your score, and aim for the high score in this fast-paced arcade experience!

## Features

-   **Classic Arcade Gameplay:** Enjoy simple yet addictive racing action.
-   **Intuitive Controls:** Move your car left and right with arrow keys or A/D.
-   **Procedural Generation:** Randomly generated opponent cars and obstacles for endless replayability.
-   **Dynamic Difficulty:** Game speed gradually increases as your score climbs, keeping you on your toes.
-   **Collision Detection:** Game over if you hit an obstacle, adding a challenge.
-   **Scoring System:** Track your performance with an ever-increasing score counter.
-   **High Score Tracking:** Your best score is saved locally using `localStorage`.
-   **Visual Feedback:** Scrolling road with lane markings creates a compelling illusion of movement.
-   **Engaging UI:** Clear score and speed displays, and a distinct game over screen.
-   **Sound Effects:** Basic engine sound and collision sound enhance the arcade feel.
-   **Responsive Design:** Optimized for a great experience on desktop browsers.
-   **Modern Styling:** Clean and colorful graphics powered by Tailwind CSS.

## How to Play

1.  **Open `index.html`:** Simply open the `index.html` file in your web browser.
2.  **Start the Game:** Click the "START GAME" button on the welcome screen.
3.  **Control Your Car:**
    *   Press the **Left Arrow key (←)** or **A key** to move your car left.
    *   Press the **Right Arrow key (→)** or **D key** to move your car right.
4.  **Objective:** Your car moves forward automatically. Your goal is to dodge the oncoming obstacle cars for as long as possible. The longer you survive, the higher your score will be, and the faster the game will get!
5.  **Game Over:** If you collide with an obstacle, the game ends. Your final score will be displayed, along with the current high score.
6.  **Restart:** Click the "RESTART" button to play again and try to beat your high score!

## Technologies Used

*   **HTML5:** Structure of the web page.
*   **CSS (Tailwind CSS CDN):** For responsive design and modern styling of UI elements.
*   **JavaScript (Vanilla):** Game logic, interaction, and Canvas drawing.
*   **HTML5 Canvas API:** For rendering all game graphics (road, cars, lane lines).
*   **Web Audio API:** For dynamic sound effects (engine, collision).

## Development Notes

*   The game assets are drawn programmatically using Canvas API primitives (rectangles, rounded rectangles).
*   `requestAnimationFrame` is used for a smooth 60fps animation loop.
*   Collision detection is implemented using Axis-Aligned Bounding Box (AABB) method.
*   High score is persistent across browser sessions using `localStorage`.

## License

This project is open-sourced under the MIT License. See the `LICENSE` file for full details.
