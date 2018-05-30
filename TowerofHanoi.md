# Tower of Hanoi

The Tower of Hanoi (also called the Tower of Brahma or Lucas'
Tower and sometimes pluralized) is a mathematical game or puzzle. 
It consists of three rods and a number of disks of different sizes,
which can slide onto any rod. The puzzle starts with the disks in 
a neat stack in ascending order of size on one rod, the smallest 
at the top, thus making a conical shape.

The objective of the puzzle is to move the entire stack to another 
rod, obeying the following simple rules:

- Only one disk can be moved at a time.
- Each move consists of taking the upper disk from one of the 
stacks and placing it on top of another stack or on an empty rod.
- No disk may be placed on top of a smaller disk.

![Hanoi Tower](https://upload.wikimedia.org/wikipedia/commons/8/8d/Iterative_algorithm_solving_a_6_disks_Tower_of_Hanoi.gif)

Animation of an iterative algorithm solving 6-disk problem

With `3` disks, the puzzle can be solved in `7` moves. The minimal 
number of moves required to solve a Tower of Hanoi puzzle 
is `2^n − 1`, where `n` is the number of disks.

## References

- [Wikipedia](https://en.wikipedia.org/wiki/Tower_of_Hanoi)
- [HackerEarth](https://www.hackerearth.com/blog/algorithms/tower-hanoi-recursion-game-algorithm-explained/)

# 汉诺塔

汉诺塔：汉诺塔（又称河内塔）问题是源于印度一个古老传说的益智玩具。大梵天创造世界的时候做了三根金刚石柱子，在一根柱子上从下往上按照大小顺序摞着64片黄金圆盘。大梵天命令婆罗门把圆盘从下面开始按大小顺序重新摆放在另一根柱子上。并且规定，在小圆盘上不能放大圆盘，在三根柱子之间一次只能移动一个圆盘。