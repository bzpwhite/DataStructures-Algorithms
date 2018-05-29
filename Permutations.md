# Permutations

When the order doesn't matter, it is a **Combination**.

When the order **does** matter it is a **Permutation**.

**"The combination to the safe is 472"**. We do care about the order. `724` won't work, nor will `247`. 
It has to be exactly `4-7-2`.

## Permutations without repetitions

A permutation, also called an “arrangement number” or “order”, is a rearrangement of 
the elements of an ordered list `S` into a one-to-one correspondence with `S` itself. 

Below are the permutations of string `ABC`.

`ABC ACB BAC BCA CBA CAB`

Or for example the first three people in a running race: you can't be first and second.

**Number of combinations**

```
n * (n-1) * (n -2) * ... * 1 = n!
```

## Permutations with repetitions

When repetition is allowed we have permutations with repetitions.
For example the the lock below: it could be `333`.

![Permutation Lock](https://www.mathsisfun.com/combinatorics/images/combination-lock.jpg)

**Number of combinations**

```
n * n * n ... (r times) = n^r
```

## References

[Math Is Fun](https://www.mathsisfun.com/combinatorics/combinations-permutations.html)

# 排列

排列，一般地，从n个不同元素中取出m（m≤n）个元素，按照一定的顺序排成一列，叫做从n个元素中取出m个元素的一个排列(permutation)。特别地，当m=n时，这个排列被称作全排列(all permutation)。