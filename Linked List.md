# Linked List

In computer science, a linked list is a linear collection 
of data elements, in which linear order is not given by 
their physical placement in memory. Instead, each 
element points to the next. It is a data structure 
consisting of a group of nodes which together represent 
a sequence. Under the simplest form, each node is 
composed of data and a reference (in other words, 
a link) to the next node in the sequence. This structure
allows for efficient insertion or removal of elements 
from any position in the sequence during iteration. 
More complex variants add additional links, allowing 
efficient insertion or removal from arbitrary element 
references. A drawback of linked lists is that access 
time is linear (and difficult to pipeline). Faster 
access, such as random access, is not feasible. Arrays 
have better cache locality as compared to linked lists.

![Linked List](https://upload.wikimedia.org/wikipedia/commons/6/6d/Singly-linked-list.svg)

## References

- [Wikipedia](https://en.wikipedia.org/wiki/Linked_list)
- [YouTube](https://www.youtube.com/watch?v=njTh_OwMljA&index=2&t=1s&list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8)


# 链表

链表是一种物理存储单元上非连续、非顺序的存储结构，数据元素的逻辑顺序是通过链表中的指针链接次序实现的。链表由一系列结点（链表中每一个元素称为结点）组成，结点可以在运行时动态生成。每个结点包括两个部分：一个是存储数据元素的数据域，另一个是存储下一个结点地址的指针域。 相比于线性表顺序结构，操作复杂。由于不必须按顺序存储，链表在插入的时候可以达到O(1)的复杂度，比另一种线性表顺序表快得多，但是查找一个节点或者访问特定编号的节点则需要O(n)的时间，而线性表和顺序表相应的时间复杂度分别是O(logn)和O(1)。