# Strongly Connected Component

A directed graph is called **strongly connected** if there is a path 
in each direction between each pair of vertices of the graph. 
In a directed graph G that may not itself be strongly connected, 
a pair of vertices `u` and `v` are said to be strongly connected 
to each other if there is a path in each direction between them.

![Strongly Connected](https://upload.wikimedia.org/wikipedia/commons/5/5c/Scc.png)

Graph with strongly connected components marked

## References

- [Wikipedia](https://en.wikipedia.org/wiki/Strongly_connected_component)
- [YouTube](https://www.youtube.com/watch?v=RpgcYiky7uw&list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8)

# 强连通分量

有向图强连通分量：在有向图G中，如果两个顶点vi,vj间（vi>vj）有一条从vi到vj的有向路径，同时还有一条从vj到vi的有向路径，则称两个顶点强连通(strongly connected)。如果有向图G的每两个顶点都强连通，称G是一个强连通图。有向图的极大强连通子图，称为强连通分量(strongly connected components)。