矩阵是 a matrix of coefficient, a vector of unknowns
$$
\left|
    \begin{matrix}
    2&-1\\
    -1&2&\\
    \end{matrix}
\right|
\left|
	\begin{matrix}
	x\\
	y\\
	\end{matrix}
\right|
=
\left|
	\begin{matrix}
	0\\
	3\\
	\end{matrix}
\right|
$$
上面的方程可以记为AX = b,

A 是系数矩阵（coefficient matrix）

X是未知数矩阵（unknowns vector）

b是（right side vector）

上述方程的row picture就是我们小学就会的以x为横轴，y为纵轴，满足方程的解的点组成的直线在里面的图。



列图像，column picture， 
$$
x
\left|
    \begin{matrix}
        2\\
        -1\\
    \end{matrix}
\right|
+
y
\left|
    \begin{matrix}
        -1\\
        2\\
    \end{matrix}
\right|
=
\left|
    \begin{matrix}
        0\\
        3\\
    \end{matrix}
\right|
$$
这就是 liner combination

那么，如果是3个equation，3个unknowns呢？

比如
$$
\left[
	\begin{matrix}
		1&2&0\\
		2&1&0\\
		3&-1&4\\
	\end{matrix}
\right]
\left[
	\begin{matrix}
		x\\
		y\\
		z\\
	\end{matrix}
\right]
=
\left[
		\begin{matrix}
			0\\0\\4
		\end{matrix}
\right]
$$
行图像

可以想象应该是三维直角坐标系中三个平面交与一点

列图像

可以想象三维空间中三个向量的和



那么，如果是9个方程，9个未知数呢？

留给你自己去想想吧，哈哈


$$
AX=b
$$
A是一个matrix，x是一个未知数的向量，一个矩阵乘以一个向量代表着什么呢？

从行的角度来看，就是点乘（dot multiply）

从列的角度来看，就是矩阵中的列的线性组合命中b向量。

**Remember: This is what we should think of A times in next **

------------

Self think:

what is row picture?
for 2 equation 2 unknowns 方程组, it'a line that comsists of every coordinates of solution of a row of equation.

what is column picture?

the liner combination of column coefficient.
