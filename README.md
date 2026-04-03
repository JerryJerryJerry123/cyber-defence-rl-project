# Autonomous Adaptive Cybersecurity Using Supervised and Reinforcement Learning

## Overview

This project implements a hybrid cybersecurity system that combines supervised learning for intrusion detection with reinforcement learning for adaptive defence.

The system classifies network traffic using a Random Forest model and uses Q-learning to determine appropriate defensive actions.

## Features

* Intrusion detection using NSL-KDD dataset
* Random Forest classification
* Q-learning agent for decision-making
* Evaluation using confusion matrix and reward metrics
* Noise simulation for realistic testing

## Technologies Used

* Python
* Scikit-learn
* NumPy
* Matplotlib

## How to Run

1. Install dependencies:

```
pip install -r requirements.txt
```

2. Run the notebook:

```
jupyter notebook
```

## Results

* Classification accuracy ~74%
* Reinforcement learning converges to optimal policy
* Performance evaluated under detection noise

## Repository Structure

* `notebook.ipynb` → Main implementation
* `requirements.txt` → Dependencies

## Author

Jerry Lin
