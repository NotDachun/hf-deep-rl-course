# Unit 2 Midway
_Q1: What are the two main approaches to find optimal policy?_
- [X] Policy-based methods
- [ ] Random-based methods
- [X] Value-based methods
- [ ] Evolution-strategies methods

_Q2: What is the Bellman Equation?_

The Bellman Equation is a recursive equation that reduces the redundancy of value estimation by formulating the value estimate at one state as a expected value of the immediate reward plus the reward of of the next state. Rather than computing the value for each state independently, we can reuse sub-problems that are shared between states.

_Q3: Define each part of the Bellman Equation_

- Green: Value of state __s__
- Orange: Expected value of the immediate reward assuming that it uses policy __$\pi$__
- Purple: Discounted value of the value of the next state
- Blue: Given that the current state is __s__


_Q4: What is the difference between Monte Carlo and Temporal Difference learning methods?_

- [X] With Monte Carlo methods, we update the value function from a complete episode
- [ ] With Monte Carlo methods, we update the value function from a step
- [ ] With TD learning methods, we update the value function from a complete episode
- [X] With TD learning methods, we update the value function from a step

_Q5: Define each part of the Temporal Difference learning formula_

- Light green: New value of states __S__ at time __t__
- Blue: Current value of states __S__ at time __t__
- Red: Learning rate __$\alpha$__
- Orange: Immediate reward
- Purple: Discounted value of the value of the next state
- Dark Green: TD target

_Q6: Define each part of the Monte Carlo learning formula_

- Green: New value of states __S__ at time __t__
- Blue: Current value of states __S__ at time __t__
- Red: Learning rate __$\alpha$__
- Orange: Returned rewardm at time __t__