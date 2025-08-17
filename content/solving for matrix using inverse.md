---
{"publish":true,"created":"2024-11-21T06:17:33.000-05:00","modified":"2025-08-17T17:05:39.959-04:00","cssclasses":""}
---

#math/algebra/matrix 


Lets say you have an equation like: 
$$
\begin{bmatrix}
3&2 \\
2&1
\end{bmatrix} X= \begin{bmatrix}
11 \\
8
\end{bmatrix}
$$
- We can solve for this by using [[inverse matrix\|inverse matrices]]
	- Multiplying both sides by the inverse of $\begin{bmatrix}3&2 \\ 2&1\end{bmatrix}$ on THE LEFT SIDE because [[matrix multiplication#^4ebc52]]
	- Why the left side? Because that’s what you do to get rid of the matrix $\begin{bmatrix}3&2 \\ 2&1\end{bmatrix}$ if it was like $XA=B$ then we do $X=BA^{-1}$
	- When we multiply by inverse, we’re left with the [[Identity Matrix]] which is just like multiplying by 1, so we don’t need to write it
	- Now we can have our answer on the right 