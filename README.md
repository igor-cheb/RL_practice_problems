Several practice problems for key RL methods.

**Tabular methods** </br>
- 10 hand bandit problem (In Sutton/Barto section 2.3)
- Simple gridworld (In Sutton/Barto fig. 4.1) - dynamic programming, policy improvement
- Jack's car rental (In Sutton/Barto ex. 4.7) - dynamic programming, policy iteration
-  Racetrack (In Sutton/Barto: ex. 5.12, p.111) — Off-policy MC
-  Windy Gridworld with King’s Moves (In Sutton/Barto: ex. 6.9)  — SARSA (TD)
-  Taxi-dispatch - https://gym.openai.com/envs/Taxi-v3/ — Q-learning
-  Mazeworld - Dyna-Q
-  Hard Racetrack - Dyna-Q with prioritised sweeping

**Policy gradient methods**
- REINFORCE
- A2C
  - One network, actor and critic are updated after each episode
  - 2 networks, actor updated and episode end, critic is updated every step of the trajectory
  - 2 networks, both actor and critic are upated at each step of the trajectory
