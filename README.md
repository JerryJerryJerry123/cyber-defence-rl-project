# cyber-defence-rl-project
# Autonomous Adaptive Cybersecurity System

## Overview
This project implements a hybrid cybersecurity system combining supervised learning and reinforcement learning.

A Random Forest model detects cyber attacks, and a Q-learning agent selects defensive actions.

## Features
- Intrusion detection using NSL-KDD dataset
- Reinforcement learning-based defence
- Epsilon-greedy exploration strategy
- Static vs RL comparison
- Noise robustness evaluation

## How it Works
1. Network traffic is classified
2. Classification becomes RL state
3. RL agent selects action
4. Rewards guide learning

## Results
- ~74% classification accuracy
- RL converges to optimal policy
- Static performs better in deterministic environments
- RL shows adaptive learning behaviour

## Key Insight
Reinforcement learning is most effective in dynamic environments, not static ones.

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook ids_detection.ipynb
