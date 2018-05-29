# Hamming Distance

the Hamming distance between two strings of equal length is the 
number of positions at which the corresponding symbols are 
different. In other words, it measures the minimum number of
substitutions required to change one string into the other, or 
the minimum number of errors that could have transformed one 
string into the other. In a more general context, the Hamming 
distance is one of several string metrics for measuring the 
edit distance between two sequences.

## Examples

The Hamming distance between:

- "ka**rol**in" and "ka**thr**in" is **3**.
- "k**a**r**ol**in" and "k**e**r**st**in" is **3**.
- 10**1**1**1**01 and 10**0**1**0**01 is **2**.
- 2**17**3**8**96 and 2**23**3**7**96 is **3**.

## References

[Wikipedia](https://en.wikipedia.org/wiki/Hamming_distance)

# 汉明距离

汉明距离是使用在数据传输差错控制编码里面的，汉明距离是一个概念，它表示两个（相同长度）字对应位不同的数量，我们以d（x,y）表示两个字x,y之间的汉明距离。对两个字符串进行异或运算，并统计结果为1的个数，那么这个数就是汉明距离。