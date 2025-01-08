# Flappy Bird AI with NEAT

This project implements an AI-powered version of the classic game **Flappy Bird** using **Python**, **Pygame**, and **NEAT (NeuroEvolution of Augmenting Topologies)**. The AI evolves over generations, learning how to play the game more efficiently.

## Features
- **AI-controlled Gameplay**: The birds use a genetic algorithm to learn and improve their gameplay over time.
- **Dynamic Environment**: Randomized pipe heights create a challenging and ever-changing gameplay environment.
- **Visual Animations**: Smooth graphics and animations powered by Pygame.
- **Real-time Learning**: Observe how the birds evolve and adapt to the game environment.

## Technologies Used
- **Python**: A core programming language for the project.
- **Pygame**: This is used to render the graphics and handle animations.
- **NEAT (NeuroEvolution of Augmenting Topologies)**: A machine learning framework for evolving neural networks.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/flappy-bird-ai.git
   cd flappy-bird-ai
   ```

2. Install the required dependencies:
   ```bash
   pip install pygame neat-python
   ```

3. Ensure the following directory structure for game assets:
   ```
   flappy-bird-ai/
   |-- imgs/
       |-- bird1.png
       |-- bird2.png
       |-- bird3.png
       |-- pipe.png
       |-- base.png
       |-- bg.png
   |-- config-feedforward.txt
   ```

4. Run the project:
   ```bash
   python flappy_bird_ai.py
   ```

## How It Works
1. **Bird Class**: Handles bird movements, animations, and collisions.
2. **Pipe Class**: Manages the pipes' position, movement, and collision detection.
3. **Base Class**: Simulates the scrolling base of the game.
4. **NEAT Algorithm**:
   - A neural network controls each bird.
   - The networks evolve based on fitness scores (calculated by how far each bird progresses).
   - The birds improve their performance over generations by avoiding pipes and surviving longer.

## Configuration
The NEAT algorithm is configured using the `config-feedforward.txt` file. You can customize parameters such as:
- Population size
- Number of hidden layers
- Mutation rates

## Gameplay
When you run the project, you'll see birds trying to navigate through the pipes. Over time, they learn to avoid collisions and survive longer. The score and progress are displayed on the screen.

## Demo


## Future Improvements
- Add a user-controlled mode to compare human and AI performance.
- Enhance visuals with additional animations and effects.
- Implement more challenging levels and environments.

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.

## Acknowledgments
- The NEAT-Python library for enabling neuroevolution.
- Pygame for making game development accessible and fun.



---
