---
{"publish":true,"created":"2024-11-21T06:17:32.000-05:00","modified":"2025-08-17T17:05:51.920-04:00","cssclasses":""}
---

#math/geometry/transformation , [[Transformation]]


# What is rotation
## Basic rotation
- In some cases, you may have to change a [[2D shape\|shapes]] [[orientation]]. 
- Here is an activity from edmentum example: ![[Files/Images/Pasted image 20240627095037.png]]
- We rotate $\triangle ABC$ around point $p$.
- ! Changing the angle of rotation does not affect the distance the shape is from point $p$.
- ~ If P moves away so do all the other triangles. If it moves closer then all the triangles get closer as well. This is because when P moves farther the distance from P and the preimage gets larger so the other triangles distance will also increase.


- When a [[plane]] figure rotates about a point on a [[plane]] it's [[orientation]] changes but the [[size]] and [[2D shape\|shape]] stay the same. The point is called the [[center of rotation]]. The center of rotation can lie anywhere on a [[plane]], in this figure it's origin.                ![[Files/Images/Pasted image 20240627095736.png|200]]
- The rotation around a point preserves the [[Distance]], the distance will stay consistent. 
- For when $A$ is a point in the [[preimage]] and $P$ is the [[center of rotation]]:
	- For each point $A$ in the [[preimage]] and $A'$ in the [[image (transformation)]], $\overline {PA}=\overline {PA'}$
	- The angle measure m$\angle APA'=a$ (measured clockwise or counterclockwise)
- The [[Angles\|Angle]] between any [[Line Segment]] in the preimage and the corresponding [[Line Segment]] in the [[image (transformation)]] is $a$. 
## Predicting rotations

- A few rotations are easy to describe

| Rotation about origin                                                       | Equation Relating Coordinates |
| --------------------------------------------------------------------------- | ----------------------------- |
| [[Right Angle\|90 degrees]] counterclockwise (270 degrees counterclockwise) | $(x',y')=(-y,x)$<br>          |
| [[Straight angles\|180 degrees]] counterclockwise or clockwise              | $(x',y')=(-x,-y)$             |
| 270 degrees counterclockwise ([[Right Angle\|90 degrees]] clockwise)        | $(x'y')=(y,-x)$               |
- ? Why does rotating something $90^{\circ}$ CCW around [[origin]] give us $(-y,x)$ 
	- Lets look at a few examples ![[Files/Images/Pasted image 20240629102153.png]]
		- Here we can see [[quadrilateral]] $ABCD$ and it's getting rotated $90^{\circ}$
		- It's "going" to [[origin]] and it does this by going 2 up 1 right. 
		- It then has to be rotated $90$ degrees, and to do this the [[slope]] of the line is going to be what makes it [[Perpendicular]] to the original [[line]] that got it to [[origin]]
		- It went 2 up 1 right before, so now it has to be the [[Reciprocal]] and [[Negative Number\|Negative]] so it will be 2 right 1 down to keep itself [[Perpendicular]] and go to the new point. We go exactly 2 right 1 down because the distance between the point and [[origin]] must be the same, we're just going in a different direction.
	- To synthesize [[using algebra]], we go from $(a,b)$ to $0,0$
		- To do this we [[Translation\|Translate]] both points by doing $(a-a,b-b)$ to get $(0,0)$. Our slope will be $\frac{{-b}}{-a}=\frac{b}{a}$
		- Now, to do our CCW rotation we have to travel by the line that is [[Perpendicular]] to our line that has slope $-\frac{a}{b}$. You may notice we only travel by both of these if our original [[preimage]] is in the 3rd quadrant. However, the [[Cartesian coordinate system]] is symmetrical no matter what way you rotate it so we can always pretend our [[preimage]] is in the 3rd quadrant so this explanation will always work.
		- ![[Files/Images/Rotation 2024-06-30 16.59.50.excalidraw]]
		- In the [[slope]] of a [[perpendicular lines on cartesian coordinate plane\|Perpendicular line]] on a [[Cartesian coordinate system]] we find the [[Reciprocal]] of the original slope and flip the sign
		- The problem with this explanation is that we can go either way now. We have the perpendicular line but now what?
			- Travelling counterclockwise
			- Same [[Distance]]
		- To get to origin, we travelled $-a,-b$, but now we travel $-b,a$ to get to the new [[point]] 
			- Thinking sesh: ![[Files/Images/Rotation 2024-07-01 07.29.05.excalidraw]]
		 
- ? Why does rotating something $180^{\circ}$ make the $x$ and $y$ negative? 
	- When we rotate something $180^{\circ}$ from origin, the [[point]] goes to origin by doing $(x-x,y-y)$. It then has to continue in the backwards direction of it's slope, so we subtract $-x$ and $-y$ again from it's respective values. 
- ? Why does rotating something $90^{\circ}$ clockwise around [[origin]] give us $(y,-x)$
	- we are doing basically the same thing for CCW but in the opposite direction. If [[point]] $(a,b)$ is rotated CW to get to origin it has to do $(a-a,b-b)$. To get to it's new point it has to go the [[Distance\|Same distance]] so we write in terms of $a$ and $b$. The [[slope]] of the line new line it's on will be [[Perpendicular]] to the slope of the original line with $(a,b)$ and $(0,0)$. However, instead of going left to right $(0-b,0+a)$ we're going right to left $(0+b,0-a)$ since it's a clockwise rotation

# Rotation as a [[Rigid Transformations\|Rigid transformation]]
- Rotation is a [[Rigid Transformations\|Rigid transformation]]
	- ![[Files/Images/Pasted image 20240628113043.png]]
	- The object is rotated around the [[center of rotation]]. Each point moves in a [[Circle\|circular path]] so the [[Distance]] from the center of rotation and the point remains constant. 

