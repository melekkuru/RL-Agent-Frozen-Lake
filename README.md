# RL Agent: Frozen Lake

Reinforcement learning agents solving the **Frozen Lake** environment using **Monte Carlo** and **SARSA** algorithms. The agent learns to navigate a slippery grid world, reaching the goal while avoiding holes.

> Developed as part of the **Dynamic Programming and Reinforcement Learning (MA338)** module at the University of Essex.

---

## Overview

Frozen Lake is a classic RL benchmark where an agent must traverse a grid from start to goal on a frozen surface. Some tiles are holes that end the episode, and the ice is slippery — actions don't always produce the intended movement.

**Two algorithms are implemented:**

1. **Monte Carlo Method** — learns from complete episodes, averaging cumulative rewards for policy updates
2. **SARSA** — on-policy temporal-difference learning for step-by-step Q-value updates

---

## Key features

- Epsilon-greedy exploration with configurable decay
- Q-table-based value estimation
- Visualization of reward convergence across episodes
- Policy extraction and comparison between methods
- Analysis of convergence speed and final performance

---

## Results

- Both agents successfully learn to solve the Frozen Lake environment
- Reward trends show clear learning progression across training episodes
- Monte Carlo and SARSA converge to similar optimal policies
- Trade-offs between the two methods are discussed in the notebook

---

## Project structure

```
RL-Agent-Frozen-Lake/
├── Frozen_Lake_RL_Agent.ipynb   # Main implementation and analysis
├── requirements.txt
└── README.md
```

---

## Getting started

```bash
git clone https://github.com/melekkuru/RL-Agent-Frozen-Lake.git
cd RL-Agent-Frozen-Lake

pip install -r requirements.txt

jupyter notebook Frozen_Lake_RL_Agent.ipynb
```

---

## Technologies

Python · OpenAI Gym · NumPy · Matplotlib

---

## License

This project is for educational purposes. Feel free to use it as a reference.
