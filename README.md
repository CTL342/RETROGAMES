# RETRO GAMES - A Classic Arcade Experience

Welcome to RETRO GAMES, your ultimate destination for classic gaming experiences! This project is a web-based platform that brings back the joy and simplicity of iconic vintage arcade games, allowing users to immerse themselves in a world of pixelated nostalgia and timeless fun.

## Description

Our mission is to celebrate the golden age of gaming by providing a curated selection of classic titles, faithfully recreated using modern web technologies. Whether you're revisiting old favorites or discovering them for the first time, prepare for an unforgettable journey down memory lane. Each game is designed to be played directly in your browser.

## Features

* **Classic Game Collection**: Play a variety of beloved retro arcade games.
* **Responsive Design**: The website layout is designed to be accessible on different screen sizes.
* **Interactive Gameplay**: Each game features its original core mechanics, recreated with HTML5 Canvas and JavaScript.
* **Leaderboards**: (As seen in `leaderboards.html`) A system for users to create accounts, sign in, and submit their high scores for different games.
* **Easy Navigation**: Simple navigation bar to switch between Games, Leaderboards, and About sections.
* **Dynamic Game Grid**: The main games page dynamically lists available games.

## Games Included

Currently, the RETRO GAMES collection features the following classics:

* Space Invaders
* TRON Light Cycles (2 Player)
* Pac-Man (Simplified)
* Tetris (with Hold and Ghost Piece)
* Asteroids (with progressive difficulty)
* Pong (2 Player)
* Breakout (with levels)
* Frogger (with enhanced visuals)
* Tank Battle (2 Player, inspired by Atari Combat)

Each game is implemented in its own HTML file with embedded JavaScript for game logic and rendering on an HTML5 Canvas.

## Technologies Used

* **HTML5**: For the structure of the web pages and game containers.
* **CSS3**: For styling the website, game areas, and UI elements.
* **JavaScript (ES6+)**: For all game logic, including:
    * HTML5 Canvas API for 2D rendering of game graphics and animations.
    * Keyboard event handling for player controls.
    * Game state management (scores, lives, levels, etc.).
    * Collision detection.
    * DOM manipulation for UI updates (e.g., start messages, score displays in some versions).

## Website Structure

The website is organized into the following main pages:

* `index.html`: The main landing page showcasing the grid of available games.
* `about.html`: Provides information about the RETRO GAMES project and contact details.
* `leaderboards.html`: Features a system for user authentication (sign-up/sign-in) and a display for game-specific leaderboards. Users can submit their scores for various games.
* **Game Pages** (`space-invaders.html`, `tron.html`, etc.): Each game has its dedicated HTML page where the game canvas and specific instructions are presented.

## How to Run/View

1.  Clone or download the project files.
2.  Open any of the `.html` files (e.g., `index.html`) directly in a modern web browser (like Chrome, Firefox, Edge, Safari).
3.  Navigate between pages using the header navigation links.
4.  For game pages, click the "CLICK TO START" message to begin playing.

## Author

This RETRO GAMES website was developed by \[Your Name/Username Here].

*(Optional: Add an acknowledgment if you wish)*
The game implementations were developed with the assistance of Google's Gemini AI for code generation, logic refinement, and debugging.

## Future Enhancements (Potential Ideas)

* Persistent leaderboards using a backend database (e.g., Firebase).
* More advanced AI for single-player opponents.
* Sound effects and music for a more immersive retro experience.
* Mobile touch controls for games.
* Additional classic games added to the collection.
* User profiles and settings.

---

Enjoy your trip down memory lane with RETRO GAMES!
