# 18 | 总结课：数据结构、编程语句和基础算法体现了哪些数学思想？

## 数据结构

数组只对稠密的数列更有效，如果数列非常稀疏，那么很多数组的元素就是无效值，浪费了存储空间。而且插入和删除也比较麻烦，需要数据的批量移动。

链表适合稀疏的数列，特点是不能通过下标来直接访问数据，而是必须按照存储的结构逐个读取。无法支持快速随机访问，进行读写操作时更加耗时。

链表也可以是多维的，链表结构中，点与点的链接，分别体现了图论中的顶点和边。

基于数组和链表，可以构建更复杂的数据结构，比如：哈希表、队列和栈。

更复杂的是图论中的各种模型，例如各种二叉树、多叉树、有向图和无向图等。

## 编程语句

布尔运算：if 和 SQL 中的 Select。

集合操作：SQL 中的 inner join、outer join。

循环迭代和多层嵌套进行排列组合遍历。

函数的递归调用，也可以提现排列组合的思想。

## 基础算法

分治思想，MapReduce 的数据切分，求余的哈希函数等。

字符串的编辑距离。

分治、动态规划和回溯，用回溯来解决八皇后等问题，体现了递归和排列的思想，对搜索空间做了一些优化，提前排除了不可能的情况，提升了算法整体的效率。

还有算法复杂度。

## 总结

不同的数据结构，都是在编程中运用数学思维的产物。每种数据结构都有自身的特点，有利于我们更方便地实现某种特定的数学模型。

在平时学习编程的时候，你可以多从数学的角度出发，思考其背后的数学模型。这样不仅有利于你对现有知识的融会贯通，还可以帮助你优化数据结构和算法。
