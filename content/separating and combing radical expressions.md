---
{"publish":true,"aliases":"","created":"2024-11-21T06:17:33.000-05:00","modified":"2025-08-17T17:05:38.914-04:00","cssclasses":""}
---

 #math/arithmetic/exponent/radical 
# Square roots
### Square root of a product of [[Perfect Squares]]
We have to compute:
$$\sqrt{49\cdot25\cdot144}$$
Now, we obviously don't want to multiply all these out, so lets try to figure out a way to get the answer without having to do that. 

1. We first realize that 49, 25, and 144 are all [[Perfect Squares]]
	1. If we didn't realize that we could maybe [[Prime factorization\|Try Prime factorizing]] these numbers, since we know that prime factorization gives us the [[Exponents\|Powers of]] [[Prime Numbers]]
	2. After realizing that 49 is 7 squared, and 25 is 5 squared, and 144 is 12 squared we can move on
	
2. So now the problem is $$\sqrt{7^2\cdot5^2\cdot12^2}$$
3. Using our part example of [[Radicals and Square Roots#Finding big square roots\|Finding Square Roots of big Numbers]], we came across the problem of having multiple powers of 2, but we know to use our [[Product of Powers, quotient of powers]] rule and turn this expression into: $$\sqrt{\left(7\cdot5\cdot12\right)^2}$$
4. The [[Radicals and Square Roots#Square root if a square\|Square root of a square]] tells us that the square root of a square is just the base number, which in this case is 7 times 5 times 12, now we are left with: $$7\cdot5\cdot12$$
5. [[Multiplication\|Multiplying]] these gives us our final result:$$420$$
6. Celebrate

[[Finding big square roots]]


### Separating Square roots
#### First way to prove
source: https://artofproblemsolving.com/videos/prealgebra/chapter9/171
How to solve Products of Square roots
![[Files/Images/Square root of a product and product of square roots 2024-01-31 20.11.20.excalidraw]]
- We can combine products of square roots because when they are squared it equals them multiplied, the [[Radicals and Square Roots\|square root]] of them being multiplied should be the same
- We use the [[Product of Powers, quotient of powers]] rule
- This also means that we can seperate them, since they will be the same thing, both the square root of xy squared and the square of the square root of x multiplied by the square root of y equals xy


#### Second way, [[Fractional Exponent]]s way.

If we have $\sqrt x*\sqrt y$, we also have $(xy)^{1/2}$ through [[Product of Powers, quotient of powers]] rule which is equal to ${} \sqrt {xy} {}$
#### Problem that equals 0 (First problem in source)
Problem: Compute: $$\sqrt{15}\cdot\sqrt5-\sqrt{27}-\sqrt{12}$$
![[Files/Images/Square root of a product and product of square roots 2024-01-31 20.21.35.excalidraw]]
1.  We first write out the problem
2. We combine the square root of 15 and 5
3. we simplify the square root of 15 times 5 to 5 times the square root of 3
4. Simplify square root of 27 by beginning [[Prime factorization]] then seeing a [[Perfect Squares\|Perfect square, (9]]
5. Do the same with 12 that we did 9
6. Subtract common values, everything has a square root of 3
7. We see that 0 is infact, the answer



# Separating all [[Radicals and Square Roots\|Radical Expressions]]
if we have something like $\sqrt[y]{xa}$ we can separate them because this is equal to $(xa)^{1/y}$ which through the [[Product of Powers, quotient of powers\|power of a product]] rule is equal to $x^{1/y}a^{1/y}$ which is $\sqrt[y]x*\sqrt[y]a$.

We can also combine them by just reversing the process.

> [!Warning] WARNING
> We can only combine radicals of the same exponent


