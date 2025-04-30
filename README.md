# Berkeley CS188 Project 6: Reinforcement Learning

This repository contains my implementation of Project 6 from UC Berkeley's CS188: Introduction to Artificial Intelligence. The project focuses on reinforcement learning methods applied to the Pacman environment.

## 📌 Overview

In this project, we implemented several key reinforcement learning techniques:

- **Value Iteration**: Solve a known MDP using dynamic programming to compute the optimal policy.
- **Q-Learning**: Learn the optimal policy through model-free temporal-difference learning.
- **Approximate Q-Learning**: Use feature-based representations to generalize Q-values across large state spaces.
- **(Optional)** Deep Q-Learning: Extend learning to neural networks (not part of the original spec).

The agents are tested in various environments such as Gridworld, Crawler, and Pacman.

## 📁 Project Structure

- `valueIterationAgents.py`: Value Iteration agent implementation.
- `qlearningAgents.py`: Q-Learning and Approximate Q-Learning agent implementations.
- `learningAgents.py`: Base classes for learning agents.
- `mdp.py`: Defines the Markov Decision Process interface.
- `gridworld.py`: Gridworld environment for debugging and evaluation.
- `util.py`: Utility functions including a custom Counter class.
- `featureExtractors.py`: Feature extractors for Approximate Q-Learning.
- `autograder.py`: Autograder script provided by the course.
- `test_cases/`: Folder containing test case definitions.

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/RL_CS188_Proj6.git
   cd RL_CS188_Proj6
