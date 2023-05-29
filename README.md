# A-Proactive-Approach-to-Policy-Learning
<img width="370" alt="Screenshot 2023-03-21 at 11 37 25 AM" src="https://github.com/YoshaM09/A-Proactive-Approach-to-Policy-Learning/assets/105993890/6d172fb3-898f-4e72-80c2-1f021ba1d622">

### Purpose:

Change MDP (Markov Decision Process) by introducing skip connections.

### Problem Statement:

With traditional RL, learning a policy can be slow and it is not sample efficient. It is challenging to learn when it is necessary to execute new decisions. This makes learning inefficient, especially in environments that need various degrees of fine and coarse control.

### How the problem was efficiently solved using the new approach:

Using skip connections makes new approach sample efficient and allows us to learn the skip-policy for repeating the same action along these skips.
The improved learning speed comes from the ability of repeating actions and to learn which repetitions are helpful for better exploration.
This also allowed us to decide when it becomes beneficial to switch actions.
### Impact:

Optimized a deep reinforcement learning agent to efficiently comprehend environment and achieve goal faster compared to traditional Q-Learning by introducing a skip policy in Markov Decision Process. Improved learning speed, better exploration.

### Tools & Tech: Python, Google Colab
