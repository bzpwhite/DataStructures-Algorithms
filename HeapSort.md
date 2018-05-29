# Heap Sort

Heapsort is a comparison-based sorting algorithm.
Heapsort can be thought of as an improved selection
sort: like that algorithm, it divides its input into
a sorted and an unsorted region, and it iteratively
shrinks the unsorted region by extracting the largest
element and moving that to the sorted region. The 
improvement consists of the use of a heap data structure
rather than a linear-time search to find the maximum.

![Algorithm Visualization](https://upload.wikimedia.org/wikipedia/commons/1/1b/Sorting_heapsort_anim.gif)

![Algorithm Visualization](https://upload.wikimedia.org/wikipedia/commons/4/4d/Heapsort-example.gif)

## References

[Wikipedia](https://en.wikipedia.org/wiki/Heapsort)

# 堆排序

堆排序(Heapsort)是指利用堆积树（堆）这种数据结构所设计的一种排序算法，它是选择排序的一种。可以利用数组的特点快速定位指定索引的元素。堆分为大根堆和小根堆，是完全二叉树。大根堆的要求是每个节点的值都不大于其父节点的值，即A[PARENT[i]] >= A[i]。在数组的非降序排序中，需要使用的就是大根堆，因为根据大根堆的要求可知，最大的值一定在堆顶。