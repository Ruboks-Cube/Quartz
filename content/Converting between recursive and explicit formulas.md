---
{"publish":true,"created":"2024-11-21T06:17:22.000-05:00","modified":"2025-08-17T17:05:19.099-04:00","cssclasses":""}
---

#math/algebra/sequence , [[Sequence]], #math/algebra/inequality/equations 

- We can convert between [[Recursive Functions in arithmetic\|recursive formulas]] and [[explicit functions in arithmetic\|explicit formulas]]
	- A [[Recursive Functions in arithmetic\|recursive formula]] has the structure $a(n)=A$ (A is starting value) and $a(n)=B+a(n-1)$ where $B$ is the common difference → The recursive formula has 2 [[function\|functions]] 
	- A [[explicit functions in arithmetic\|explicit formula]] has the structure of $a(n)=A+B(n-1)$ where $A$ is the starting value and $B$ is the common difference
	- Therefore, we can convert a recursive formula ($B+a(n-1)$) into a [[explicit functions in arithmetic\|explicit formula]] by putting $A+B(n-1)$ where $n$ is the value you want

- We can ALSO convert a [[explicit functions in arithmetic\|explicit formula]] to a [[Recursive Functions in arithmetic\|recursive formula]] 
	- A recursive formula has structure:
		$$
\begin{cases}
a(1)=A \\\\
a(n)=a(n-1)+B
\end{cases}
$$
	- An explicit formula has structure:
		$$
a(n)=A+B(n-1)
$$
	- In both examples $A$ → Starting value $B$ → Common difference
	- With an explicit formula we know that $A$ is the starting value, so we already have the first part of our recursive formula
	- For the second part of our recursive formula, we set the common difference $(B)$to be added to $a(n-1)$ (common difference is added to the past value) 

# Problems

## Converting Recursive To explicit
- Write an explicit formula for this sequence
		$$
\begin{cases}
b(1)=-22 \\\\
b(n)=b(n-1)+7
\end{cases}
$$
	- $b(n)=-22+7(n-1)$ → We know the starting value and common difference  

## Converting Explicit to Recursive
- Convert $d(n)=5+16(n-1)$ 
	- This formula is given in the standard form
		- The first [[term]] of the sequence is $5$ and the common difference is $16$
	- We know the recursive formula is:
		1. The first [[term]] (we know is $5$)
		2. The pattern rule to get any term from the term before it
	- Therefore we have this:
		$$
\begin{cases}
d(1)= \textcolor{lightgreen}{5}\\\\
d(n)=d(n-1)\textcolor{red}{+16}
\end{cases}
$$
## IMPORTANT → Explicit Formula is in simplified form
- We are given the following explicit formula:
	$e(n)=10+2n$ 
- We want to convert into recursive
	- ! This formula is not in the standard explicit form
		$\textcolor{green}{A}+\textcolor{orange}{B}(n-1)$ 
		- For this reason we can’t just use the structure of the formula to find the first term and common difference, instead we find first 2 terms
	- $e(1)=12$
	- $e(2)=14$
	- The first term is $12$ and the common difference is $2$
- So for the recursive formula we have
$$
\begin{cases}
e(1)=12 \\
e(n)=(n-1)+2
\end{cases}
$$
- Another way to do this is to realize that we can “de simplify” the [[explicit functions in arithmetic\|explicit formula]]
	- We have $e(n)=10+2n$ and the standard form is $e(n)=A+B(n-1)$
	- We realize that we can simplify $A+B(n-1)$ by [[Distributive Property\|distributing]] the $B$ across $n-1$ to get $Bn-B$ so we have ${} A-B+Bn {}$
	- This means $2$ is $B$ and $A-B$ is → $12-2$ so we have $12-2+2n$, factor out the $2$ from $-2+2n$ to get $2(n-1)$ (we flipped $-1$ and $n$) so we have $12+2(n-1)$ and we know that the starting [[term]] is $12$ and the common difference is $2$ 
