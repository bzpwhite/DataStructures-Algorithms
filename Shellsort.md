# Shellsort

Shellsort, also known as Shell sort or Shell's method, 
is an in-place comparison sort. It can be seen as either a 
generalization of sorting by exchange (bubble sort) or sorting 
by insertion (insertion sort). The method starts by sorting 
pairs of elements far apart from each other, then progressively 
reducing the gap between elements to be compared. Starting 
with far apart elements, it can move some out-of-place 
elements into position faster than a simple nearest neighbor 
exchange

![Shellsort](https://upload.wikimedia.org/wikipedia/commons/d/d8/Sorting_shellsort_anim.gif)

## How Shell Sort Works

For our example and ease of understanding, we take the interval 
of `4`. Make a virtual sub-list of all values located at the 
interval of 4 positions. Here these values are 
`{35, 14}`, `{33, 19}`, `{42, 27}` and `{10, 44}`

![Shellsort](https://www.tutorialspoint.com/data_structures_algorithms/images/shell_sort_gap_4.jpg)

We compare values in each sub-list and swap them (if necessary)
in the original array. After this step, the new array should
look like this

![Shellsort](https://www.tutorialspoint.com/data_structures_algorithms/images/shell_sort_step_1.jpg)

Then, we take interval of 2 and this gap generates two sub-lists 
- `{14, 27, 35, 42}`, `{19, 10, 33, 44}`

![Shellsort](https://www.tutorialspoint.com/data_structures_algorithms/images/shell_sort_gap_2.jpg)

We compare and swap the values, if required, in the original array.
After this step, the array should look like this

![Shellsort](https://www.tutorialspoint.com/data_structures_algorithms/images/shell_sort_step_2.jpg)

Finally, we sort the rest of the array using interval of value 1. 
Shell sort uses insertion sort to sort the array.

![Shellsort](https://www.tutorialspoint.com/data_structures_algorithms/images/shell_sort.jpg)

## References

* [Tutorials Point](https://www.tutorialspoint.com/data_structures_algorithms/shell_sort_algorithm.htm)
* [Wikipedia](https://en.wikipedia.org/wiki/Shellsort)

# 希尔排序

希尔排序(Shell's Sort)是插入排序的一种又称“缩小增量排序”（Diminishing Increment Sort），是直接插入排序算法的一种更高效的改进版本。希尔排序是非稳定排序算法。该方法因D.L.Shell于1959年提出而得名。
希尔排序是把记录按下标的一定增量分组，对每组使用直接插入排序算法排序；随着增量逐渐减少，每组包含的关键词越来越多，当增量减至1时，整个文件恰被分成一组，算法便终止。