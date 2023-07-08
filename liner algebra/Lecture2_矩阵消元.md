什么是消元？（elimination）

根据每个方程的主元（pivot）消去该方程下面的方程中该主元所在的列的项。
$$
1x + 2y + z = 2\\
3x + 8y + z = 12\\
     4y + z = 2
$$



$$
\left[
	\begin{matrix}
		1&2&1\\
		3&8&1\\
		0&4&1\\
	\end{matrix}

\right]
=
\left[
	\begin{matrix}
		2\\
		12\\
		2\\
	\end{matrix}
\right]
$$
//TODO write code to apply elimination


$$
\left[
	\begin{matrix}
		1&2&7
	\end{matrix}
\right]
\times
\left[
	\begin{matrix}
		-&-&-\\
		-&-&-\\
		-&-&-\\
	\end{matrix}
\right]
$$
**A row times a matrix means the combination of rows.**

通过上面一句加粗的话，我们可以用矩阵来表示消元的过程
$$
\left[
	\begin{matrix}
		1&0&0\\
		0&1&0\\
		0&-2&1\\
	\end{matrix}
\right]
\left[
	\begin{matrix}
		1&0&0\\
		-3&1&0\\
		0&0&1\\
	\end{matrix}
\right]
\left[
	\begin{matrix}
		1&2&1\\
		3&8&1\\
		0&4&1\\
	\end{matrix}
\right]
$$
第一个矩阵记作,用于将该位置设为0，也就是根据第二个pivot对第三行消元。
$$
E_{31}
$$
第二个矩阵记作，用于将该位置设为0，也就是根据第一个pivot对第二行消元。
$$
E_{21}
$$
例如$E_{21}$

第一行表示：系数矩阵的第一行 x 1 + 系数矩阵第二行 x 0 + 系数矩阵第三行 x 0

第二行表示：系数矩阵的第一行 x -3 + 系数矩阵第二行 x 1 + 系数矩阵第三行 x 0

。。。。。



如果要对$E_{21}$进行inverse，不难写出
$$
E_{21}^{-1} =
\left[
	\begin{matrix}
		1&0&0\\
		3&1&0\\
		0&0&1\\
	\end{matrix}
\right]
$$
