# Decision making model
## Overview

Here we show how the Markov decision process (MDP) framework can be extended to allow uncertainty about the states. This can be used to model a wide range of decision-making problems where there is uncertainty or noise associated with the state of the world.

We consider the example of the random dot motion discrimination task, where a subject must indicate the direction in which the majority of dots are moving. Here we model a two-stage formulation of this task, where the decision-maker can either make an immediate decision (i.e., at the first stage) on the basis of initial information, or choose to wait and gather further information before making their choice (i.e., at the second stage). The complete description of the problem can be found in the original paper: http://www.gatsby.ucl.ac.uk/~dayan/papers/NDM002wc.pdf

## Structure

1. Environment and Dependencies Setup
2. Modelling decision making under uncertainty
3. Updating the belief state & Solving for the optimal actions
4. Visualization of results
5. Conclusion

## Conclusion
The overall structure and content of the notebook serve as a comprehensive guide to understanding and implementing Bayesian decision-making models, with practical code examples and visualizations to illustrate the concepts.
