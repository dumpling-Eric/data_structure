### 1. 计算

**算法**：在特定的计算模型下，解决特定问题的指令序列；包含输入输出、正确性、确定性、可行性和有穷性。

一个好算法应该具备的条件：正确性、健壮性、可读性和高效率。

### 2. 计算模型

**算法分析**主要在两个方面：是否正确和成本大小。

用算法A求解某一问题规模为n的实例，所需计算成本讨论特定的算法A时，可以简记为$T(n)​$，并且是关注最坏时（成本最高时）

图灵机

![1564798516101](C:\Users\cxy\AppData\Roaming\Typora\typora-user-images\1564798516101.png)

![1564798538794](C:\Users\cxy\AppData\Roaming\Typora\typora-user-images\1564798538794.png)

根据需求进行移动，等到完成功能之后复位即可。

### 3. 渐进分析

大$O$记号：$T(n)=O(f(n))$ iff $\exists c>0, \forall n >> 2, T(n) < c*f(n)$

大$\Omega$记号：$T(n)=\Omega(f(n))$ iff $\exists c>0, \forall n >> 2, T(n) > c*f(n)$

大$\Theta$记号：$T(n)=\Theta(f(n))$ iff $\exists c_{1}>c_{2}>0, \forall n >> 2, c_{1}f(n) > T(n) > c_{2}*f(n)$

![1564799679788](C:\Users\cxy\AppData\Roaming\Typora\typora-user-images\1564799679788.png)

从$O(n^{c})$到$O(2^{n})$是算法时间复杂度从有效算法到无效算法的分水岭。

