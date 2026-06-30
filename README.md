# PacMan

A fully playable **Pac-Man clone** built using **Java Swing** and **AWT**. This project recreates the classic arcade experience with smooth movement, randomly moving ghosts, collectible food pellets, score tracking, multiple lives, and game restart functionality.

---

## Features

- Classic Pac-Man gameplay
- Keyboard-controlled movement
- Tile-based game map
- Random ghost movement with collision detection
- Food pellet collection
- Score tracking
- Three lives system
- Game Over screen
- Restart game by pressing any key
- Simple and clean object-oriented design

---

## Technologies Used

- Java
- Java Swing
- Java AWT
- Object-Oriented Programming (OOP)

---

## Project Structure

```
├── App.java          // Creates the game window
├── PacMan.java       // Main game logic
├── wall.png
├── pacmanUp.png
├── pacmanDown.png
├── pacmanLeft.png
├── pacmanRight.png
├── blueGhost.png
├── orangeGhost.png
├── pinkGhost.png
└── redGhost.png
```

---

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/pacman-java.git
```

### 2. Open the project

Open the project in your preferred Java IDE such as:

- IntelliJ IDEA
- Eclipse
- VS Code

### 3. Ensure all image assets are present

The following image files should be in the same package/folder as the Java files:

- wall.png
- pacmanUp.png
- pacmanDown.png
- pacmanLeft.png
- pacmanRight.png
- blueGhost.png
- orangeGhost.png
- pinkGhost.png
- redGhost.png

### 4. Compile and run

Run:

```bash
App.java
```

The game window will launch.

---

## Controls

| Key | Action |
|------|--------|
| ↑ | Move Up |
| ↓ | Move Down |
| ← | Move Left |
| → | Move Right |

After Game Over:

- Press any key to restart.

---

## Gameplay

- Control Pac-Man using the arrow keys.
- Eat all food pellets to clear the level.
- Avoid colliding with ghosts.
- Each collision costs one life.
- The game ends after losing all three lives.
- Clearing all pellets reloads the map while keeping the game running.

---

## Project Highlights

This project demonstrates:

- Java Swing GUI development
- Game loops using `javax.swing.Timer`
- Keyboard event handling
- Collision detection using rectangle overlap
- Object-oriented programming
- Randomized ghost movement
- Tile-map based level design
- Resource loading with `ImageIcon`

---

## Screenshots

Add screenshots of the game here.

Example:

```
screenshots/gameplay.png
screenshots/game-over.png
```

---

## Future Improvements

- Power pellets
- Ghost pathfinding (BFS/A*)
- Multiple levels
- Sound effects
- Animated sprites
- Pause menu
- High score saving
- Main menu
- Better ghost AI (Blinky, Pinky, Inky, Clyde behaviors)

---

## Contributing

Contributions are welcome!

Feel free to fork the repository, improve the game, and submit a pull request.

---

## License

This project is open-source and available under the MIT License.
