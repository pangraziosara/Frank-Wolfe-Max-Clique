# Evaluation of Results of Frank Wolfe Algorithms and Variants with the Maximum Clique Problem

**Authors:** Sara Pangrazio, Nicola Bazzani

Project for *Optimization for Data Science*, University of Padova, 2025

We benchmark Frank–Wolfe, Away-Step Frank–Wolfe, and Pairwise Frank–Wolfe on the Maximum Clique Problem. For a graph 
G=(V,E), a clique is a set of vertices with all pairwise edges present; the goal is to find the largest such set. We use the MCP formulation introduced in 
[Hungerford & Rinaldi, 2019] (https://arxiv.org/abs/1709.02486) and evaluate how the three methods perform on this constrained maximization problem.

## Data
To test the algorithms, we considered three different datasets from three families of maximum cliques instances belonging to the DIMACS benchmark:
-  p_hat300-3,
-  C125.9,
-  hamming8-4.

## References
- Hungerford, J. T., & Rinaldi, F. (2019), *A General Regularized Continuous Formulation for the Maximum Clique Problem*, https://arxiv.org/abs/1709.02486
- DIMACS Implementation Challenges - Maximum Clique Benchmark, https://www.dcs.gla.ac.uk/~pat/jchoco/clique/dimacs/DIMACS_cliques/
