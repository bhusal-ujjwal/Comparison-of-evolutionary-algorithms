# Comparison of Genetic Algorithm (GA), Differential evolution (Rand/1/bin and jDE) and Particle Swarm Optimization (PSO)
- choose 3 test functions and compare the implemented algorithms: GA, DE (both versions) and PSO

## 3 test functions
- Each test function will be optimized by each algorithm 11x (to have some sort of reasonable statistic)
- Each test function will be optimized for 5D and 30D. Thus the total number of test functions is 6 (3 functions, each in 2 different dimensional settinsg)
- Stop each run of an algorithm after 3,000*D objective function evaluations (15,000 for 5D and 90,000 for 30D)
- Prepare statistical evaluation - average objective function value (OFV), median, standard deviation, min and max for each algorithm on each function and present the results in a readable format - preferably table (ie. pandas dataframe).

## Extra: Compare the average convegrence of different algorithms on the same function.
