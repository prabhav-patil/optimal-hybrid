# optimal-hybrid
An attempt to analyze and compare different optimization techniques

# Motivation
I had a recent encounter with Simulated Annealing and Genetic Algorithms in pursuit of finding an optimal solution for the Expectation-Maximization.
While the algorithm itself could run after some number of iterations, there was no guarantee that it would produce an optimal solution in a single run unless we the initial parameters ( such a mean, mixing coefficients and standard deviation in the case of Gaussian Mixtures ) need to be initialized in some particular fashion.
This is because the EM Algorithm succeeds in finding the solution such that the corresponding objective function has a local extrema, rather than providing a optimal solution. Hence, this project attempts to compare the optimization algorithm techniques to generate an optimal solution.

# Aim
This project is an attempt at comparing the time and the memory complexities of optimization algorithms, which would always result in an optimal solution. While comparing, we might also discuss the pros and cons of each optimization, while attempting to model a new hybrid.

# Technologies Used
1. Python 3
2. NumPy
3. MatPlotLib
