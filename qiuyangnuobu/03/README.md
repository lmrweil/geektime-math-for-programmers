## 迭代法：不用编程语言的自带函数，你会如何计算平方根？

### 迭代法（Iterative Method）

迭代法，简单来说，其实就是不断地用旧的变量值，递推计算新的变量值。
古印度国王舍罕酷重赏国际象棋的发明人宰相西萨·班·达依尔的故事

    (function getNumberOfWheat(grid) {
        let num = 1
        let sum = 1
        console.log(`第1个格子:${num}粒米,当前总共:${sum}`)
        for (let i = 1; i < grid; i++) {
            num *= 2
            sum += num
            console.log(`第${i+1}个格子:${num}粒米,当前总共:${sum}`)
        }
        console.log(`最终：${sum}粒米`)
    })(55)
    // 最终：36028797018963970粒米
    // js 55之前还准确超过55格子已经不精确了

### 迭代法的基本步骤

- 确定用于迭代的变量
- 简历迭代变量之间的递推关系
- 控制迭代过程

### 迭代法的应用

- 求数值的精确或者近似解
典型的方法包括二分法（Bisection method）和牛顿迭代法（Newton’s method）
- 在一定范围内查找目标值
典型的方法包括二分查找
- 机器学习算法中的迭代
相关的算法或者模型有很多，比如 K- 均值算法（K-means clustering）、PageRank 的马尔科夫链（Markov chain）、梯度下降法（Gradient descent）等等。迭代法之所以在机器学习中有广泛的应用，是因为很多时候机器学习的过程，就是根据已知的数据和一定的假设，求一个局部最优解。而迭代法可以帮助学习算法逐步搜索，直至发现这种解。