# Bridges in Graph

In graph theory, a **bridge**, **isthmus**, **cut-edge**, or **cut arc** is an edge 
of a graph whose deletion increases its number of connected components. Equivalently, 
an edge is a bridge if and only if it is not contained in any cycle. A graph is said 
to be bridgeless or isthmus-free if it contains no bridges.

![Bridges in graph](https://upload.wikimedia.org/wikipedia/commons/d/df/Graph_cut_edges.svg)

A graph with 16 vertices and 6 bridges (highlighted in red)

![Bridgeless](https://upload.wikimedia.org/wikipedia/commons/b/bf/Undirected.svg)

An undirected connected graph with no cut edges

![Bridges in graph](https://www.geeksforgeeks.org/wp-content/uploads/Bridge1.png)

![Bridges in graph](https://www.geeksforgeeks.org/wp-content/uploads/Bridge2.png)

![Bridges in graph](https://www.geeksforgeeks.org/wp-content/uploads/Bridge3.png)

## References

- [GeeksForGeeks on YouTube](https://www.youtube.com/watch?v=thLQYBlz2DM&list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8)
- [Wikipedia](https://en.wikipedia.org/wiki/Bridge_%28graph_theory%29#Tarjan.27s_Bridge-finding_algorithm)
- [GeeksForGeeks](https://www.geeksforgeeks.org/bridge-in-a-graph/)

# 桥

在图这种数据结构中，设无向图G=<V,E>,若存在E'⊆E使得p(G-E')>p(G),且对于任意的E''⊂E',均有p(G-E'')=p(G),则称E'是G的边割集，或简称为割集。若E'={e}，则称e为割边或桥。