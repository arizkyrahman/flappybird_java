# Flappy Bird Game - Java
This is a simple Flappy Bird game developed in Java using the Swing library for the graphical user interface. The game is based on the popular mobile game, where the player controls a bird that has to fly through a series of pipes without touching them. The game features a high score system, where the player can try to beat their previous best score.

## Installation
To play the game, you will need to have Java installed on your computer. Here are the steps to run the game:

1. Clone the repository to your local machine: git clone `https://github.com/arizkyrahman/flappybird_java.git`
2. Open the command prompt and navigate to the project folder: `cd flappy_java`
3. Compile the game using the Java compiler: `javac FlappyBird.java .. `
4. Run the game using the Java Virtual Machine: `java flappybird_java.. 

## How to Play
The objective of the game is to fly the bird through the pipes without touching them. The bird automatically moves forward, and the player must click the mouse to make the bird flap its wings and fly upwards. If the bird hits a pipe or the ground, the game is over.

The game features a high score system, where the player's best score is saved and displayed on the game over screen. The player can try to beat their previous best score by playing the game again.

## Development
The game is developed using the Swing library for the graphical user interface. The game is structured using the Model-View-Controller (MVC) pattern, where the game logic and data are separated from the user interface.

The game uses a number of Java features, including:

- BufferedImage for loading and rendering graphics
- Random for generating random pipe heights
- MouseListener for handling user input
- Timer for updating the game state at regular intervals
