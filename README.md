# 🧗 Cliff Walking — Reinforcement Learning

This project implements **SARSA** and **Q-Learning** on the `CliffWalking-v1` environment using **Gymnasium**.

The objective is to train an agent to navigate from the starting position to the goal while avoiding the cliff and maximizing the cumulative reward.

## 🎯 Learning Objective

This project was built to understand the fundamentals of **model-free Reinforcement Learning**, particularly how SARSA and Q-Learning learn policies through interaction with an environment.
It also provides a foundation for understanding more advanced algorithms such as **Deep Q-Networks (DQN)**.

## 🧠 Algorithms Implemented

- **SARSA** — On-policy Temporal Difference learning
- **Q-Learning** — Off-policy Temporal Difference learning
- Epsilon-Greedy Action Selection
- Temporal Difference (TD) Learning
- Q-Table based learning

## 🎮 Environment

The project uses the `CliffWalking-v1` environment from **Gymnasium**.

The environment is a grid world where:

- The agent starts at the bottom-left corner.
- The goal is at the bottom-right corner.
- The cells between the start and goal represent a cliff.
- Stepping into the cliff results in a large negative reward.
- The agent learns a policy to reach the goal while avoiding the cliff.

## ⚔️ SARSA vs Q-Learning

| Feature | SARSA | Q-Learning |
|---|---|---|
| Type | On-policy | Off-policy |
| Next Action | Action selected by current policy | Best estimated action |
| Learning Target | Q(s', a') | max Q(s', a') |
| Exploration | Reflected in learning | Not reflected in target |

## 🛠️ Technologies Used

- Python
- NumPy
- Gymnasium

## 📂 Project Structure

```text
Cliff Walking/
├── Notebook/
│   ├── SARSA.py
│   └── Q_Learning.py
├── Output/
│   └── cliff_walking.jpg
├── README.md
```

## 📚 Key Concepts

- Reinforcement Learning
- Model-Free Learning
- Markov Decision Processes
- Q-Table
- Epsilon-Greedy Exploration
- Temporal Difference Learning
- On-Policy Learning
- Off-Policy Learning
- SARSA
- Q-Learning

## 👩‍💻 Author

**Heer Shah**

Computer Science & AI/ML Student
