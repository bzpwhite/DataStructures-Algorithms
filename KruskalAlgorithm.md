# Kruskal's Algorithm

Kruskal's algorithm is a minimum-spanning-tree algorithm which 
finds an edge of the least possible weight that connects any two 
trees in the forest. It is a greedy algorithm in graph theory 
as it finds a minimum spanning tree for a connected weighted 
graph adding increasing cost arcs at each step. This means it 
finds a subset of the edges that forms a tree that includes every
vertex, where the total weight of all the edges in the tree is 
minimized. If the graph is not connected, then it finds a 
minimum spanning forest (a minimum spanning tree for each 
connected component).

![Kruskal Algorithm](https://upload.wikimedia.org/wikipedia/commons/5/5c/MST_kruskal_en.gif)

![Kruskal Demo](https://upload.wikimedia.org/wikipedia/commons/b/bb/KruskalDemo.gif)

A demo for Kruskal's algorithm based on Euclidean distance.

## Minimum Spanning Tree

A **minimum spanning tree** (MST) or minimum weight spanning tree 
is a subset of the edges of a connected, edge-weighted 
(un)directed graph that connects all the vertices together, 
without any cycles and with the minimum possible total edge 
weight. That is, it is a spanning tree whose sum of edge weights 
is as small as possible. More generally, any edge-weighted 
undirected graph (not necessarily connected) has a minimum 
spanning forest, which is a union of the minimum spanning 
trees for its connected components.

![Minimum Spanning Tree](https://upload.wikimedia.org/wikipedia/commons/d/d2/Minimum_spanning_tree.svg)

A planar graph and its minimum spanning tree. Each edge is 
labeled with its weight, which here is roughly proportional 
to its length.

![Minimum Spanning Tree](https://upload.wikimedia.org/wikipedia/commons/c/c9/Multiple_minimum_spanning_trees.svg)

This figure shows there may be more than one minimum spanning 
tree in a graph. In the figure, the two trees below the graph 
are two possibilities of minimum spanning tree of the given graph.

## References

- [Minimum Spanning Tree on Wikipedia](https://en.wikipedia.org/wiki/Minimum_spanning_tree)
- [Kruskal's Algorithm on Wikipedia](https://en.wikipedia.org/wiki/Kruskal%27s_algorithm)
- [Kruskal's Algorithm on YouTube by Tushar Roy](https://www.youtube.com/watch?v=fAuF0EuZVCk&list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8)
- [Kruskal's Algorithm on YouTube by Michael Sambol](https://www.youtube.com/watch?v=71UQH7Pr9kU&list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8)

# 克鲁斯克尔演算法

Kruskal算法是一种用来寻找最小生成树的算法，由Joseph Kruskal在1956年发表。用来解决同样问题的还有Prim算法和Boruvka算法等。三种算法都是贪婪算法的应用。和Boruvka算法不同的地方是，Kruskal算法在图中存在相同权值的边时也有效。
Kruskal算法每次选择n- 1条边，所使用的贪婪准则是：从剩下的边中选择一条不会产生环路的具有最小耗费的边加入已选择的边的集合中。注意到所选取的边若产生环路则不可能形成一棵生成树。Kruskal算法分e 步，其中e 是网络中边的数目。按耗费递增的顺序来考虑这e 条边，每次考虑一条边。当考虑某条边时，若将其加入到已选边的集合中会出现环路，则将其抛弃，否则，将它选入。