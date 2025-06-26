# -LunarLander-PPO-Agent
A Reinforcement Learning (RL) agent trained using the PPO (Proximal Policy Optimization) algorithm to land a lunar module safely and precisely on the landing pad.

#  How It Works
The Lunar Lander agent learns to control a spaceship that's trying to land safely on a designated landing pad.

The agent gets 8 pieces of information about the lander’s current state , including things like:

     -Its horizontal and vertical position

     -Speed (velocity) in both directions

     -Angle (tilt) of the lander

     -Whether the left or right legs are touching the ground

Based on this, the agent picks one action at a time from these options:

     -0: Do nothing

     -1: Fire left engine (tilts right)

     -2: Fire main engine (goes straight up or slows descent)

     -3: Fire right engine (tilts left)

The main goal? Land smoothly on the pad without crashing.
To encourage better landings, we’ve added a custom reward system that gives bonus points for landing precisely near the center of the pad, promoting safer and more accurate landings.

# Getting Started
# Install Dependencies
Make sure you have Python installed. Then, open your terminal and run:
     -pip install gymnasium stable-baselines3

# Features
     -Custom reward system — Encourages smooth and precise landings near the center.
     -PPO algorithm — Reliable and stable reinforcement learning method.
     -Clean, simple, and beginner-friendly code — Easy to understand and modify.

# Credits
Gymnasium — For providing the LunarLander environment.

PPO reinforcement learning implementation — https://medium.com/@danushidk507/ppo-algorithm-3b33195de14a
