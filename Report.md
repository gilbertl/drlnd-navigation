##Implmentation and Algorithm##

We train the agent using a Deep Q-learning Network. We employ two techniques 1) replay memory and 2) fixed target network to keep the learning stable. Some hyper parameters used in training:

replay memory buffer: 10000
minibatch size: 64
gamma (belman equation discount factor): 0.99
tau (soft update of target network's parameters): 0.001
learning rate: 0.0005

##Neural Net Model##

Input layer: 37 units
Hidden Layer: 64 units
Output layer: 4

Each layer is fully connected with RELU activation.

##Episodes##

Episode 100	Average Score: 0.37
Episode 200	Average Score: 4.58
Episode 300	Average Score: 7.77
Episode 400	Average Score: 9.91
Episode 500	Average Score: 12.91
Episode 502	Average Score: 13.01
Environment solved in 402 episodes!	Average Score: 13.01

The environment was solved in 402 episodes with a final average score of 13.01.

##Future Work##
In the future, we might consider using Double Q-Learning, Prioritized Experience Replay, or Dueling DQN to improve our training.


