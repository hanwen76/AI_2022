## what is an agent?
- perceiving through sensor
- acting through actators
## rationality
- the actions to be most successful -> measure success -> *performance measure*
- prior knowledge of env
- actions that agent can perform
- percept sequence
## rational agent
- learning
- autonomy
## Properties of task environments
- Deterministic: next state of the environment Completely determined by the current state and the actions
- Stochastic : otherwise
- Strategic environment: deterministic except for actions of other agents
## structure of agents
- Agent = architecture + program
## Share1: 惊喜最小化agent
- motivation: static and predictable status
- agent目的：长远来看环境熵最小，但不清楚完整的真实状态分布（需估计）
## Share2: diffusion model
- motivation: 减少计算量，在低维空间训练
## Types of agent programs
- Four Types
  - simple reflex 
     condition-action-rules -> if...then... stated & status
  - model-based reflex 
     far more complex condition-action-rules & dynamic
  - goal-based 
     less efficient but more flexible & different goal -> different action
  - utility-based
     high-quality 
  - *learning agent