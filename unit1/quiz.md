# Unit 1 Quiz
_Q1: What is Reinforcement Learning?_

Reinforcement learning is the framework for solving tasks through an agent that learns from the rewards of interacting with an environment in order to maximize their reward.

_Q2: Define the RL Loop_

At every step:
- Our Agent receives __state s0__ from the environment
- Based on that __state s0__ the Agent takes an __action a0__
- Our Agent will move to the right
- The Environment goes to a __new state s1__
- The environment gives a __reward r1__ to the Agent

_Q3: What's the difference between a state and an observation?_

- [x] The state is a complete description of the state of the world (there is no hidden information)
- [ ] The state is a partial description of the state
- [ ] The observation is a complete description of the state of the world (there is no hidden information)
- [x]  The observation is a partial description of the state
- [x] We receive a state when we play with chess environment
- [ ] We receive an observation when we play with chess environment
- [ ] We receive a state when we play with Super Mario Bros
- [x] We receive an observation when we play with Super Mario Bros

_Q4: A task is an instance of a Reinforcement Learning problem. What are the two types of tasks?_

- [x] Episodic
- [ ] Recursive
- [ ] Adversarial
- [x] Continuing

_Q5: What is the exploration/exploitation tradeoff?_

A reinforcement learning agent must balance between exploring new actions and states to find the global maxima with exploiting the current information that it is aware to maximize reward. To explore the environment, the agent can try random actions to discover unseen outcomes. To exploit, an agent takes the best known action in each state to maximize reward as well as it knows how to.

_Q6: What is a policy?_

A policy is like the brain of an agent - given the state of the environment, it decides what the next action is.

_Q7: What are value-based methods?_

Value-based methods assign an expected value to each state of the environment. This allows the agent to select the action that yields the state with the highest value.

A value function maps a state to the expected value of being at that state.

_Q8: What are policy-based methods?_

Policy-based methods assign an expected value to each action for the current state of the environment. This allows th agent to select the action with the highest value.

A policy function maps each state to the best corresponding action at that state or a probability distribution over the set of possible actions at that state.