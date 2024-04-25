PPO is used to stabilise the policy updates in a given agent.
PPO uses a clipped surrogate function which is easy to compute then the one which trpo uses:

![image](https://github.com/AkshayKulkarni3467/PPO-algorithm/assets/129979542/d2ae1543-fc07-4069-bb2a-e36310c8afa5)

In the PPO paper released by OpenAI, the inputs and middeware are shared, hence it includes an entropy term.
Here in this project, we implement the value neurel network and policy neural network seperately.

Here, we use ppo in A2C to optimise the cart pole problem:

![image](https://github.com/AkshayKulkarni3467/PPO-algorithm/assets/129979542/07c21449-0468-4f50-b912-762b983d7efb)

The PPO helps us to make a stable gradient ascent. Here are a few examples for different alpha and batch_size:

![image](https://github.com/AkshayKulkarni3467/PPO-algorithm/assets/129979542/23b99c95-a20e-4ce7-8c03-5627715f712f)
