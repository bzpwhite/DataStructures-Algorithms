# Priority Queue

In computer science, a priority queue is an abstract data type 
which is like a regular queue or stack data structure, but where 
additionally each element has a "priority" associated with it. 
In a priority queue, an element with high priority is served before 
an element with low priority. If two elements have the same 
priority, they are served according to their order in the queue.

While priority queues are often implemented with heaps, they are 
conceptually distinct from heaps. A priority queue is an abstract 
concept like "a list" or "a map"; just as a list can be implemented
with a linked list or an array, a priority queue can be implemented
with a heap or a variety of other methods such as an unordered 
array.

## References

- [Wikipedia](https://en.wikipedia.org/wiki/Priority_queue)
- [YouTube](https://www.youtube.com/watch?v=wptevk0bshY&list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8&index=6)

# 优先队列

普通的队列是一种先进先出的数据结构，元素在队列尾追加，而从队列头删除。在优先队列中，元素被赋予优先级。当访问元素时，具有最高优先级的元素最先删除。优先队列具有最高级先出 （first in, largest out）的行为特征。通常采用堆数据结构来实现