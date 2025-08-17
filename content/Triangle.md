---
{"publish":true,"aliases":"#math/geometry/2d/shape/Triangle","created":"2024-11-21T06:17:35.000-05:00","modified":"2025-08-17T17:05:44.107-04:00","cssclasses":""}
---

#math/geometry/2d/shape/Triangle #tag
- A 3 sided [[Polygon]], AKA DORITO
	- A triangle is the simplest type of [[Polygon]]. Triangles and their properties have far reaching 
		- In construction triangles are used for stability
- [[Triangle Sum theorem]]

# Triangle Properties 
- [[connecting triangle midpoints]]
- [[Concurrent Triangle medians]]
### Opposite Side length?
- When we say opposite side length we are referring to the [[Line Segment\|sides]] of the triangle that is not [[adjacent]] to the angle we are talking about.
## Angles experimentation
- In triangles, the [[Line Segment\|Side length]] opposite to the largest [[Angles\|Angle]] is the largest
	- The [[Line Segment\|Side Length]] opposite to the smallest [[Angles\|Angle]] is the smallest
![[Files/Images/Pasted image 20240626195103.png|300]]
- take this triangle ABC. When we move $C$ closer to $B$ along $\overline {BC}$ what happens?
	- $\angle{ACB}$ gets larger, and $\angle {BAC}$ gets smaller. 
	- ? Why? This is because $\angle A$ needs to decrease to account for it's opposite [[Line Segment\|side length]]. $\angle C$ needs to get bigger since it's getting closer to [[Line Segment\|side length]] $\overline {AB}$ so the angle must get bigger so it "fits". 
- What happens when we move $C$ *farther*
	- The opposite will happen
	- $\angle {ACB}$ will get smaller, $\angle BAC$ will get smaller.
	- ? Why
		- $\angle ACB$ needs less of the angle for it to "fit" into $\overline {AB}$
		- $\angle BAC$ needs to increase since $\overline {BC}$ is increasing as $C$ moves farther


## Types of Triangles
We define what type of triangle it is with 2 different aspects of the triangle

### Angle
[[Right Triangle]]
[[Acute Triangle]]
[[Obtuse Triangle]]
### Side Length 
[[Equilateral Triangle]] 
[[Scalene Triangle]]
[[isosceles triangle]]
## How to find the [[Area]] of a Dorito

FOR ALL 3 TRIANGLES IT IS 1/2 TIMES BASE TIMES HEIGHT, go over each one to know why


So, how do we find the area of a triangle! First, lets consider the [[Rectangle]].
![[Files/Images/Triangle 2024-02-13 21.04.59.excalidraw\|100]]
You can see that a rectangle is 2 [[Right Triangle]]s put against each other. So how can we use THIS to find the area of a Right triangle?

### Right Triangle example
![[Files/Images/Triangle 2024-02-13 21.07.22.excalidraw\|200]]
When we multiply x and y to attempt to find the area of the triangle, we actually get the area of the rectangle since it's like you're multiplying length and width, there's nothing stopping it from becoming the area of the rectangle.<mark class="hltr-yellow"> Since a rectangle is TWO triangles, we can simply divide by TWO to get the area of the triangle! We're taking 1 half of the rectangle!</mark>

- In a triangle we actually don't call it length and width, we call it base and height
- The formula for finding the area of a triangle is xy/2

### [[Acute Triangle]]s
What about finding the area of an acute triangle?
![[Files/Images/Triangle 2024-02-15 18.25.25.excalidraw]]
- an acute triangle is just 2 right triangles
- We can see that by factoring "h" or the height and 1/2, we are left with x+y, the base
- The area of an acute triangle is base times height divided by 2

### [[Obtuse Triangle]]s
![[Files/Images/Triangle 2024-02-15 19.55.47.excalidraw\|200]]
- to find area for obtuse we can do the same thing with acute
- What if we want AB to be the base? How would we do that?
- We can draw a [[Rectangle]] *around* the triangle
![[Files/Images/Triangle 2024-02-15 19.58.54.excalidraw]]
- We have 2 right triangles around, so we can see what part of the rectangle triangle ABC is
- The area of ABC will be the area of ACY minus the area of CYB
![[Files/Images/Triangle 2024-02-15 20.04.46.excalidraw]]
- Hrm, this looks A LOT like doing the acute triangle thing, and we're left with 1/2(H)(AB)

# Triangle Problems

### Angle

The measure of the largest [[Angles\|Angle]] in a triangle is three times the measure of the smallest angle, and 23 degrees larger than the measure of the third angle of the triangle. What is the measure of the largest angle?
![[Files/Images/Triangle 2024-02-10 10.01.53.excalidraw]]
We first recognize that the largest angle is just 3 times the smallest angle, and then the middle angle is 3 times the smallest angle, - 23

Now we have a linear equation, because the angles of a triangle are [[Straight angles\|supplementary angle]]s, solving the [[Linear Equation]] gives is 29.
29 is the value of the smallest angle, so multiplying that by 3 should give us the largest angle (87).

### [[Angles and parallel lines\|transversal lines]] with triangles, eye trick
![[Files/Images/Pasted image 20240210100732.png|500]]
OKAY!
![[Files/Images/Triangle 2024-02-10 10.07.45.excalidraw]]
So, we filled it out, using [[Angles and parallel lines\|transversal lines]]. 
