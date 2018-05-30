# Hamiltonian Path

**Hamiltonian path** (or **traceable path**) is a path in an 
undirected or directed graph that visits each vertex exactly once. 
A **Hamiltonian cycle** (or **Hamiltonian circuit**) is a 
Hamiltonian path that is a cycle. Determining whether such paths 
and cycles exist in graphs is the **Hamiltonian path problem**.

![Hamiltonian cycle](https://upload.wikimedia.org/wikipedia/commons/6/6c/Hamiltonian_path_3d.svg)

One possible Hamiltonian cycle through every vertex of a 
dodecahedron is shown in red – like all platonic solids, the 
dodecahedron is Hamiltonian.

## Naive Algorithm

Generate all possible configurations of vertices and print a 
configuration that satisfies the given constraints. There 
will be `n!` (n factorial) configurations.

```
while there are untried configurations
{
   generate the next configuration
   if ( there are edges between two consecutive vertices of this
      configuration and there is an edge from the last vertex to 
      the first ).
   {
      print this configuration;
      break;
   }
}
```

## Backtracking Algorithm

Create an empty path array and add vertex `0` to it. Add other 
vertices, starting from the vertex `1`. Before adding a vertex, 
check for whether it is adjacent to the previously added vertex 
and not already added. If we find such a vertex, we add the 
vertex as part of the solution. If we do not find a vertex 
then we return false.

## References

- [Hamiltonian path on Wikipedia](https://en.wikipedia.org/wiki/Hamiltonian_path)
- [Hamiltonian path on YouTube](https://www.youtube.com/watch?v=dQr4wZCiJJ4&list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8)
- [Hamiltonian cycle on GeeksForGeeks](https://www.geeksforgeeks.org/backtracking-set-7-hamiltonian-cycle/)

# 哈密顿图

哈密顿通路（回路）与哈密顿图 （Hamilton图） 通过图G的每个结点一次，且仅一次的通路（回路），就是哈密顿通路（回路）。存在哈密顿回路的图就是哈密顿图。
美国图论数学家奥勒在1960年给出了一个图是哈密尔顿图的充分条件：对于顶点个数大于2的图，如果图中任意两点度的和大于或等于顶点总数，那这个图一定是哈密顿图。闭合的哈密顿路径称作哈密顿圈，含有图中所有顶点的路径称作哈密顿路径。