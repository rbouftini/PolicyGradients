# Survey of Policy Gradients

This repository provides an in-depth exploration and implementation of various policy gradient methods used in reinforcement learning. The focus is on understanding and comparing different techniques to optimize policies in both simple and complex environments.

## Key Methods Covered

### 1. Vanilla Policy Gradient (VPG)

- **Description**: A foundational approach where the policy is directly parameterized and optimized using gradient ascent.
- **Implementation**: Includes training an agent to play Tic Tac Toe and evaluating its performance.

### 2. Policy Gradient with Baseline

- **Description**: Enhances VPG by introducing a baseline (typically an estimate of the value function) to reduce variance in gradient estimates.
- **Implementation**: Demonstrates how adding a baseline can stabilize training, using the Lunar Lander environment from OpenAI Gym.

### 3. Proximal Policy Optimization (PPO)

- **Description**: An advanced policy gradient method that clips the probability ratio to prevent large policy updates, ensuring stability and sample efficiency.
- **Implementation**: Provides a detailed implementation of PPO, showcasing its effectiveness in handling complex environments like Lunar Lander.
