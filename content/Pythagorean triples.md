---
{"publish":true,"created":"2024-11-21T06:17:32.000-05:00","modified":"2025-08-17T17:05:58.677-04:00","cssclasses":""}
---

#math/geometry/2d/shape/Triangle 
- Pythagorean triples are what we call [[Right Triangle]]s that have [[integer]]s for all 3 sides, so $a$, $b$, and $c$ are all integers that all fulfill the [[Pythagorean Theorem]]
- There are many Pythagorean triples out there.
	- $3,4,5$
	- $5,12,13$
	- $8,15,17$
	- $7,24,25$
	

- Pythagorean triples


### 3, 4, 5, triangles

If you try to find some triples, you will find that you can start from 3,4, and 5 and multiplying the side lengths by the same factor, you will get a Pythagorean triple, as long as the factor is an integer itself.

Here is why:

A right triangle's legs have the ratio of 3:4, what is the hypotenuse?
This just means that one side is 3x and the other is 4x, so what is the hypotenuse in relation to this? Just break out the Pythagorean theorem and you will get $c^2=25$ which means that $c=5$.

3x, 4x, 5x, will always be a Pythagorean triple. And it makes sense, the [[Perfect Squares\|Square]] of 3 and 4 added make the square of 5, so the multiples of 3 and 4 should have the same relationship because of the [[Product of Powers, quotient of powers]] rule, and we can use it in REVERSE.

Take this example:
$3^2,4^2,5^2$,
$6^2,8^2,10^2$
$(3*2)^2,(4*2)^2,(5*2)^2$
The [[Ratio]] stays consistent.


Now, you may already know how to use this in problems because it's intuitive.


### Problems
Find $pq$
![[Files/Images/pythagorean triples 2024-02-21 19.09.00.excalidraw]]
The first step is to check the ratios of this triangle so we can see if this is a 3,4,5 triangle. What we do is put 1 side length over the other and simplify the [[Fraction]] so we can find out the simplified ratio.

$$
\frac{{252\sqrt{ 2 }}}{315\sqrt{ 2 }}
$$
The $\sqrt{ 2 }$'s cancel and after simplifying the fraction by using our [[3 and 9 for divisibility]] rules, we are left with $\frac{4}{5}$ 
So we know that this is a $3,4,5$ triangle, and now all we have to do is find the 3, since the ratio between the 2 side lengths we have are 4/5, we need the 3 side length
The ratio to the 4 side and the 3 side is 3:4, which means we multiply the 4 side by 3/4 to get the 3 side.
$252\sqrt{ 2 }\left( \frac{3}{4} \right)=189\sqrt{ 2 }$
And we're done :)

