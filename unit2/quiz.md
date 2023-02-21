# Unit 2
_Q1: What is Q-Learning?_
- [x] The algorithm that we use to train our Q-function
- [ ] A value function
- [x] An algorithm that determines the value of being at a particular state and taking a specific action
- [ ] A table

_Q2: What is a Q-table?_
- [ ] An algorithm we use in Q-Learning
- [x] Q-table is the internal memory of our agent
- [ ] In Q-table each cell corresponds to a state value 

_Q3: Why if we have an optimal Q-function Q<sup>*</sup> we have an optimal policy_

With an optimal Q-function, we would know what the optimal action is to take since we know the value of each state-action pair.

_Q4: Can you explain what is Epsilon-Greedy Strategy_

Epsilon-greedy strategy balances explore and exploitation with parameter $\epsilon$ $\in$ [0, 1]. Using this strategy, with $\epsilon$ probability that we take a random action, otherwise we greedily select the best action.

_Q5: How do we update the Q value of a state, action pair?_

We update the Q-value at each time step by the learning rate times difference between the immediate reward plus the discounted estimate Q-value of the next state minus the Q-value of the current state. The term within the brackets is called the Temporal Difference error.

_Q6: What's the difference between on-policy and off-policy_

An on-policy learning algorithm uses the same policy at training and inference time, while an off-policy learning algorithm uses different policies.