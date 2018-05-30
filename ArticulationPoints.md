# Articulation Points (or Cut Vertices)

A vertex in an undirected connected graph is an articulation point
(or cut vertex) if removing it (and edges through it) disconnects 
the graph. Articulation points represent vulnerabilities in a 
connected network – single points whose failure would split the 
network into 2 or more disconnected components. They are useful for 
designing reliable networks.

For a disconnected undirected graph, an articulation point is a 
vertex removing which increases number of connected components.

![Articulation Points](https://www.geeksforgeeks.org/wp-content/uploads/ArticulationPoints.png)

![Articulation Points](https://www.geeksforgeeks.org/wp-content/uploads/ArticulationPoints1.png)

![Articulation Points](https://www.geeksforgeeks.org/wp-content/uploads/ArticulationPoints21.png)

## References

- [GeeksForGeeks](https://www.geeksforgeeks.org/articulation-points-or-cut-vertices-in-a-graph/)
- [YouTube](https://www.youtube.com/watch?v=2kREIkF9UAs&list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8)

# 关节点

在某图中，若删除顶点V以及V相关的边后，图的一个连通分量分割为两个或两个以上的连通分量，则称顶点V为该图的一个关节点。一个没有关节点的连通图称为重连通图。
在重连通图中，任意一对顶点之间至少存在两条路径，则再删去某个顶点即相关各边后也不破坏图的连通性。若在图的连通图上删去k个节点才能破坏图的连通性，则称K为此图的连通度。
他们常常在通信网络的图或航空网中应用，K越大，系统越稳定，反之，战争中若要摧毁敌方的运输线，只须破坏其运输网中的关节点即可。