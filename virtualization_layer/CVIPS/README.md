# Curious Value Iteration with Prioritized Sweeping (CVIPS)

Responsible: Erik Nemeth (erik.nemeth@sorbonne-universite.fr)

CVIPS is a discrete model-based reinforcement learning (MB-RL) algorithm used in the context of spatial navigation. CVIPS constructs a virtualized world model in order to generate off-line sequences of experiences that accelerate learning (hippocampal replay). Besides classical food rewards, the algorithm internally generates epistemic rewards proportional to the decrease of uncertainty in the world model. These rewards, alongside the classical food rewards, span a three-dimensional reward space within which Q-values are optimized. As a result, the agent naturally balances exploration and exploitation in line with the active inference framework.

The model forms the basis of an upcoming publication (Nemeth et al., in preparation)
