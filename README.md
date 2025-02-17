# Random-Dice-Game

## Description
The Dice Rolling Game is a simple Java-based GUI application where two players roll virtual dice to determine a winner. The game includes animated dice rolling, random number generation, and a result display. The game can be played multiple times by clicking the "Roll!" button.

## Features
- Interactive GUI with player labels
- Real-time dice rolling animation (3 seconds)
- Random dice values between 1 and 6
- Displays the result (Player 1 Wins, Player 2 Wins, or Tie)
- Allows continuous gameplay by enabling the "Roll!" button after each round

## Prerequisites
Before running the project, ensure you have the following installed:
- Java Development Kit (JDK) 8 or later
- Java Swing for GUI (comes with JDK)

## Installation & Running Instructions
1. **Clone the Repository**
   git clone https://github.com/maksudulpranto1/dice-rolling-game.git
   cd random-dice-game
   
2. **Compile the Java Program**
   go to your IDE (VISUAL STUDIO CODE) and open the exracted ZIP file. After that just run java. 

## How to Play
1. Launch the application.
2. Click the **"Roll!"** button to start rolling the dice.
3. The dice images will change randomly for 3 seconds to simulate rolling.
4. Once the rolling stops, the final dice values are displayed.
5. The winner is determined based on the dice values:
   - **Player 1 Wins:** If Player 1’s dice value is greater than Player 2’s.
   - **Player 2 Wins:** If Player 2’s dice value is greater than Player 1’s.
   - **It's a Tie:** If both values are the same.
6. Click the **"Roll!"** button again to play another round.

## File Structure
```
├── src/
│   ├── DiceRollingGame.java
│   ├── ImgService.java
│   ├── assets/
│       ├── dice1.png
│       ├── dice2.png
│       ├── dice3.png
│       ├── dice4.png
│       ├── dice5.png
│       ├── dice6.png
│       ├── banner.png
└── README.md
```

## Contributing
Contributions are welcome! Feel free to fork this repository and submit a pull request with improvements.

## Author
Maksudul Hasan Pranto - [GitHub Profile][(https://github.com/maksudulpranto1)]

Enjoy the game! 🎲🎲


