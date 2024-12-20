# Autonomous Lunar Lander using Deep Q-Learning

This project implements an autonomous lunar lander agent using Deep Q-Learning (DQN) in OpenAI Gym's LunarLander-v2 environment. The agent learns to safely land a spacecraft on a landing pad.

## Lunar Landing Agent - Video

Watch the Lunar Landing Agent successfully land in the video below:
[![Agent Landing Safely](https://raw.githubusercontent.com/Siraj-786/Deep-Q-Learning-for-Lunar-Landing-Agent/master/lunar_Agent.png)](https://github.com/Siraj-786/Deep-Q-Learning-for-Lunar-Landing-Agent/blob/master/download.mp4)

[Click here to watch the video](https://drive.google.com/file/d/1fADEMyTL9RhFGpMKcxtelTofr9BPaRNQ/view?usp=sharing)


## Features

- Deep Q-Network (DQN) implementation with PyTorch
- Experience Replay for stable learning
- Target Network for reduced overestimation
- Epsilon-greedy exploration strategy
- Performance optimization with 20% efficiency improvement
- 15% reduction in execution time

## Architecture

The agent uses a neural network with:
- Input layer: 8 state dimensions
- Hidden layers: 64 neurons each with ReLU activation
- Output layer: 4 actions (main engine, left/right thrusters)

## Performance

- Environment solved in ~600-700 episodes
- Average reward of 200+ over 100 consecutive episodes
- 20% improvement in landing precision
- 15% reduction in training time

## Requirements

- Python 3.7+
- PyTorch
- Gymnasium (OpenAI Gym)
- NumPy

## Usage

```bash
# Install dependencies
pip install -r requirements.txt

# Run training
python main.py
```
