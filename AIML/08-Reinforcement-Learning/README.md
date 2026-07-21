# Reinforcement Learning

## Foundations

- Agents, environments, observations, states, actions, rewards, episodes, and returns
- Markov property and Markov decision processes
- Policies, state-value functions, action-value functions, and advantages
- Discounting, horizons, exploration, exploitation, and credit assignment
- Bellman expectation and optimality equations

## Classical Methods

- Multi-armed bandits
- Dynamic programming: policy evaluation, policy iteration, and value iteration
- Monte Carlo prediction and control
- Temporal-difference learning
- SARSA and Q-learning
- Eligibility traces concepts

## Deep Reinforcement Learning

- Function approximation and the deadly-triad intuition
- Deep Q-networks, replay buffers, target networks, and exploration schedules
- Policy gradients and REINFORCE
- Actor-critic methods
- Advantage estimation and PPO
- Model-based, offline, imitation, and multi-agent RL concepts

## Practical Concerns

- Reward design and unintended behavior
- Sample efficiency and unstable training
- Environment wrappers, seeds, and reproducibility
- Evaluation over multiple episodes and random seeds
- On-policy versus off-policy data
- Safety constraints and human oversight

## Required Builds

1. Multi-armed bandit strategies
2. Value iteration on a small MDP
3. Tabular Q-learning and SARSA
4. DQN in a simple environment
5. Policy-gradient or PPO experiment

## Mastery Checklist

- [ ] I can derive and interpret Bellman equations.
- [ ] I understand model-free versus model-based learning.
- [ ] I can explain on-policy versus off-policy methods.
- [ ] I understand value-based versus policy-based approaches.
- [ ] I evaluate across seeds rather than reporting one lucky run.
- [ ] I can identify poor reward design and unstable conclusions.
