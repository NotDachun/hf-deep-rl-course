# Unit 3
_Q1: We mentioned Q-Learning is a tabular method. What are tabular methods?_

Tabular methods are methods that save their value function in a table. They work well for environments will small observation and action spaces.

_Q2: WHy can't we use a classifical Q-Learning to solve an Atari Game?_

- [ ] Atari environments are too fast for Q-Learning
- [x] Atari environments have a big observation space. So creating and updating the Q-Table would not be efficient

_Q3: Why do we stack four frames together when we use frames as input in Deep Q-learning?_

With Atari games that provide their observations in frames, a single frame is not enough information to capture temporal information - for instance, what direction is the ball traveling in Pong. So, by stacking four frames together we can overcome this temporal limitation.

_Q4: What are the two phases of Deep Q-Learning?_
- [x] Sampling
- [ ] Shuffling
- [ ] Reranking
- [x] Training

_Q5: Why do we create a replay memory in Deep Q-Learing?_

We sample a batch of instances for training from a replay memory to stablize neural network training. This prevents the model from forgetting earlier experiences or overfitting to a sequence of events.

_Q6: How do we use Double Deep Q-Learing?_

With Double Deep Q-Learning, we have independent networks - one for determining the best action given a state and a second for estimating the Q-value of that state-action pair. This prevents the problem of overestimating the Q-value when our network at the beginning of training.