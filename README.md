# Pac-Man

A simple console-based Pac-Man game built in Java. The game recreates the core Pac-Man gameplay using a text-based board, player movement, ghosts, scoring, lives, and difficulty control.

## Features

* **Console-Based Gameplay**
  Play Pac-Man directly in the terminal using a text-based game board.

* **Player Movement**
  Control Pac-Man using:

  * `W` — Move Up
  * `S` — Move Down
  * `A` — Move Left
  * `D` — Move Right

* **Ghost Enemies**
  Three ghosts move around the maze using randomized movement and can capture the player.

* **Scoring System**

  * Collect `.` pellets to earn **1 point**
  * Collect `@` items to earn **3 points**

* **Lives System**
  The player starts with **3 lives**. Getting captured by a ghost costs one life and resets the player position.

* **Difficulty Control**
  The main menu allows you to increase or decrease the game speed, changing the difficulty.

* **Win Condition**
  Clear all collectible items from the maze to win the game.

* **Lose Condition**
  Lose all available lives to end the game.

* **Main Menu**

  * Start Game
  * Increase Difficulty
  * Decrease Difficulty
  * Exit

## Controls

| Key | Action |
| --- | ------ |
| `W` | Up     |
| `A` | Left   |
| `S` | Down   |
| `D` | Right  |

## How to Run

Make sure Java is installed on your system.

Compile the program:

```bash
javac main.java
```

Run the game:

```bash
java main
```

## Project Structure

The game is organized into several classes:

* `Board` — Creates and renders the game board.
* `Player` — Handles player movement, input, score, and lives.
* `Ghost` — Controls ghost movement.
* `Game_Manager` — Handles game logic, collisions, winning, and losing.
* `main` — Handles the main menu and starts the game.

## Technologies

* Java
* Object-Oriented Programming
* Multithreading
* Randomized Enemy Movement
* Console-Based Rendering

## Project

This project was created as a Java game development project to practice object-oriented programming, game loops, input handling, collision detection, and basic game logic.
