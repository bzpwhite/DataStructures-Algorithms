# Disjoint Set

**Disjoint-set** data structure (also called a union–find data structure or merge–find set) is a data 
structure that tracks a set of elements partitioned into a number of disjoint (non-overlapping) subsets. 
It provides near-constant-time operations (bounded by the inverse Ackermann function) to *add new sets*, 
to *merge existing sets*, and to *determine whether elements are in the same set*. 
In addition to many other uses (see the Applications section), disjoint-sets play a key role in Kruskal's algorithm for finding the minimum spanning tree of a graph.

![disjoint set](https://upload.wikimedia.org/wikipedia/commons/6/67/Dsu_disjoint_sets_init.svg)

*MakeSet* creates 8 singletons.

![disjoint set](https://upload.wikimedia.org/wikipedia/commons/a/ac/Dsu_disjoint_sets_final.svg)

After some operations of *Union*, some sets are grouped together.

## References

- [Wikipedia](https://en.wikipedia.org/wiki/Disjoint-set_data_structure)
- [By Abdul Bari on YouTube](https://www.youtube.com/watch?v=wU6udHRIkcc&index=14&t=0s&list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8)

# 并查集

并查集，在一些有N个元素的集合应用问题中，我们通常是在开始时让每个元素构成一个单元素的集合，然后按一定顺序将属于同一组的元素所在的集合合并，其间要反复查找一个元素在哪个集合中。这一类问题近几年来反复出现在信息学的国际国内赛题中，其特点是看似并不复杂，但数据量极大，若用正常的数据结构来描述的话，往往在空间上过大，计算机无法承受；即使在空间上勉强通过，运行的时间复杂度也极高，根本就不可能在比赛规定的运行时间（1～3秒）内计算出试题需要的结果，只能用并查集来描述。
并查集是一种树型的数据结构，用于处理一些不相交集合（Disjoint Sets）的合并及查询问题。常常在使用中以森林来表示