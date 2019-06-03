# Reinforcement-Learning
Reinforcement learning is an important type of Machine Learning where an agent learn how to behave in a environment by performing actions and seeing the results.
Q-learning is a value-based Reinforcement Learning algorithm that is used to find the optimal action-selection policy using a q function.
It evaluates which action to take based on an action-value function that determines the value of being in a certain state and taking a certain action at that state.
Goal: maximize the value function Q (expected future reward given a state and action).
Q table helps us to find the best action for each state.
To maximize the expected reward by selecting the best of all possible actions.
The Q come from quality of a certain action in a certain state.
Function Q(state, action) → returns expected future reward of that action at that state.
This function can be estimated using Q-learning, which iteratively updates Q(s,a) using the Bellman Equation
Before we explore the environment: Q table gives the same arbitrary fixed value → but as we explore the environment → Q gives us a better and better approximation.
