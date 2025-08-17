---
{"publish":true,"created":"2025-04-02T16:24:43.000-04:00","modified":"2025-08-17T17:06:01.790-04:00","cssclasses":""}
---

#math/arithmetic/logarithm 

- Basically, $\log_{2}4+\log_{2}8=\log_{2}32$ because $2+3=5$
	- So the rule is $\log_{a}X+\log_{a}Y=\log_{a}XY$ because ${} 4*8=32 {}$
	- but HOW?
		- $\log_{a}X=x$ asks for $x$ in $a^x=X$ 
		- $\log_{a}Y=y$  asks for $y$ in $a^y=Y$
	- We know that $a^y*a^x=a^{xy}$
	- logs are the inverse of exponents, so instead of multiplying its when you ADD THEM for [[Same Base exponent rules\|product of powers]]
	- Why is this?
		- Start with 3 logs
			- $\log_{b}a*c=x$
			- $\log_{b}a=y$
			- $\log_{b}c=z$
		- The first log tells us $b^x=a*c$
		- Second tells us $b^y=a$
		- third $b^z=c$ 
		- Using [[substitution]] we get $b^x=b^z*b^y$ 
		- this gives us $b^x=b^{y+z}$ so $x=y+z$ 
		- We can then substitute our values for $x$, $y$, and $z$ to be $\log_{b}a*c=\log_{b}a+\log_{b}c$ 
- ACTUAL PROOF: 
	1. $\log_{b}a+\log_{b}c$  → Get 2 logs
		- $\log_{b}a=x$ and $\log_{b}c=y$  → set them equal to values
	2. $x+y=\log_{b}a+\log_{b}c$ → Add the values together
	3. $b^x=a$ and $b^y=c$ → turn the logs from step one into [[Exponents\|exponential]] equations
	4. $b^{x+y}=a*c$ Simplify
	5. so $\log_{b}a*c=x+y$ Convert BACK to [[Logarithm]]
	6. [[substitution\|substitute]] values for $x+y$ which gives us $\log_{b}a*c=\log_{b}a+\log _{b}c$



If you think of $\log_{b}ac$ as the exponent from $b\to ac$ or just $[b\to ac]$ and set that equal to $x$ you have $[b\to ac]=x$. Then $[b\to a]=y$  and $[b\to c]=z$.

This means that $b^y*b^z=b^x$ and $b^{y+z}=b^x$.
$y+z=x$ so $[b\to a]+[b\to c]=[b\to ac]$ through [[substitution]].