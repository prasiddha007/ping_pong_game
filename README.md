
# Pong Game 🎮

A simple implementation of the classic Pong game using Python's `turtle` module. The game allows two players to control paddles and compete by bouncing a ball back and forth. The first player to miss the ball loses the round, and the other player scores a point.

## Features
- Two-player paddle control
- Ball speed increases as the game progresses
- Scoreboard to keep track of the scores for both players
- Collision detection for paddle hits and wall bounces

## Table of Contents
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Technologies Used](#technologies-used)
- [Connect](#connect)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/prasiddha007/ping_pong_game.git
   ```
   
2. **Navigate to the project directory:**
   ```bash
   cd ping_pong_game
   ```

3. **Install required dependencies:**
   You only need Python installed on your system. There are no third-party libraries required (aside from Python's standard `turtle` module, which comes pre-installed).

4. **Run the game:**
   ```bash
   python main.py
   ```

## How to Play

- Player 1 (left paddle) uses the `W` (up) and `S` (down) keys to move their paddle.
- Player 2 (right paddle) uses the `Up` and `Down` arrow keys to move their paddle.
- The ball will bounce off the paddles and walls. If one player misses the ball, the other scores a point.

## File Structure
```
ping_pong_game/
│
├── paddle.py          # Defines the Paddle class for both players
├── ball.py            # Defines the Ball class with movement and bounce logic
├── scoreboard.py      # Manages the display and updates of the score
├── main.py            # Main game file to set up the game and run the game loop
└── README.md          # Project readme file
```

## Technologies Used

- **Python 3.x**
- **Turtle Graphics**: Python's built-in `turtle` module is used to create the game's graphical elements.
- **Object-Oriented Programming (OOP)**: The game is structured using classes such as `Paddle`, `Ball`, and `Scoreboard` to manage different components of the game.

## Connect

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/prasiddha-shah007/) if you have any questions or want to collaborate on future projects. I'd love to network with like-minded developers and professionals!

---

Thanks for checking out my project! 😊
