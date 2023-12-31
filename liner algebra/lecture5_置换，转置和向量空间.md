# 1.置换（permutation）

例如：
$$
\left|
    \begin{matrix}
    1&0&0\\
    0&1&0\\
    0&0&1\\
    \end{matrix}
\right|
$$
那么
$$
\left|    
\begin{matrix}    
0&1&0\\
1&0&0\\   
0&0&1\\   
\end{matrix}\right|
$$
就是他的一个置换矩阵，一个n阶的单位矩阵，有n！个置换矩阵（n个数有多少中排列）

矩阵分解A = LU，消元时可能遇到主元为0，因此需要置换行，

因此PA = LU



# 2.转置（transpose）

$$
A^T
$$

把一个矩阵行列互换得到他的转置矩阵
$$
(AA^T)^T = AA^T
$$


因此A乘以A的转置得到一个对称矩阵（symmetric matrix）

# 3.向量空间

定义：向量空间中的向量相加，乘以一个因子，得到的向量仍然在向量空间中。
$$
R^n
$$
$$R^n$$是由n个实数构成的向量 构成的向量空间。

二维空间的子空间：（0，0）、穿过0点的直线

一个矩阵的列向量通过加减乘除构成一个向量空间。