# Tree

* [Binary Search Tree](https://github.com/trekhleb/javascript-algorithms/tree/master/src/data-structures/tree/binary-search-tree)
* [AVL Tree](https://github.com/trekhleb/javascript-algorithms/tree/master/src/data-structures/tree/avl-tree)

In computer science, a tree is a widely used abstract data 
type (ADT) — or data structure implementing this ADT—that 
simulates a hierarchical tree structure, with a root value 
and subtrees of children with a parent node, represented as 
a set of linked nodes.

A tree data structure can be defined recursively (locally) 
as a collection of nodes (starting at a root node), where 
each node is a data structure consisting of a value, 
together with a list of references to nodes (the "children"), 
with the constraints that no reference is duplicated, and none 
points to the root.

A simple unordered tree; in this diagram, the node labeled 7 has
two children, labeled 2 and 6, and one parent, labeled 2. The
root node, at the top, has no parent.

![Tree](https://upload.wikimedia.org/wikipedia/commons/f/f7/Binary_tree.svg)

## References

- [Wikipedia](https://en.wikipedia.org/wiki/Tree_(data_structure))
- [YouTube](https://www.youtube.com/watch?v=oSWTXtMglKE&list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8&index=8)

# 树

树状图是一种数据结构，它是由n（n>=1）个有限节点组成一个具有层次关系的集合。把它叫做“树”是因为它看起来像一棵倒挂的树，也就是说它是根朝上，而叶朝下的。它具有以下的特点：
每个节点有零个或多个子节点；没有父节点的节点称为根节点；每一个非根节点有且只有一个父节点；除了根节点外，每个子节点可以分为多个不相交的子树