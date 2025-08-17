---
{"publish":true,"created":"2024-11-21T06:17:20.000-05:00","modified":"2025-08-17T17:05:54.333-04:00","cssclasses":""}
---

#math/geometry/2d/shape/Triangle #math/geometry/2d/Perimeter_Area 

We know how to find the [[Area]] of a [[Triangle]] if we have the height and base, but what if we don't have the height?

## The rule
[[Splitting Isosceles or Equilateral triangle in half also splits the base and gives 2 right triangles]]
### Example Problem

Find the area of $\triangle ABC$

![[Files/Images/area of Isosceles and equilateral Triangles 2024-02-26 17.56.02.excalidraw]]
Source:
  <div class="nifty-link-card-container">
	<a class="nifty-link-card" href="https://artofproblemsolving.com/videos/prealgebra/chapter12/231" target="_blank">
		<div class="nifty-link-card-text" style="width: 100%;">
			<div class="nifty-link-card-title">Videos</div>
			<div class="nifty-link-card-description"></div>
			<div class="nifty-link-href">
			<img class="nifty-link-icon" src="https://artofproblemsolving.com/apple-touch-icon.png">
				https://artofproblemsolving.com/videos/prealgebra/chapter12/231
			</div>
		</div>
		
	</a>
  </div>
  
**What is the problem?**
- Since we don't have $h$ how do we find the area of this [[isosceles triangle]]?
- We could use the [[Pythagorean Theorem]] to find the height, and maybe we can assume that when we split $\triangle ABC$ that $\overline{BC}$ will be $\frac{18}{2}$ since $\frac{1}{2}$ of $18$ is $9$
	- In math we cannot ASSUME! We must prove!

**proving a and b are the same**
- We know that $a^2+h^2=15^2$
- We also know that $b^2+h^2=15^2$
- And we have a proof! Since both $b^2$ and $a^2=15$, we know that $a$ and $b$ must be the same value, since ${} 15^2-h^2=a^2 {}$ and $15^2-h^2=b^2$, they **are the same value!**
- so we have $a=b$

Now we know that A and B are Equal, so they must be 9.

Key take away: [[Splitting Isosceles or Equilateral triangle in half also splits the base and gives 2 right triangles]]
Now the diagram looks like THIS:
![[Files/Images/area of Isosceles and equilateral Triangles 2024-02-26 18.23.45.excalidraw]]
We can find $h$ with pythagorean theorem now
$15^2=9^2+h^2$, solve for $h$
$225=81+h^2$
$144=h^2$
$h=\sqrt{ 144 }$
$h=12$

So now we have 

![[Files/Images/area of Isosceles and equilateral Triangles 2024-02-26 18.32.02.excalidraw]]
HEY! This is a [[Pythagorean triples#3, 4, 5, triangles\|3:4:5 Triangle]]!
$3*3, 4*3, 5*3$

Now we do $\frac{12(18)}{2}$ which is $108$

