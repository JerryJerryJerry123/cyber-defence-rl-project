# cyber-defence-rl-project
# Autonomous Adaptive Cybersecurity System using Supervised and Reinforcement Learning

## Overview
This project implements a hybrid cybersecurity system that combines supervised learning and reinforcement learning to detect and respond to cyber attacks.

The system uses a Random Forest classifier to identify attack types and a Q-learning agent to determine appropriate defensive actions.

## Features
- Intrusion detection using NSL-KDD dataset
- Reinforcement learning-based decision making
- Epsilon-greedy exploration strategy
- Comparison with static rule-based defence
- Evaluation under detection noise

## Technologies Used
- Python
- Scikit-learn
- NumPy
- Matplotlib

## How it Works
1. Network data is classified using a Random Forest model
2. The predicted attack type is used as the RL state
3. The Q-learning agent selects a defensive action
4. Rewards guide the learning process

## Results
- Classification accuracy ~74%
- RL converges to optimal policy
- Static policy outperforms RL in deterministic environments
- RL demonstrates adaptability under exploration

## Key Insight
Reinforcement learning does not outperform static policies in deterministic environments, but provides a framework for adaptive defence in dynamic and uncertain conditions.

## How to Run
1. Install dependencies:
