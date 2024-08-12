# Lunar Lander: Deep Q-Learning for Lunar Landing

This project demonstrates the application of Deep Q-Learning (DQL) to solve the Lunar Lander problem, a classic reinforcement learning challenge. The goal is to train an agent to successfully land a lunar module on the moon's surface using optimal control strategies.

## Project Overview

- **Environment**: The Lunar Lander environment from OpenAI's Gym library.
- **Algorithm**: Deep Q-Learning (DQL), an advanced reinforcement learning algorithm that combines Q-Learning with deep neural networks.
- **Objective**: Train an agent to land the lunar module safely by optimizing its actions through experience and exploration.

## Features

- Implementation of a Deep Q-Network (DQN) with experience replay and target network.
- Visualization of training progress and agent's performance.
- Evaluation of the trained agent's ability to land the lunar module in different scenarios.

## Requirements

To run this project, you need the following dependencies:
- Python 3.x
- TensorFlow or PyTorch (for the deep learning models)
- NumPy
- OpenAI Gym
- Matplotlib (for visualizations)

You can install the required packages using pip:
```bash
pip install numpy gym matplotlib tensorflow  # or pytorch instead of tensorflow
```

## How to Run
1. **Clone the Repository**:
```bash
git clone https://github.com/dhritishetty/LunarLander
```
2. **Run the Notebook**:
Open the `Deep_Q_Learning_for_Lunar_Landing.ipynb` notebook in Jupyter and run the cells to train the agent.

3. **Evaluate the Agent**:
After training, evaluate the agent's performance by running the evaluation cells in the notebook.
