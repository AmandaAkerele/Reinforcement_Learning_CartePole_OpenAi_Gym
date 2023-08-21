Deep Q-Network (DQN) Agent for CartPole-v1 OpenAi_Gym

This repository contains code to train and test a Deep Q-Network (DQN) agent on the "CartPole-v1" environment using the Keras-RL library.

## Overview

The DQN algorithm is a powerful technique for training agents to learn optimal policies in reinforcement learning tasks. In this project, we utilize the Keras-RL library to implement and train a DQN agent to balance a pole on a cart in the "CartPole-v1" environment.

## Getting Started

1. **Installation**:
   Make sure you have the necessary dependencies installed. You can install the required packages using the following command:
   ```bash
   pip install gym keras-rl matplotlib
   ```

2. **Repository Cloning**:
   Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/dqn-cartpole.git
   cd dqn-cartpole
   ```

3. **Training and Testing**:
   Run the provided Python script to train and test the DQN agent:
   ```bash
   python dqn_cartpole.py
   ```

## Contents

- `dqn_cartpole.py`: Main script for training and testing the DQN agent.
- `README.md`: This README file with project information.
- Other relevant files and dependencies.

## Training Process

1. The DQN agent's neural network model is defined using the Keras Sequential API.
2. The agent is initialized with the defined model, a memory for experience replay, a policy (BoltzmannQPolicy), and other configuration parameters.
3. The agent is trained using the `fit` method with a specified number of training steps.
4. Training statistics are displayed for each interval, including episode rewards, loss, MAE, and mean Q-value.
5. The trained agent is tested on 10 episodes to evaluate its performance.

## Results

The DQN agent's performance improves as the training steps increase. During testing, the agent achieves a perfect score of 500 in each of the tested episodes, indicating successful learning and policy optimization.

## Conclusion

This project demonstrates the application of the Deep Q-Network (DQN) algorithm to solve the "CartPole-v1" environment using the Keras-RL library. The agent learns to balance the pole on the cart effectively and achieves high performance during testing.

