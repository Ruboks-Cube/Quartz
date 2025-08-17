---
{"publish":true,"created":"2024-11-21T06:17:29.000-05:00","modified":"2025-08-17T17:05:29.461-04:00","cssclasses":""}
---

#math/algebra/matrix 

- Multiplying [[matrix\|matrices]] is a bit more difficult than you may think
	- The first step is to identify the rows and columns in each
	- $a\text{x}b \space b\text{x}c$ where $a,b,c$ are real numbers 
	- The columns of the first matrix and the rows of the second matrix have to be the same
	- **The order you multiply in matters in matrix multiplication** ^4ebc52
	- $a\text{x}c$ will be the dimensions of the new matrix
- Ok, if you have a situation where its possible to multiply the matrices
	1. Take the first row of the first matrix and the first column of the second matrix
	2. Multiply the first number in the first row by first number in first column, 2nd number in each, 3rd and so on until you’re done
	3. Add up all of these and now you have a number, that will be your first [[element]]
	4. Take the first row of first matrix and move on to second column of 2nd matrix (if there is)
	5. You multiply these the same, and add them the same, and you get a number, another [[element]]
	6. Once you’re done with all the columns with that row, move onto the next row
- Example:
$$
\begin{bmatrix}
x&y&z\\ \\
a&b&c
\end{bmatrix}*\begin{bmatrix}
s&t \\
u&v \\
w&o
\end{bmatrix}
$$
- The dimensions of our answer will be 2x2
- Take $xs+yu+zw$ and that will be our first element
- take $xt+yv+zo$ for second element
- Move onto row 2 and then do the same process to get all elements
- Elements you go left to right on first row and then down a row left to right and so on till you’re done