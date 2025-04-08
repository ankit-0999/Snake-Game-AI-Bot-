# Snake AI with PyTorch

This project implements a Snake game and trains an AI agent to play it using Deep Q-Learning. The project is built using Python and PyTorch, and it includes a graphical interface for the game using Pygame.

## Features

- **Snake Game**: A classic Snake game implemented with Pygame.
- **AI Agent**: An AI agent trained using Deep Q-Learning to play the Snake game.
- **Visualization**: Real-time plotting of scores and training progress using Matplotlib.
- **Model Saving**: The trained model is saved for future use.

## Project Structure

Workspace
(rerun without)
Collecting workspace information

Here is a README.md file for your project:

snake-ai-pytorch/ ├── agent.py # Implementation of the AI agent and training logic ├── arial.ttf # Font file (optional, not used in the current code) ├── game.py # Snake game logic for AI training ├── helper.py # Helper functions for plotting training progress ├── model.py # Neural network model and training utilities ├── requirements.txt # Python dependencies ├── snake_game_human.py # Snake game for human players ├── pycache/ # Compiled Python files (auto-generated) └── model/ └── model.pth # Saved model file (auto-generated during training)

### File Descriptions

- **`agent.py`**: Contains the `Agent` class, which implements the Deep Q-Learning algorithm. It includes methods for state representation, action selection, and memory replay.
- **`game.py`**: Implements the `SnakeGameAI` class, which provides the game logic for training the AI agent.
- **`helper.py`**: Provides a `plot` function to visualize the training progress, including scores and mean scores.
- **`model.py`**: Defines the `Linear_QNet` neural network and the `QTrainer` class for training the model.
- **`snake_game_human.py`**: A standalone script to play the Snake game manually using keyboard inputs.
- **`requirements.txt`**: Lists the Python dependencies required for the project.
- **`model/model.pth`**: Stores the trained model weights (generated during training).

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/snake-ai-pytorch.git
   cd snake-ai-pytorch
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

Ensure you have Python 3.7+ installed.

Usage
Play the Game Manually
Run the snake_game_human.py script to play the Snake game manually:

Train the AI Agent
Run the agent.py script to train the AI agent:
python [agent.py](http://_vscodecontentref_/9)
During training, the game will be displayed, and a real-time plot of the scores and mean scores will be shown.
# Dependencies
The project requires the following Python libraries:
    pygame
    numpy
    torch
    matplotlib
    IPython