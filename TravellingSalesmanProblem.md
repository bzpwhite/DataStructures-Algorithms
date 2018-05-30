# Travelling Salesman Problem

The travelling salesman problem (TSP) asks the following question: 
"Given a list of cities and the distances between each pair of 
cities, what is the shortest possible route that visits each city 
and returns to the origin city?"

![Travelling Salesman](https://upload.wikimedia.org/wikipedia/commons/1/11/GLPK_solution_of_a_travelling_salesman_problem.svg)

Solution of a travelling salesman problem: the black line shows 
the shortest possible loop that connects every red dot.

![Travelling Salesman Graph](https://upload.wikimedia.org/wikipedia/commons/3/30/Weighted_K4.svg)

TSP can be modelled as an undirected weighted graph, such that 
cities are the graph's vertices, paths are the graph's edges, 
and a path's distance is the edge's weight. It is a minimization 
problem starting and finishing at a specified vertex after having 
visited each other vertex exactly once. Often, the model is a 
complete graph (i.e. each pair of vertices is connected by an 
edge). If no path exists between two cities, adding an arbitrarily 
long edge will complete the graph without affecting the optimal tour.

## References

- [Wikipedia](https://en.wikipedia.org/wiki/Travelling_salesman_problem)

# 旅行商问题

旅行商问题，即TSP问题（Traveling Salesman Problem）又译为旅行推销员问题、货郎担问题，是数学领域中著名问题之一。假设有一个旅行商人要拜访n个城市，他必须选择所要走的路径，路径的限制是每个城市只能拜访一次，而且最后要回到原来出发的城市。路径的选择目标是要求得的路径路程为所有路径之中的最小值