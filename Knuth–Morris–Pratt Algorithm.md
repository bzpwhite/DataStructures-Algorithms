# Knuth–Morris–Pratt Algorithm

The Knuth–Morris–Pratt string searching algorithm (or 
KMP algorithm) searches for occurrences of a "word" `W` 
within a main "text string" `T` by employing the 
observation that when a mismatch occurs, the word itself 
embodies sufficient information to determine where the 
next match could begin, thus bypassing re-examination 
of previously matched characters.

## Complexity

- **Time:** `O(|W| + |T|)` (much faster comparing to trivial `O(|W| * |T|)`)
- **Space:** `O(|W|)`

## References

- [Wikipedia](https://en.wikipedia.org/wiki/Knuth%E2%80%93Morris%E2%80%93Pratt_algorithm)
- [YouTube](https://www.youtube.com/watch?v=GTJr8OvyEVQ&list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8)

# 克努斯-莫里斯-普拉特算法

KMP算法是一种改进的字符串匹配算法，由D.E.Knuth，J.H.Morris和V.R.Pratt同时发现，因此人们称它为克努特——莫里斯——普拉特操作（简称KMP算法）。KMP算法的关键是利用匹配失败后的信息，尽量减少模式串与主串的匹配次数以达到快速匹配的目的。具体实现就是实现一个next()函数，函数本身包含了模式串的局部匹配信息。时间复杂度O(m+n)。