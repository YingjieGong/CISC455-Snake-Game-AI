# CISC455-Snake-Game-AI
**Description**: Our project is to use a Evalution Algoraithm to find out a best nueral network model to play the snake game.
**Introduction:** We use neural network model to predict which direction should the snake move, and we use evolutionary algorithm to adjust the weight of the neural network models. Each of the individual is defined by genes which stores the weight of a neural network model. 
- **Representation**: Weights parameter of the NN model
- **Recombination**: Single point cross over
- **Recombination probability**: 100%
- **Mutation**: Gaussian Function
- **Mutation Rate**: 10%
- **Parent Selection**: Tounament selection
- **Survival Selection**: Elitism selection
- **Population size**: 100
- **Number of offspring**: 2
- **Initialization**: Uniformly Random
- **Termination condition**: reach score 97(initial body size 3)

Fitness Function we used is quite simple, it is mainly decided by score((score+1/steps)*100000), steps has little influence on the fitness. That caused the snake will hanging around and waste many useless steps. We may improve this in further work.
