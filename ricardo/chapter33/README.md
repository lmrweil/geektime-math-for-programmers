# 线性代数
### 向量和向量空间
- 向量矢量。它代表一组数字，并且这些数字是有序排列的。我们用数据结构的视角来看，向量可以用数组或者链表来表达。
- 向量和标量最大的区别在于，向量除了拥有数值的大小，还拥有方向。向量或者矢量中的“向”和“矢”这两个字，都表明它们是有方向的。
- 特征向量----向量的每个元素就代表一维特征，而元素的值代表了相应特征的值

### 向量的运算
##### 向量和向量之间的加法或乘法应该如何进行呢？我们需要先定义向量空间。向量空间理论上的定义比较繁琐，不过二维或者三维的坐标空间可以很好地帮助你来理解。这些空间主要有几个特性：
- 空间由无穷多个的位置点组成；
- 这些点之间存在相对的关系；
- 可以在空间中定义任意两点之间的长度，以及任意两个向量之间的角度；
- 这个空间的点可以进行移动。

### 矩阵的运算
- 矩阵由多个长度相等的向量组成，其中的每列或者每行就是一个向量。因此，我们把向量延伸一下就能得到矩阵（Matrix）。
- 两个矩阵中对应元素进行相乘，这种操作也是存在的，我们称它为元素对应乘积
- 转置（Transposition）是指矩阵内的元素行索引和纵索引互换，例如 Xij​ 就变为 Xji​，
- 元素对应乘积 两个矩阵中对应元素进行相乘

### 总结
- 标量和向量的区别，标量只是单独的一个数，而向量是一组数。矩阵是向量的扩展，就是一个二维数组。我们可以使用哈希表的链地址法表示稀疏矩阵。
- 标量和向量或矩阵的加法、乘法比较简单，就是把这个标量和向量或矩阵中所有的元素轮流进行相加或相乘。向量之间的加法和矩阵之间的加法，是把两者对应的元素相加。向量之间的相乘分为叉乘和点乘，我在专栏里默认向量乘法为点乘。而矩阵的乘法默认为左矩阵的行向量和右矩阵的列向量两两点乘。