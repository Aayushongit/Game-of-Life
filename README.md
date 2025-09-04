# Game of Life

A Python implementation of Conway's Game of Life using Pygame.

## Features

- Visual simulation of cellular automaton
- Configurable rules for cell birth and death
- Fade effect for recently dead cells
- Random seed generation at borders
- Generation counter display
- Real-time performance metrics

## Requirements

- Python 3.x
- Pygame

## Installation

1. Install Python 3.x
2. Install Pygame:
   ```bash
   pip install pygame
   ```

## Usage

Run the simulation:
```bash
python 2d.py
```

## Game Rules

The simulation follows these rules:
- A new cell appears if it has exactly 3 neighbors
- A living cell dies if it has more than 3 or fewer than 2 neighbors
- The board wraps around at the edges

## Controls

- Close the window to exit the simulation

## Output

The program generates:
- Real-time visual display of the game state
- Console output showing performance metrics (FPS)

## Configuration

You can modify these parameters in the code:
- `generations_per_second`: Speed of simulation
- `fade_time`: Duration of fade effect for dead cells
- `size`: Window dimensions (currently 900x600)
- `R`: Rules tuple for birth and death conditions