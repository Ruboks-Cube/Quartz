---
{"publish":true,"created":"2024-11-21T06:17:32.000-05:00","modified":"2025-08-17T17:05:37.428-04:00","cssclasses":""}
---

#math/geometry #math/geometry/transformation , [[Transformation]], [[Geometry]]


- Imagine you are a production operator setting up an automated assembly for making Hydraulic Pumps. 
	- A robotic arm has to drill holes in each corner of a regular hexagonal steel piece which will be used as a pump cover. You need to make sure that the holes are drilled properly at all 6 corners of the piece. 
	- After each hole is drilled, the piece must be [[Rotation\|rotated]] precisely about its center so the next corner is correctly positioned under the drill. 
	- After the holes are drilled, the piece is transferred to a machine that paints both sides of the cover. During the painting process, the hexagon is [[Reflection\|flipped]] so both sides of the piece get painted the same way.
- To program these operations you need to learn the [[Rotation]] and [[Reflection]] [[Transformation\|transformations]]. 
## [[Rotation]]
- [[Regular polygon]] 
	- [[Polygon rotation aligning]]
- Regular polygons can go back to their original position multiple times during a full rotation.

## Reflection
- [[Rotation\|Rotations]] through the center of a polygon can return to its original position.
	- There is another class of [[Transformation]] that can do this and it's called [[Reflection\|Reflections]]
	- Just like [[Rotation]] about certain [[Angles]] can map a [[Polygon]] back on itself so can [[Reflection\|Reflections]] about certain [[line\|lines]].  

- ? How can we make it so a polygon reflects back on itself? Meaning that when use a [[line of reflection]], how can we make it so the polygon just says where it is?
	- $ The answer is [[Line of Symmetry]]
- When [[line]] of reflection is a line of symmetry, the [[image (transformation)]] will be the same as the [[preimage]] because the symmetrical [[point\|points]] are just switching sides so it looks like nothing happens. 
	- There are 2 lines of reflection for when the shape has an even amount of sides. Opposite [[vertex]] to opposite [[vertex]] and [[Perpendicular]] bisector of opposite [[Line Segment\|side lengths]]. 
		- Take this hexagon: ![[Files/Images/Pasted image 20240627154041.png]]
		- The image shows the [[Line of Symmetry\|Lines of Symmetry]] (or possible [[line of reflection\|lines of reflection]] to keep the [[2D shape\|shape]] as it is) for the [[Hexagon]].
			- You can see the [[line\|lines]] crossing the blue points are opposite [[vertex]] to opposite [[vertex]] lines
			- The lines crossing the green points are [[Perpendicular]] bisectors of opposite [[Line Segment\|sides]] 
	- When the shape has an odd amount of sides it's different. The vertex-vertex crossing does not lead to a line of symmetry. Instead, the line crosses a [[vertex]] AND bisects a [[Line Segment\|side]]. 
		- Take this [[Pentagon]]:                              ![[Files/Images/Pasted image 20240627154546.png]]


- ? What about irregular [[Polygon\|Polygons?]] 
	- [[Rectangle\|Rectangles]], [[Rhombus\|Rhombi]] and [[Trapezoid\|Trapezoids]] are all irregular polygons. 
		- When we were looking at [[Polygon rotation aligning]] the [[Regular polygon\|Regular Polygons]] had more [[Angles]] where they were aligned. It's similar to reflections. 
	- The diagonals of [[Perfect Squares\|Squares]] are [[line of reflection\|lines of reflection]] that keep the square on itself, but the diagonals of a [[Rectangle]] are not. 
		- A rectangle is symmetric only by cutting the [[Line Segment\|sides]] 
	- Some [[parallelogram\|parallelograms]] cannot map back onto themself after a [[Reflection]], only if all the sides of a parallelogram are equal in length, like a [[Rhombus]] it can be reflected across it's diagonals.                                                      ![[Files/Images/Pasted image 20240627160154.png|300]]




