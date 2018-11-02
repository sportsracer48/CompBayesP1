# Bayes Agent Automata
Henry Rachootin


I want to investigate cellular automata in which each cell has a Bayesian state (a suite of hypotheses) and at each tick they update their beliefs by sampling from their neighbors. I want to create stochastic versions of well known automata like the game of life or its may variants. 

I think that this could easily have some interesting emergent behavior, and could probably used to model belief propagation in geographic networks. I also suspect that even quite boring deterministic automata could display interesting behavior when upgraded to a Bayesian form. 

This project isn’t going to require a ton of data, since it’s mostly made up, which is nice. I’m going to have to do some reading on Bayesian networks to build the inference models that the cells will use. [Here’s a link to a source I’m currently reading on them.](https://towardsdatascience.com/introduction-to-bayesian-networks-81031eeed94e)

To begin I think I’m going to implement a Bayesian game of life, where each cell tracks a hypotheses about how alive/dead it is as well as hypotheses about its neighbors, and updates it’s state by first sampling its neighbors to update what it thinks of them, then updates itself based on a sample of what it thinks of its neighbors. I want to see if I can tune the parameters to give stable life-like behavior (like gliders). This will work as a concrete starting point, and I will definitely find directions to go from there.

I am a bit concerned that this will be too open ended, but not so concerned that I’m not going to try.

I’m working alone, so I don’t think I’m gonna use a trello.
