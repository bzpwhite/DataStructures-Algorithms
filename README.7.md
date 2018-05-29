# Trie

In computer science, a trie, also called digital tree and sometimes 
radix tree or prefix tree (as they can be searched by prefixes), 
is a kind of search tree—an ordered tree data structure that is 
used to store a dynamic set or associative array where the keys 
are usually strings. Unlike a binary search tree, no node in the 
tree stores the key associated with that node; instead, its 
position in the tree defines the key with which it is associated.
All the descendants of a node have a common prefix of the string
associated with that node, and the root is associated with the 
empty string. Values are not necessarily associated with every 
node. Rather, values tend only to be associated with leaves, 
and with some inner nodes that correspond to keys of interest. 
For the space-optimized presentation of prefix tree, see compact 
prefix tree.

![Trie](https://upload.wikimedia.org/wikipedia/commons/b/be/Trie_example.svg)

## References

- [Wikipedia](https://en.wikipedia.org/wiki/Trie)
- [YouTube](https://www.youtube.com/watch?v=zIjfhVPRZCg&list=PLLXdhg_r2hKA7DPDsunoDZ-Z769jWn4R8&index=7&t=0s)

# 字典树

又称单词查找树，Trie树，是一种树形结构，是一种哈希树的变种。典型应用是用于统计，排序和保存大量的字符串（但不仅限于字符串），所以经常被搜索引擎系统用于文本词频统计。它的优点是：利用字符串的公共前缀来减少查询时间，最大限度地减少无谓的字符串比较，查询效率比哈希树高。