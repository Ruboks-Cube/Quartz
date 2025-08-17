---
{"publish":true,"created":"2025-04-29T19:21:36.000-04:00","modified":"2025-08-17T17:05:54.577-04:00","cssclasses":""}
---

#math/geometry/2d/shape/Triangle/trigonometry 
## Law of sines
- We use the law of sines when we have 2 sides and an angle opposite to one of the sides
	- Also when we have 2 angles and a side length not included between the angles.
- In some situations you need to [[solving a shape\|Solve a triangle]] with 2 angles given and a side or 2 sides given and 1 angle
	- The law of sines gives the angle opposite to a side or a side opposite to an angle

	![[Files/Images/Pasted image 20240715070834.png|non right triangles|200]]
	- In both of these situations you're given 3 parts of the triangle, lets see how you can use [[Trigonometry]] to determine the [[Line Segment\|side lengths]] and [[Angles]].
	- Lets see how we can [[solving a shape\|solve the triangle]] in both of these examples. 
		![[Files/Images/Pasted image 20240716100727.png|diagram|200]]
		- If we take a look at the diagram we see a triangle. Each angles' letter matches to the opposite side, so $\angle A$'s opposite side is $a$. 
		- We also see 2 [[Perpendicular]] lines that go from the angle to the matching side.
		- ? If we take a look at JUST [[Perpendicular]] line $AE$ and try to solve for it. We know that $\sin C=\frac{AE}{b}=b \sin C=AE$. We also know that $\sin B=\frac{AE}{c}=c\sin B=AE$
		- $ Now we have 2 [[equations\|Equations]], $b\sin C=AE$ and $c\sin B=AE$. Since both of these equal $AE$ we have $b\sin C=c\sin B$ which simplifies to $\frac{b}{\sin B}=\frac{c}{\sin C}$. 
		- Now lets take $BD$. We know that $\sin C = \frac{BD}{a}=a \sin C=BD$ . We also know $\sin A = \frac{BD}{c}=c\sin A=BD$. 
		- $ We now have 2 [[equations\|Equations]], $c\sin A=BD$ and $a\sin C=BD$.
			- Both equal $BD$ so we have $c\sin A=a\sin C$ which gives us $\frac{c}{\sin C}=\frac{a}{\sin A}$.
		- ! So we have $\frac{c}{\sin C}=\frac{a}{\sin A}$ and $\frac{c}{\sin C}=\frac{b}{\sin B}$... We have $\frac{a}{\sin A}=\frac{b}{\sin B}=\frac{c}{\sin C}$. This relationship can help us [[solving a shape\|solve triangles]].