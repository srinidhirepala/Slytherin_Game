Snake Game in Java
This is a classic Snake Game implemented in Java using Swing for GUI and AWT for graphics rendering. In this game, the player controls a snake that moves around a grid to eat food and grow in size while avoiding collisions with its body or the walls.

Features:
Snake Movement: Controlled using the arrow keys (UP, DOWN, LEFT, RIGHT).
Game Over: The game ends when the snake collides with itself or the walls of the game area.
Food Generation: Food is placed randomly on the grid, and the snake grows when it eats food.
Score Tracking: The score is based on the number of body segments of the snake.
Game Loop: The game state updates periodically using a Timer to refresh the display and move the snake.
Graphics Rendering: Game visuals (snake, food, and grid) are rendered using Java's Graphics class.
Event Handling: Keyboard inputs are captured to control the snake’s movement.
Technologies Used
Java: Core programming language used for game logic.
Swing: Used for GUI creation and game window management (JFrame, JPanel).
AWT (Abstract Window Toolkit): Used for basic graphics rendering (Graphics class).
Timer (javax.swing.Timer): Used to manage the game loop and update the game state.
KeyListener: Captures keyboard inputs (arrow keys) for controlling the snake’s direction.
Random Class: Used for generating random positions for food on the game board.
Java Collections (ArrayList): Used to store the snake’s body parts dynamically.

How to Run

Clone the repository to your local machine:
bash
Copy
git clone https://github.com/your-username/snake-game-java.git

Navigate to the project directory:
bash
Copy
cd snake-game-java

Compile the SnakeGame.java file:
bash
Copy

javac SnakeGame.java
Run the game:
bash
Copy
java SnakeGame
The game window should open, and you can start playing the Snake Game!

Controls
Arrow Keys: Use the UP, DOWN, LEFT, and RIGHT arrow keys to control the snake’s movement.
Screenshots

Example of the game in action.

![image](https://github.com/user-attachments/assets/81921644-a4b7-4414-ac51-8c601664a90e)


