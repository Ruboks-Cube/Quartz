---
{"publish":true,"created":"2024-11-21T06:17:23.000-05:00","modified":"2025-08-17T17:05:19.654-04:00","cssclasses":""}
---

#math/algebra/matrix 
- Cramers rule works when you have to [[solve for a matrix]], specifically only when there is only 1 column for the [[answer matrix]]
- Its very similar whether you are dealing with 2x2 matrices or 3x3 matrices


- Cramer’s rule goes as follows
	- PART 1, find the [[Denominator]]
		- Take the [[coefficient matrix]] and find the [[determinant]] of THAT
	- Part 2, solve for variables
		- Replace first column of [[Coefficient]] matrix with [[answer matrix\|constant matrix]]
		- Calculate [[determinant]] of new matrix and divide by the original determinant
		- This will be the first solution
		- Repeat these steps by taking the original matrix and replacing the next column until you’re done
