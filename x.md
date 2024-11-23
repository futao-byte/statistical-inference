# 深度学习数学部分
## 2.5 范数
用于衡量向量的大小，因此使用范数(norm)来进行衡量。形式上 $L^p$ 的范数如下：

$$\left \|  x\right \| _{p} = \left(\sum_i \left| x \right|^p \right)^{\frac{1}{p}}$$

相当于范数是将一个向量映射到 $R+$ （非负实数集）。

范数的性质有以下三条：

- f(x) = 0 $\Longrightarrow$ x = 0
- f(x+y) $\le$ f(x) + f(y)
- $$\forall a \in R,f(ax) = \left|a\right|f(x)$$

当 p = 2, 这表示欧几里得距离，也就是我们所处空间中的距离，常简化表示为 $\left\| x\right\|$。

机器学习中的常用范数：
- $$L^1 范数：\left\| x\right\|_1 = \sum_{i}\left|x_i\right|x$$
