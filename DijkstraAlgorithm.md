# Dijkstra's Algorithm

Dijkstra's algorithm is an algorithm for finding the shortest 
paths between nodes in a graph, which may represent, for example, 
road networks. 

The algorithm exists in many variants; Dijkstra's original variant 
found the shortest path between two nodes, but a more common 
variant fixes a single node as the "source" node and finds 
shortest paths from the source to all other nodes in the graph, 
producing a shortest-path tree.

![Dijkstra](https://upload.wikimedia.org/wikipedia/commons/5/57/Dijkstra_Animation.gif)

Dijkstra's algorithm to find the shortest path between `a` and `b`.
It picks the unvisited vertex with the lowest distance, 
calculates the distance through it to each unvisited neighbor, 
and updates the neighbor's distance if smaller. Mark visited
(set to red) when done with neighbors.

## References

- [Wikipedia](https://en.wikipedia.org/wiki/Dijkstra%27s_algorithm)
- [On YouTube by Nathaniel Fan](https://www.youtube.com/watch?v=gdmfOwyQlcI&list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8)
- [On YouTube by Tushar Roy](https://www.youtube.com/watch?v=lAXZGERcDf4&list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8)

# 戴克斯特拉算法

戴克斯特拉算法（英语：Dijkstra's algorithm）由荷兰计算机科学家艾兹赫尔·戴克斯特拉在1956年提出。迪科斯特拉算法使用了广度优先搜索解决赋权有向图的单源最短路径问题。该算法存在很多变体；戴克斯特拉的原始版本找到两个顶点之间的最短路径，但是更常见的变体固定了一个顶点作为源节点然后找到该顶点到图中所有其它节点的最短路径，产生一个最短路径树。该算法常用于路由算法或者作为其他图算法的一个子模块。举例来说，如果图中的顶点表示城市，而边上的权重表示城市间开车行经的距离，该算法可以用来找到两个城市之间的最短路径。