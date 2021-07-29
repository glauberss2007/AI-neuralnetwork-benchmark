# neuraln-metah
Benchmark for Neural Network training using diferents methaheuristics

## Overview

### Neural Network
![image](https://user-images.githubusercontent.com/22028539/127484502-dee629e9-4b38-4767-b853-e9d53f386230.png)

A neural network is a network or circuit of neurons, or in a modern sense, an artificial neural network, composed of artificial neurons or nodes. Thus a neural network is either a biological neural network, made up of biological neurons, or an artificial neural network, for solving artificial intelligence (AI) problems. The connections of the biological neuron are modeled as weights. A positive weight reflects an excitatory connection, while negative values mean inhibitory connections. All inputs are modified by a weight and summed. This activity is referred to as a linear combination. Finally, an activation function controls the amplitude of the output. For example, an acceptable range of output is usually between 0 and 1, or it could be −1 and 1.

### Methaheuristics
![image](https://user-images.githubusercontent.com/22028539/127484918-c5b0b8cb-d8c9-418f-8930-64964df8c635.png)

A metaheuristic is a higher-level procedure or heuristic designed to find, generate, or select a heuristic (partial search algorithm) that may provide a sufficiently good solution to an optimization problem, especially with incomplete or imperfect information or limited computation capacity. Metaheuristics sample a subset of solutions which is otherwise too large to be completely enumerated or otherwise explored. Metaheuristics may make relatively few assumptions about the optimization problem being solved and so may be usable for a variety of problems.

Calculate parameters for a deep NN can take too much time so we combine methaheurist + neural network to improve speed.

#### Neural Network + Genetic Algorithym
![image](https://user-images.githubusercontent.com/22028539/127486746-af824ef5-c13b-4b13-aff9-ef28993d2cb9.png)

A individual is defined by a set of numbers that are the parameters of a NN.
1. The conections in green and red represents positive and negative links while width represents the intensity. 
2. The two first neuron are the inputs
3. They are what individuals sees of its environment
4. The last one is the output representing the response related to that input
5. With a defined objective, we initialize creating a random set of individual 
6. When all individual are done we create a new generation composed by the bests of previous one mixing best parameters
7. A mutation is a simply and rare random modification of a parameter allowing emergence of new solutions

## AI Playing Flappy Bird
The researcher did not provide any information about what the bird or pipes look like to the agent, and the agent must learn these representations and directly use the input and score to develop an optimal strategy. 

### NN + Genetic Algorithym

### NN + Simulated Anealing

### NN + Tabu Search

### NN + MultiStart

### NN + Variable Neighborhood Search








