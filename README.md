# SnakeGame

A classic Snake game built in Java. The player controls a snake that grows in length as it consumes food, but must avoid colliding with the walls or itself.

## Table of Contents
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Project Structure](#project-structure)
- [Build and Run](#build-and-run)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/SnakeGame.git
   ```
2. Open the project in [NetBeans IDE](https://netbeans.apache.org/).
3. Build and run the project using the IDE or command line.

## How to Play

- Use the arrow keys to control the snake's direction.
- The snake grows longer each time it eats the food.
- Avoid hitting the walls or the snake's own body.
- Try to score as high as possible!

## Project Structure

```bash
SnakeGame/
│
├── src/
│   └── snakegame/
│       ├── SnakeGame.java    # Main class
│       └── Board.java        # Game logic and rendering
│
├── dist/
│   └── SnakeGame.jar         # Compiled JAR for distribution
│
└── README.md                 # Project documentation
```

## Build and Run

1. From the command line, navigate to the `dist` folder:
   ```bash
   cd dist
   ```
2. Run the game using the following command:
   ```bash
   java -jar "SnakeGame.jar"
   ```

Alternatively, you can build and run the project directly in the NetBeans IDE.

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
