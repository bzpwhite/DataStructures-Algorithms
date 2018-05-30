# DataStructures-Algorithms
dataStructures&amp;algorithms introduction

## 数据结构

数据结构是在计算机中组织和存储数据的一种特殊方式，它可以高效地访问和修改数据。更确切地说，数据结构是数据值的集合，它们之间的关系、函数或操作可以应用于数据。

* [链表](./linked-list)
* [队列](./queue)
* [栈](./stack)
* [哈希表](./hash-table)
* [堆](./heap)
* [优先队列](./priority-queue)
* [字典树](./trie)
* [树](./tree)
    * [二分查找](./binary-search-tree)
    * [AVL 树](./avl-tree)
    * 红黑树
    * 后缀树
    * 线段树 或 间隔树
    * 二叉索引树
* [图](./graph) (有向图与无向图)
* [并查集](./disjoint-set)

## 算法

算法是如何解决一类问题的明确规范。 算法是一组精确定义操作序列的规则。

### 算法主题

* **数学**
  * [阶乘](./factorial)
  * [斐波那契数](./fibonacci)
  * [素数检测](./primality-test) (排除法)
  * [欧几里得算法](./euclidean-algorithm) - 计算最大公约数（GCD）
  * [最小公倍数](./least-common-multiple) (LCM)
  * [整数拆分](./integer-partition)
* **集合**
  * [笛卡尔积](./cartesian-product) - 多集合结果
  * [幂集](./power-set) - 该集合的所有子集
  * [排列](./permutations) (有/无重复)
  * [组合](./combinations) (有/无重复)
  * [洗牌算法](./fisher-yates) - 随机置换有限序列
  * [最长公共子序列](./longest-common-subsequnce) (LCS)
  * [最长递增子序列](./longest-increasing-subsequence)
  * [Shortest Common Supersequence](./shortest-common-supersequence) (SCS)
  * [背包问题](./knapsack-problem) - "0/1" and "Unbound" ones
  * [最大子数列问题](./maximum-subarray) - BF算法 与 动态编程
* **字符串**
  * [莱温斯坦距离](./levenshtein-distance) - 两个序列之间的最小编辑距离
  * [汉明距离](./hamming-distance) - 符号不同的位置数
  * [克努斯-莫里斯-普拉特算法](./knuth-morris-pratt) - 子串搜索
  * [字符串快速查找](./rabin-karp) - 子串搜索
  * [最长公共子串](./longest-common-substring)
* **搜索**
  * [二分查找](./binary-search)
* **排序**
  * [冒泡排序](./bubble-sort)
  * [选择排序](./selection-sort)
  * [插入排序](./insertion-sort)
  * [堆排序](./heap-sort)
  * [归并排序](./merge-sort)
  * [快速排序](./quick-sort)
  * [希尔排序](./shell-sort)
* **树**  
  * [深度优先搜索](./depth-first-search) (DFS)
  * [广度优先搜索](./breadth-first-search) (BFS)
* **图**
  * [深度优先搜索](./depth-first-search) (DFS)
  * [广度优先搜索](./breadth-first-search) (BFS)
  * [戴克斯特拉算法m](./dijkstra) - 找到所有图顶点的最短路径
  * [贝尔曼-福特算法](./bellman-ford) - 找到所有图顶点的最短路径
  * [判圈算法](./detect-cycle) - 对于有向图和无向图（基于DFS和不相交集的版本）
  * [普林演算法](./prim) - 寻找加权无向图的最小生成树（MST）
  * [克鲁斯克尔演算法](./kruskal) - 寻找加权无向图的最小生成树（MST）
  * [拓撲排序](./topological-sorting) - DFS 方法
  * [关节点](./articulation-points) - Tarjan算法（基于DFS）
  * [桥](./bridges) - 基于DFS的算法
  * [欧拉路径与一笔画问题](./eulerian-path) - Fleury的算法 - 一次访问每个边缘
  * [哈密顿图](./hamiltonian-cycle) - 恰好访问每个顶点一次
  * [强连通分量](./strongly-connected-components) - Kosaraju算法
  * [旅行推销员问题](./travelling-salesman) - 尽可能以最短的路线访问每个城市并返回原始城市
* **未分类**  
  * [汉诺塔](./hanoi-tower)
  * [八皇后问题](./n-queens)
  * [骑士巡逻](./knight-tour)

### 算法范式

算法范式是基于类的设计的通用方法或方法的算法。 这是一个比算法概念更高的抽象，就像一个
算法是比计算机程序更高的抽象。

* **BF算法** - 查找所有可能性并选择最佳解决方案
  * [最大子数列](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/maximum-subarray)
  * [旅行推销员问题](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/travelling-salesman) - 尽可能以最短的路线访问每个城市并返回原始城市

* **贪心法** - 在当前选择最佳选项，不考虑以后情况
  * [背包问题](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/knapsack-problem)
  * [戴克斯特拉算法](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/dijkstra) - 找到所有图顶点的最短路径
  * [普里姆算法](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/prim) - 寻找加权无向图的最小生成树（MST）
  * [克鲁斯卡尔算法](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/kruskal) - 寻找加权无向图的最小生成树（MST）
* **分治法** - 将问题分成较小的部分，然后解决这些部分
  * [二分查找](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/search/binary-search)
  * [汉诺塔](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/uncategorized/hanoi-tower)
  * [欧几里得算法](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/math/euclidean-algorithm) - 计算最大公约数（GCD）
  * [排列](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/permutations) (有/无重复)
  * [组合](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/combinations) (有/无重复)
  * [归并排序](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sorting/merge-sort)
  * [Quicksort](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sorting/quick-sort)
  * [树深度优先搜索](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/tree/depth-first-search) (DFS)
  * [图深度优先搜索](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/depth-first-search) (DFS)
* **动态编程** - 使用以前找到的子解决方案构建解决方案
  * [斐波那契数](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/math/fibonacci)
  * [莱温斯坦距离](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/string/levenshtein-distance) - 两个序列之间的最小编辑距离
  * [最长公共子序列](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/longest-common-subsequnce) (LCS)
  * [最长公共子串](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/string/longest-common-substring)
  * [最长递增子序列](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/longest-increasing-subsequence)
  * [最短公共子序列](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/shortest-common-supersequence)
  * [0-1背包问题](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/knapsack-problem)
  * [整数拆分](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/math/integer-partition)
  * [最大子数列](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sets/maximum-subarray)
  * [贝尔曼-福特算法](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/bellman-ford) - 找到所有图顶点的最短路径
* **回溯法** - 类似于 BF算法 试图产生所有可能的解决方案，但每次生成解决方案测试如果它满足所有条件，那么只有继续生成后续解决方案。 否则回溯并继续寻找不同路径的解决方案。
  * [哈密顿图](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/graph/hamiltonian-cycle) - 恰好访问每个顶点一次
  * [八皇后问题](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/uncategorized/n-queens)
  * [骑士巡逻](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/uncategorized/knight-tour)
* **B & B**
