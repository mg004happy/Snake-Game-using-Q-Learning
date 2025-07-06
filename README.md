🐍 Snake Game using Q-Learning

This project implements the classic Snake Game with an AI agent trained using the **Q-Learning** reinforcement learning algorithm. The goal is to teach the snake to autonomously learn strategies to maximize its score by eating food while avoiding collisions.

---

## 🎮 Features

 Autonomous snake agent that learns through trial and error  
 Q-Table learning with adjustable hyperparameters  
 Interactive training visualization  
 Simple and clean implementation in Python  
 Easily extendable for experimentation  

---

## 🧠 What is Q-Learning?

Q-Learning is a model-free reinforcement learning technique that learns the value of taking a given action in a given state. The Q-value updates according to:

\[
Q(s, a) \leftarrow Q(s, a) + \alpha \left[ r + \gamma \max_{a'} Q(s', a') - Q(s, a) \right]
\]

where:
- **s**: Current state
- **a**: Action taken
- **r**: Reward received
- **s'**: Next state
- **α (alpha)**: Learning rate
- **γ (gamma)**: Discount factor

Over time, the agent learns the optimal policy to maximize rewards.
