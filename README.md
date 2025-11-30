# Machine_Learning_algorithms
## Genetic Algorithm (GA)
This project uses a Genetic Algorithm to solve the Task Allocation problem, assigning N tasks to M students with the goal of minimizing the total completion time.

A Genetic Algorithm is a type of metaheuristic algorithm inspired by natural selection and the process of biological evolution. The core concept is based on the principle of “survival of the fittest,” where candidate solutions continuously evolve through recombination and mutation to approach the optimal solution.

### Basic process:
* Selection – Choose individuals with higher fitness as parents.
* Crossover – Recombine parent genes to create offspring.
* Mutation – Randomly modify genes to maintain diversity within the population.
* Elitism – Preserve the best individual from the current generation to the next, preventing degradation.

### Application:
Genetic Algorithms are suitable for various combinatorial optimization problems, especially when exhaustive search is impractical. Common examples include scheduling, task allocation, resource optimization, and routing problems.

### Project summary:
This project applies GA to automatically search for and optimize task assignments. Each generation includes initialization, fitness evaluation, selection, crossover, mutation, and elitism. The objective is to minimize the total task completion time, and the results output the best allocation and total time for each test case, which are written to the file results.txt.

## KNN
