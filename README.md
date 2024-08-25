# Q-Learning in GridWorld

## Overview

This repository contains the implementation of a Q-learning agent designed to navigate a GridWorld environment. The agent learns to pick up an item at a random location (A) and deliver it to a fixed goal location (B) within the grid. The project demonstrates the application of reinforcement learning in a custom-built environment.

## Project Structure

- **`Q_Learning_GridWorld.ipynb`**: The main Jupyter Notebook containing the code implementation, including environment setup, Q-learning algorithm, training, evaluation, and visualizations.
- **`README.md`**: This file, providing an overview of the project, setup instructions, and usage guidelines.

## Features

- **GridWorld Environment**: Supports customizable grid sizes, with a default size of 5x5. The environment is easily scalable to larger grids, such as 100x100.
- **Q-Learning Agent**: Implements a tabular Q-learning algorithm with adjustable parameters (`alpha`, `gamma`, `epsilon`) for learning rate, discount factor, and exploration-exploitation balance.
- **Visualization**: Includes visualizations for agent path, visit heatmaps, Q-value convergence, and success metrics, which help in understanding the learning process.

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/Q_Learning_GridWorld.git
   cd Q_Learning_GridWorld

2. **Install Dependencies**:
   Ensure you have Python 3.x installed. Then, install the required Python libraries using pip:
   ```bash
   pip install -r requirements.txt
   ```
   *(Note: Create a `requirements.txt` file with necessary dependencies like `numpy`, `matplotlib`, `seaborn`, etc.)*

3. **Run the Notebook**:
   Open the `Q_Learning_GridWorld.ipynb` notebook in Jupyter and run all cells to execute the Q-learning algorithm and visualize the results.

## Usage

- **Training**: The agent is trained over multiple episodes to learn the optimal policy for navigating the grid and completing the task.
- **Evaluation**: After training, the agent's performance is evaluated based on success rate, path efficiency, and average steps taken.
- **Scalability**: The code is optimized to handle larger grid sizes, such as 100x100, ensuring robustness and scalability.

## Results

- **Success Rate**: The agent achieves a 100% success rate in completing the task across various trials.
- **Path Efficiency**: The agent efficiently finds optimal or near-optimal paths with a high path efficiency score.
- **Exploration-Exploitation Balance**: The agent maintains a balance between exploration and exploitation, leading to effective learning.

## Contribution

Contributions are welcome! If you have suggestions for improvements or additional features, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments

- Thanks to the open-source community for providing valuable resources and tools that made this project possible.
```
