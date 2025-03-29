# Flappy Bird AI with NEAT

## Overview

This project is a Flappy Bird game implemented in Python using Pygame for graphics and NEAT (NeuroEvolution of Augmenting Topologies) for training an AI to play. The AI learns to navigate through the pipes by evolving through multiple generations.

## Features

Flappy Bird mechanics, including jumping, gravity, and collisions.

Procedurally generated pipes.

A base that moves to simulate an infinite scrolling effect.

AI training using NEAT to optimize gameplay strategies.

Score tracking and generation counter display.

## Technologies Used

Python for core programming.

Pygame for rendering and game logic.

NEAT-Python for training the AI.

## File Structure

FlappyBird_NEAT/
│-- flappy.py               # Main game and AI training script
│-- config_feedforward.txt  # NEAT configuration file
│-- imgs/                   # Folder containing game images
│   ├── bird1.png
│   ├── bird2.png
│   ├── bird3.png
│   ├── pipe.png
│   ├── base.png
│   ├── bg.png

## Installation and Setup

### Prerequisites

Ensure you have Python installed, along with the required libraries:

pip install pygame neat-python

### Running the Game

To run the AI training process and play the game, execute:

python flappy.py

## How the AI Works

Initialization: NEAT initializes a population of neural networks.

Game Simulation: Each AI-controlled bird interacts with the environment.

Fitness Calculation: Birds receive fitness points based on how far they travel.

Selection and Evolution: NEAT selects the best-performing birds and evolves them.

Repeat: The process continues until an optimal strategy emerges.

### Configuration File (config_feedforward.txt)

The config_feedforward.txt file defines parameters for NEAT, such as population size, mutation rates, and network structure.

## Controls (For Human Testing)

Press 'q' to quit the game.

## Future Improvements

Implement a graphical interface to visualize AI learning progress.

Optimize the NEAT parameters for better training efficiency.

Add different difficulty levels.

## License

This project is open-source and available for modification and learning purposes.
