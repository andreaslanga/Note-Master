---
share: true
---


# How we learn
by Stanislas Dehaene

C. elegans: 
- strong genetic determinism: most worms have exactly 959 cells, incl. 302 Neurons, but it learns nontheless -> better adaption in different environments, that pre-wired neurons!
- 2 Forms of Learning:
	- *Habituation*: an organism's capacity to adapt to the repeated presence of a stimulus and eventually cease to respond to it
	- *Association*: discovering and remembering what aspects of the environment predict sources of food or danger

## Chapter 1

### Learning = forming an *internal model* of the external world

1. Learning is adjusting the parameters of a mental model
2. Learning is exploiting a combinatorial explosion
- combinatorial explosion = exponential increase when you combine even a small number of possibilities
- brain breaks down the problem of learning by creating *hierarchical multilevel model*
3. Learning is minimizing errors
4. Learning is exploring the space of possibilities
- **randomness** is an essential ingredient of a solution -> prevents being stuck a a *local* minimum, rather than the global minimum of error
5. Learning is optimizing a reward function
- Problem: If reward is delayed (Win/Loss of a chess game only known at the end)
	- Solution: actor-critic combination:
		- critic: learns to predict the final score
		- actor: uses the critic's evaluation to correct itself at every moment, not only at the end
- Bootstraping in AI: neural network becomes better by playing against itself
6. Learning is restricting search space
- "curse of dimensionality" = learning becomes very hard if you have millions of potential levers to pull
7. Learning is projecting a priori hypotheses


## Chapter 2
