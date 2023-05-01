# Deep-Q-Learning

![image](https://user-images.githubusercontent.com/38746955/235517081-18f1bc6c-dd89-4a90-b562-dcdde1a16d21.png)


In reinforcement learning,myriad states exist so it makes infeasible to use table to 
record actions from state to state.
Instead, using Deep Q Learning is recommended.
Here, we optimize Q function to maximize cumulative reward in RL.
Every action has a fuction and yields Q value.
After training the generated environment,model maximizes reward.


So, what are the steps involved in reinforcement learning using deep Q-learning networks (DQNs)?

1. All the past experience is stored by the user in memory.

2. The next action is determined by the maximum output of the Q-network.

3. The loss function here is mean squared error of the predicted Q-value and the target Q-value – Q*. This is basically a regression problem. However, we do not know the target or actual value here as we are dealing with a reinforcement learning problem. Going back to the Q-value update equation derived fromthe Bellman equation.


![image](https://user-images.githubusercontent.com/38746955/235518351-fecee75e-cdfd-4922-9c46-ccbc40e2dad5.png)
