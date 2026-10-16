# 🎮 Tetris Game — Java

An enhanced implementation of the classic Tetris game featuring AI-powered gameplay, two modes, custom graphical interfaces, and a database-backed leaderboard.

## 📌 About the Project

This project recreates the classic Tetris experience with additional features that combine game development, artificial intelligence, data structures, database management, and graphical user interface design.
The game includes **Easy and Hard AI modes**, tetromino movement and rotation, automatic gravity, collision detection, level progression, sound controls, and a leaderboard for storing and displaying player scores.
The project was developed collaboratively, involving feature implementation, interface design, code integration, testing, and documentation.

## ✨ Key Features

### 🎮 Gameplay Mechanics
- Classic Tetris gameplay with randomly generated tetrominoes
- Automatic downward movement through a gravity mechanism
- Block movement, rotation, and collision detection
- Row and column clearing mechanics
- Game-over detection and gameplay termination
- Restart functionality
- Level progression with increasing falling speed

### 🤖 Artificial Intelligence
- **Easy Mode:** AI move evaluation using the Dellacherie Evaluation Function
- **Hard Mode:** AI decision-making through board-position evaluation
- Best-move computation for AI gameplay
- Board analysis using holes, row transitions, column transitions, and top occupied row
- AI visualization integrated into both difficulty modes

### 🏆 Database-Backed Leaderboard
- Database connectivity and configuration
- Player score and level storage
- Leaderboard retrieval and sorting
- Score display through a graphical leaderboard interface
- Database connection testing

### 🎨 User Interface & Experience
- Custom game background, logo, and board layout
- Sound on/off and AI mode on/off controls
- Play, replay, settings, Easy Mode, and Hard Mode options
- Mouse-based dialog interactions
- Background music and sound effects

## 🛠️ Technologies & Concepts

- **Programming Language:** Java
- **GUI & Rendering:** Java Swing and Graphics/Graphics2D
- **Database:** MySQL
- **Database Connectivity:** MySQL Connector/J
- **Data Structures:** Two-dimensional arrays, linked nodes, and custom key-value map
- **AI & Algorithms:** Dellacherie Evaluation Function and board-position evaluation
- **Core Concepts:** Object-oriented programming, collision detection, event handling, game-state management, and timer-based gravity

## 🧠 Technical Implementation

Some of the major classes, methods, and components developed for the project include:

| Component | Purpose |
|---|---|
| `Array2D.java` | Manages the two-dimensional structure used for tetromino shapes. |
| `Tetromino` | Represents the different block shapes using array-based structures. |
| `EasyGamePanel.java` | Handles gameplay, keyboard input, block movement, rotation, and rendering. |
| `computeBestAiMove()` | Determines a candidate move for AI gameplay. |
| `evaluatePosition()` | Evaluates a board position for AI decision-making. |
| `countHoles()` | Counts empty spaces beneath occupied board cells. |
| `countRowTransitions()` | Evaluates transitions between occupied and empty cells across rows. |
| `countColTransitions()` | Evaluates transitions between occupied and empty cells across columns. |
| `getTopOccupiedRow()` | Identifies the highest occupied row on the board. |
| `MyMap.java` and `Node.java` | Implement a custom key-value data structure using linked nodes. |
| `DBConnection.java` | Manages database connectivity and configuration. |
| `LeaderboardManager.java` | Stores, retrieves, and organizes leaderboard records. |
| `LeaderboardUI.java` | Displays leaderboard information in a graphical interface. |
| `TestConnection.java` | Tests database connectivity. |

## 🚀 Getting Started

### Prerequisites

- Java Development Kit (JDK)
- A Java IDE, such as IntelliJ IDEA, Eclipse, or NetBeans
- MySQL Server, if required by the application
- MySQL Connector/J
- The project’s image, sound, and other required resource files

## 🎥 Project Demonstration

A gameplay demonstration video is available here:

**[Add your demonstration video link]**

## 📚 Learning Outcomes

Through this project, I gained practical experience with:

- Java-based game development and graphical rendering
- Object-oriented programming and reusable class design
- AI move selection and heuristic board evaluation
- Data structures and array manipulation
- Collision detection and game-state management
- Keyboard and mouse event handling
- MySQL integration and leaderboard management
- Collaborative development, code merging, testing, and documentation

## 🔮 Potential Future Improvements

- Add more AI strategies and difficulty levels
- Improve AI performance and move evaluation
- Enhance gameplay animations and visual effects
- Expand leaderboard functionality
- Improve database configuration and error handling

## 👩‍💻 Author

**Sadisa Dar**

GitHub: [@Sadisa-Dar](https://github.com/Sadisa-Dar)

*Developed as a collaborative Java game development project.*
