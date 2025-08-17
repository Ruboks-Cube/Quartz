---
{"publish":true,"created":"2024-11-21T06:17:32.000-05:00","modified":"2025-08-17T17:06:00.729-04:00","cssclasses":""}
---

#math/geometry/transformation [[Transformation]]

# What is a reflection
## Basics
- Recall the aircraft design thing from [[Translation]]. As well as translating shapes the software program may have to flip a shape to make a mirror image of an airplane part. For example, each wing is a mirror image of the other
- Lets see the transformation that carries a [[preimage]] onto a mirror image. These are called reflections. ![[Files/Images/Pasted image 20240627084858.png|200]]


- To produce a reflection, or mirror image, you need to specify a [[line of reflection]]. When mirroring objects on a [[plane]], a line of reflection is represented by a straight [[line]].

- In this image [[Polygon]] $ABCD$ is being reflected across the [[line]] ($EF$). No matter where we move the [[preimage]] the line segments we made corresponding to the points always have the same angle. They are always [[Perpendicular]] to the line it reflects across. This is because it's a reflection, the angle is not going to change it's always going to stay consistent.  ![[Files/Images/Pasted image 20240627093152.png|200]]
- Ignore the polygon on the bottom right. If we take the [[Distance]] of each point to the [[line of reflection]], the corresponding points will have the same [[Distance]] because it's a reflection.                                                                                            ![[Files/Images/Pasted image 20240627093718.png|200]]
- The line of reflection is the [[Perpendicular]] [[bisector]] for a line segment with 2 corresponding points across a [[line of reflection]]. 

## Reflections as [[Rigid Transformations]]
- A point and it's corresponding point across the [[line of reflection]] are equidistant from it. The line of reflection is a [[Perpendicular]] bisector of the [[Line Segment]] between 2 points.
- A reflection is a [[Rigid Transformations\|Rigid transformation]]. 
## Predicting Reflections
- If the reflection is across the $x$ axis you flip the sign of $y$
- If the reflection is across the $y$ axis flip the sign of $x$
- If the reflection is the [[Linear Equation]] $y=x$ you swap the $x$ and $y$ values
	- ? Why?                                                                      ![[Files/Images/Pasted image 20240628164622.png]]
		- You can see here it happens for this polygon, but how do we know it happens for every polygon? We let $\triangle ABC$ represent a triangle where $A=(x_{1},y_{1})$ $B=(x_{2},y_{2})$ and $C=(x_{3},y_{3})$ 
			- We have an equation $y=x$ and that is a [[line of reflection]] to create $A'B'C'$
		- $y=x$ runs at a $45^{\circ}$ [[Angles\|Angle]] and the [[Distance]] from $A$ to $A'$ must be the same to $y=x$ since it's a [[Perpendicular]] bisector. 
		- We know that if we move straight up the line and once we meet it and then move left straight we will end up. This means that we added $y$ to $y$ and subtracted $y$ from $x$. 
		- We can also do the other way around and move straight left and then straight up the same distance. 
		- We also know we take the minimum [[Distance]] from the [[preimage]] then "add" it on the opposite direction to get the [[image (transformation)]]. 
- ? Why (Intuitive explanation)
	- When we reflect something across $y=x$, the roles of $x$ and $y$ flip
		- $y=x$ goes at a $45^{\circ}$ angle
		- This means that if we fold the [[Cartesian coordinate system\|Cartesian coordinate plane]] with the [[line]] $y=x$ as the middle and there is a [[point]] the point will reflect on the other side
		- ! Moving [[horizontal]] on one side of $y=x$ means moving [[vertical]] on the other side of $y=x$, which is why the roles are switched
		- Here is a diagram:                ![[Files/Images/Reflection 2024-06-28 20.50.34.excalidraw]]
	- ! We know that the line of reflection is the [[Finding the midpoint between 2 points\|Midpoint]] of [[Line Segment\|The line segment]] between the 2 points that we are [[Reflection\|Reflecting]], the [[preimage]] and the [[image (transformation)]]
		- The slope of the [[preimage]] and the [[image (transformation)]] will be $-1$. Lets draw this out ![[Files/Images/Reflection 2024-06-28 18.53.11.excalidraw]]
		- We basically notice that we can form a [[system of equations]] to find $M$
			- We know that $M=\left( \frac{b+a}{2}, \frac{{b+a}}{2} \right)$ 
			- how do we find $(c,d)?$
			- We know that the $x$ and $y$ coordinates of $M$ is the [[Mean]] of the points so what can $(c,d)$ be?
		- $(c,d)$ has to be $(b,a)$ because that is the only [[point]] where $M$ can be the midpoint since it takes the average. 
- If the reflection [[line]] is the [[Linear Equation]] $y=-x$ then you flip the sign of the values and swap them $(-y,-x)$.
	- ? Why?
		- We can use roughly the same system we used for the other one
		- If we reflect a [[point]] through $y=-x$, we can let the point $M$ be where the line [[Perpendicular]] from our point (lets call it $(a,b)$)
		- The line with slope $1$ is [[Perpendicular]] to $y=-x$. 
		- The equation for the like would be ${} y=x+(b-a) {}$ 
		- Now we have a [[system of equations]]
			- $y=-x$
			- ${} y=x+(b-a) {}$
			- ${} -x=x+(b-a) {}$
			- ${} -2x=(b-a) {}$
			- ${} x=-\frac{b-a}{2} {}$
			- ${} y=-\frac{{b-a}}{2} {}$
		- So we know that $M$ is $\left( -\frac{{b-a}}{2}, -\frac{{b-a}}{2} \right)$
		- What does this mean for $(c,d)$ (the [[image (transformation)]] of the [[Reflection]])
			- $M$ is the [[Finding the midpoint between 2 points\|Midpoint]] between $(a,b)$ and $(c,d)$ so it's coordinates are the average
		- The only way the coordinates can be average is if $(c,d)$ is if it's $(-b,-a)$ or $(-y,-x)$ because $M$ is the [[Mean]] of the 2 points.
			- Another way to explain would be if we have $\frac{{a+x}}{2}$ (finding the average of the [[preimage]] $x$ coordinate and something else) and have it be equal to $\left( -\frac{{b-a}}{2} \right)$ (the average)
			- solving this gives $\frac{{b-a}}{2}$ 
	- ? Why? (Intuitive)
		- The $y$ and $x$ swap because in the [[Reflection]] they suddenly swap roles, moving down in one of them (y) means moving right in the other (x)
			- You're moving away or toward origin in a different manner.
			- $y=-x$ is different from $y=x$ because if the [[preimage]] moves right in $y=-x$ the [[image (transformation)]] moves down, showing that the signs flip because it's moving away from [[origin]] like it would for $y=x$ but in a completely different (opposite) direction.



