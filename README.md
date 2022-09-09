
# CartPole Balance_Deep QLearning 


![animation](https://cdn-images-1.medium.com/max/1600/1*k21guf6QlOMpVJPw1Z3Vlw.gif)
## Cartpole Problem
Cartpole - known also as an Inverted Pendulum is a pendulum with a center of gravity above its pivot point. It’s unstable, but can be controlled by moving the pivot point under the center of mass. The goal is to keep the cartpole balanced by applying appropriate forces to a pivot point.
A pole is attached by an un-actuated joint to a cart, which moves along a frictionless track. The system is controlled by applying a force of +1 or -1 to the cart. The pendulum starts upright, and the goal is to prevent it from falling over. A reward of +1 is provided for every timestep that the pole remains upright. The episode ends when the pole is more than 15 degrees from vertical, or the cart moves more than 2.4 units from the center.
## DQN 
DQN is a RL technique that is aimed at choosing the best action for given circumstances (observation). Each possible action for each possible observation has its Q value, where ‘Q’ stands for a quality of a given move.


## Demo


#### *Before training*
![alt text](https://github.com/farhadvaseghi/CartPole/images/Before_training.gif)
#### *After training*
![alt text](https://github.com/farhadvaseghi/CartPole/images/After_training.gif)

