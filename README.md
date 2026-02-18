```Graph Coloring with Genetic Algorithm
The goal is to color the vertices of a graph such that:
1. No two adjacent vertices have the same color.
2. The number of colors used (chromatic number) is minimized.

Input and Output Requirements
Input
Graph G = (V, E) including:
V: Set of vertices (|V| = n)
E: Set of edges (|E| = m)
Adjacency matrix A (n×n) or edge list
Maximum allowed color K_max, for example, 10 for small graphs
GA parameters: PopulationSize, MaxGenerations, Pc, Pm, TournamentSize, ElitismCount.

Output
Color assignment for each vertex: C = {c₁, c₂, …, cₙ}, where cᵢ ∈ {1, 2, …, K}
Number of colors
Number of conflicts = number of edges where two adjacent vertices have the same color
Final fitness value
Fitness trend chart over generations```
