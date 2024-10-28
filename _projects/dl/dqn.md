---
layout: page
title: Deep Reinforcement Learning
description: Q Learning and Deep Q-Learning to train agents that plays different games
img: assets/img/personal/breakout.png
importance: 1
category: fun
tags: ["Deep Learning", "Python", "DQN", "Reinforcement Learning"]
related_publications: false
---
I implemented Q-table and Deep Q-Learning algorithms to play various games, including Cart Pole, Flappy Bird, and Breakout, using the OpenAI Gym. This project provided hands-on experience in reinforcement learning and sequence models. The input to these algorithms was either raw pixel values or game-specific state information, enabling the models to learn and play each game.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <div class="row">
            {% include figure.liquid loading="eager" path="https://github.com/yosephberhanu/rl-tutorial/blob/main/dqn/cartpole/screenshot.png?raw=true" title="Cart Pole Screenshot" class="img-fluid rounded z-depth-1" %}
        </div>
        <div class="row">
            {% include figure.liquid loading="eager" path="https://github.com/yosephberhanu/rl-tutorial/blob/main/q_table/mountain_car/screenshot.png?raw=true" title="Mountain Car Screenshot" class="img-fluid rounded z-depth-1" %}
        </div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
            {% include figure.liquid loading="eager" path="https://github.com/yosephberhanu/rl-tutorial/blob/main/q_table/custom_environment/sample.png?raw=true" title="Custom environment screenshot" class="img-fluid rounded z-depth-1" %}
    </div>

</div>

#### Key Features:
- Implemented Q-table-based reinforcement learning for small environments.
- Developed Deep Q-Learning and Double Q-Learning algorithms.
- Created a custom environment and game.
- Trained models on an Atari game from the OpenAI Gym.

#### Tools and Resources:
- Python
- PyTorch
- Anaconda Python (for local work)
- [VT ARC](https://arc.vt.edu/) cluster (for GPU access)

### Source Code
The complete source code for this project is available on [GitHub](https://github.com/yosephberhanu/rl-tutorial).

__Cover Image Credit__: [Cool Math Games Blog](https://www.coolmathgames.com/blog/how-to-play-atari-breakout)