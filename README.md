# Reinforcement-Learning-Theory
Collect commonly used theory for reinforcement learning from literature.

## 给定一个策略，证明存在奖励函数，使得这个策略是对应最优策略
Given a policy, there exists a reward function such that the policy is optimal wrt the reward. 
See Lemma 5.1 of [Learning Zero-Shot Cooperation with Humans, Assuming Humans Are Biased](https://arxiv.org/abs/2302.01605)

## (A,B)两个玩家以及各自的奖励(R_a, R_b)，B某一分布策略下A的最佳响应的收益，可以近似等于B的某一分布奖励下(A,B)纳什均衡的收益
Two players (A,B) with their rewards (R_a,R_b). The return of player A given the policy distribution of player B, is approximately equivalent to the Nash equilibrium return of (A,B) under certain reward distribution of player B. 
See Theorem 5.1 of [Learning Zero-Shot Cooperation with Humans, Assuming Humans Are Biased](https://arxiv.org/abs/2302.01605)
