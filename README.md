# Snake Game

A classic Snake Game built with Java Swing.

## Features
- Classic snake gameplay
- Score tracking
- Smooth controls using arrow keys
- Collision detection with walls and self

## How to Run

### Using Ant (NetBeans)
```bash
ant run
```

### Using Java directly
```bash
cd src
javac snakegame/SnakeGame.java snakegame/Board.java
cd ..
java -cp src snakegame.SnakeGame
```

## Controls
- **Arrow Keys**: Move the snake
- **Objective**: Eat the food to grow and increase your score without hitting walls or yourself

## Project Structure
```
Snake Game/
├── src/
│   └── snakegame/
│       ├── SnakeGame.java
│       ├── Board.java
│       └── icons/
├── build.xml
└── nbproject/
    └── (NetBeans configuration files)
```

Enjoy the game!
