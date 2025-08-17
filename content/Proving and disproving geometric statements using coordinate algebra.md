---
{"publish":true,"created":"2024-11-21T06:17:31.000-05:00","modified":"2025-08-17T17:05:53.490-04:00","cssclasses":""}
---

#math/geometry/2d/shape/circle , #math/geometry , #math/algebra, #math/graphing , [[Circle]], [[Cartesian coordinate system]], [[analytical geometry]]

Summary

- You can use [Coordinate algebra toapp://obsidian.md/analytical%20geometry):
    - Find the lengths of the [sides](app://obsidian.md/Line%20Segment) of a [Triangle](app://obsidian.md/Triangle) to prove whether a given triangle is [isosceles triangle](app://obsidian.md/isosceles%20triangle)
    - Calculate the measure of the [Angles](app://obsidian.md/Angles) of a triangle to determine whether a triangle is [Acute](app://obsidian.md/Acute%20Triangle) or not
    - Measure the [slopes](app://obsidian.md/slope) of line segments to prove whether or not a [quadrilateral](app://obsidian.md/quadrilateral) is a parallelogram
    - Show whether the sides of a quadrilateral are [Perpendicular](app://obsidian.md/Perpendicular) to their [adjacent](app://obsidian.md/adjacent) side, thereby proving whether the quadrilateral is a [Rectangle](app://obsidian.md/Rectangle)
    - Find the distance between a [point](app://obsidian.md/point) and the center of a [Circle](app://obsidian.md/Circle) to determine whether the point lies on the circle
## Circle
- When you are given the [[ordered pair\|coordinates]] of the center of a [[Circle]] and the coordinates of any point on the [[circumference]] you can use [[analytical geometry\|coordinate algebra]] or [[Geometry]] software to prove or disprove statements about the circle 
- Point _B_(-2, 4) lies on a circle centered at _A_(1, 3). Write a paragraph proof to determine whether _C_(4, 2) also lies on the circle.
	- I'm not going to write it out, but what you can do is use the [[Distance formula]] and see if the distance of $\overline {AB}$ is the same as the distance of $\overline {AC}$



## Quadrilaterals
#math/algebra #math/geometry , [[Cartesian coordinate system]], [[algebra]], [[analytical geometry]]

- Js like [[Proving and disproving statements of quadrilaterals with coordinate algebra]] you can do the same thing with [[quadrilateral\|quadrilaterals]] 
- A practice proof
	- [[Proving a quadrilateral is a parallelogram with coordinate algebra]]

## Triangles
#math/geometry #math/geometry/2d #math/geometry/2d/shape/Triangle #math/graphing , [[Triangle]], [[2D shape]], [[Cartesian coordinate system]]

- When you are given the [[ordered pair\|coordinates]] of a [[Triangle]] you can use [[ordered pair\|coordinate]]-[[algebra]] to prove or disprove facts about the [[Triangle]]
	- EG: You can find if the triangles are [[Equilateral Triangle\|equilateral]], [[isosceles triangle\|isosceles]], or [[Scalene Triangle\|scalene]] by finding the [[Line Segment\|lengths]] of the sides and determining if any of the sides have equal length



### Proving ABC is a [[Acute Triangle]]
- Consider $\triangle ABC$ which has [[vertex\|vertices]] at $A(-1,2), B(0,4), C(3,1)$ 
- Use coordinate algebra to determine whether $\triangle ABC$ is an [[Acute Triangle]] 
	- We'll find the [[Line Segment\|side lengths]] of $\triangle ABC$ and then use [[Trigonometry\|Trigonometry]] ([[How to solve a right triangle]]) to find the measure of all the angles

- Step 1, use the [[Distance formula]] to find the side lengths
	- [[vertex\|vertices]] of $\triangle ABC$ are $A(-1,2), \space B(0,4), \space C(3,1)$ -> Given
	- Using distance formula:
		- $AB=\sqrt {(0--1)^2+(4-2)^2}= \sqrt {1+4}=\sqrt {5}$ 
		- ${} BC=\sqrt {(0-3)^2+(4-1)^2}=\sqrt {9+9}=\sqrt {18} {}$ 
		- $AC=\sqrt {(-1-3)^2+(2-1)^2}=\sqrt {16+1}=\sqrt {17}$
- Step 2, find the [[Angles]] 
	![[Pasted image 20240727091758.png|Diagram|200]]
	- $AB^2=AC^2+BC^2-2(AC)(BC)\cos(C)$ -> [[How to solve a right triangle\|Law of cosines]], solve for ${} \cos(C) {}$
		- $5=18+17-2(\sqrt {18})(\sqrt {17})\cos(C)$ 
		- $5=35-6*\sqrt {34}*\cos(C)$ 
		- $\frac{5}{\sqrt {34}}=\cos(C)$ -> To get here we js used [[Inverse Operation\|inverse operations]], the $\cos(C)=\frac{5}{\sqrt 34}$ 
		- $\cos^{-1}\left( \frac{5}{\sqrt {34}} \right)=\angle C$ -> Use calculator for this [[Inverse Functions\|Inverse Function]]
		- $\angle C=30.96$ 
	- We have $\angle C$ so lets use the [[How to solve a right triangle\|law of sines]] to find the other angles
		- $\frac{\sin(C)}{\overline {AB}}=\frac{\sin(B)}{\overline {AC}}$ 
		- $\frac{\sin(30.96)}{\sqrt 5}=\frac{\sin(B)}{\sqrt {17}}$ 
		- $\angle B=71.55^{\circ}$ -> [[How to solve a right triangle\|law of sines]] 
	- $\angle A+\angle B+\angle C=180^{\circ}$ -> [[Triangle Sum theorem\|Triangle sum theorem]]
		- $71.55^{\circ}+30.96^{\circ}+\angle A=180^{\circ}$ 
		- $\angle A=77.49$ -> [[substitution]] and [[algebra]]
	- $\triangle ABC$ is an [[Acute Triangle]] 