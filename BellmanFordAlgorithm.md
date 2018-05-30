# Bellman–Ford Algorithm

The Bellman–Ford algorithm is an algorithm that computes shortest 
paths from a single source vertex to all of the other vertices 
in a weighted digraph. It is slower than Dijkstra's algorithm 
for the same problem, but more versatile, as it is capable of 
handling graphs in which some of the edge weights are negative 
numbers.

![Bellman-Ford](https://upload.wikimedia.org/wikipedia/commons/2/2e/Shortest_path_Dijkstra_vs_BellmanFord.gif)

## Complexity

Worst-case performance `O(|V||E|)`
Best-case performance	`O(|E|)`
Worst-case space complexity `O(|V|)`

## References

- [Wikipedia](https://en.wikipedia.org/wiki/Bellman%E2%80%93Ford_algorithm)
- [On YouTube by Michael Sambol](https://www.youtube.com/watch?v=obWXjtg0L64&list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8)

# 贝尔曼-福特算法

贝尔曼-福特算法（Bellman-Ford）是由理查德·贝尔曼（Richard Bellman） 和 莱斯特·福特 创立的，求解单源最短路径问题的一种算法。有时候这种算法也被称为 Moore-Bellman-Ford 算法，因为 Edward F. Moore 也为这个算法的发展做出了贡献。它的原理是对图进行V-1次松弛操作，得到所有可能的最短路径。其优于迪科斯彻算法的方面是边的权值可以为负数、实现简单，缺点是时间复杂度过高，高达O(VE)。但算法可以进行若干种优化，提高了效率。