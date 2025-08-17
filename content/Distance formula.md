---
{"publish":true,"aliases":"Finding the distance between 2 points on cartesian plane","created":"2024-11-21T06:17:24.000-05:00","modified":"2025-08-17T17:05:21.617-04:00","cssclasses":""}
---

#math/geometry #math/algebra , [[Geometry]], [[algebra]], [[Finding the distance between 2 numbers]], [[Pythagorean Theorem]]

- We use the [[Pythagorean Theorem]] to find the distance between 2 points.

# Problems
## Key ideas
- $ The distance formula between two [[ordered pair\|Ordered pairs]] $(x_{1},y_{1}),(x_{2},y_{2})$ is $\sqrt {(x_{1}-x_{2})^2+(y_{1}-y_{2})^2}$ , read the rest of the points to understand why
- We use the [[Pythagorean Theorem]] to find the distance between any 2 points
- We can use the same steps we did in [[Distance formula#8.4\|Problem 8.4]] to solve any finding the distance between 2 points problem. 
	- Suppose we have 2 points, $A$ and $B$ with coordinates $A=(x_{1},y_{2})$ and $B=(x_{2},y_{2})$. 
	- @ The little numbers are called [[Subscripts]]
	- Just like in [[Distance formula#8.4\|Problem 8.4]], we can build a [[Right Triangle]]. ![[Files/Images/Pasted image 20240526123825.png]]
	- We can see that $\overline{AC}$ is just the difference of the $x$ coordinates, so $x_{1}-x_{2}$ and $\overline {BC}$ is the difference of the $y$ coordinates, so $y_{2}-y_{1}$.
	- ! It doesn't matter if we're doing $x_{2}-x_{1}$ or $x_{1}-x_{2}$, what does matter is that it stays consistent. If we do $x_{2}-x_{1}$ then we must do $y_{2}-y_{1}$, think of the $x$'s and $y$'s like a reflection almost, if we take a difference from the $x$'s we must take the difference for the $y$'s in the SAME ORDER
	- We can now use the [[Pythagorean Theorem]] to solve for $\overline{AB}$, this gives us $(x_{1}-x_{2})^2+(y_{1}-y_{2})^2=\overline {AB}^2$
	- $ We then take the [[Radicals and Square Roots\|square root]] of both sides to get ${} \overline {AB}=\sqrt {(x_{1}-x_{2})^2+(y_{1}-y_{2})^2} {}$
	- ~ We note that here $B$ is to the right of $A$, but this will work no matter where $B$ is since we can always make a right triangle, unless $B$ and $A$ make a straight line, then either the $y$ or the $x$ will cancel out, giving us just the difference in $x$ or $y$ since we're just gonna be left with $(x_{1}-x_{2})^2=AB^2$ if the $y$'s [[cancel out]] which is equal to $x_{1}-x_{2}$, just the difference of $x$
	- @ If you know the [[Pythagorean Theorem]], you know the distance formula, because the distance formula is literally just the Pythagorean Theorem, you don't have to memorize the distance formula if you know the Pythagorean Theorem. 

## 8.4
![[Files/Images/Pasted image 20240526114556.png]]
- ~ Solution
	- One of the most common ways to find the distance between 2 points is to make a [[Right Triangle]] and use the [[Pythagorean Theorem]] ![[Files/Images/Pasted image 20240526121502.png]]
	- We connect $A$ and $B$ forming a [[Line Segment]]
		- We extend Line segments horizontally for $A$ and Vertically for $B$ until they intersect, this gives us point $C$ and $\triangle ABC$. 
		- ! Note how $C$ has the same $y$ coordinate as point $A$ and the same $x$ coordinate as point $B$. We could also do it the other way around, and have our 3rd point be at $-3,1$. We take the $x$ coordinate of $A$ and $y$ coordinate of $B$ which also works
	- Now we have to solve for $\overline{AB}$. To do this, we have to find $\overline{AC}$ a d $\overline{BC}$. We can do this easily because $\overline{AC}$ and $\overline{BC}$ are horizontal and vertical. We just find the distance like we would with a [[Number Line]], only considering the point we need. [[Finding the distance between 2 numbers]]
		- $\overline{AC}$ is horizontal so we consider the $x$ coordinate, just find the difference between $5$ and $-3$ which is $5-(-3)=8$, so $\overline{AC}=8$
		- $\overline{BC}$ is vertical so we consider the $y$ coordinate. Find the difference between $1$ and $-5$ which is $1-(-5)=6$. 
	- $\triangle ABC$ is a [[Right Triangle]], so we use the [[Pythagorean Theorem]].
		- $\overline {AC}^2+\overline {BC}^2=\overline{AB}^2$
		- We plug in the actual values for $\overline {AB}$ and $\overline {BC}$ to get $8^2+6^2=\overline{AB}^2$
	- $8^2+6^2=64+36=100$. This means that $\overline {AB}^2=100$, we [[Radicals and Square Roots\|square root]] this to get $\overline{AB}=10$ because distance must be positive.
