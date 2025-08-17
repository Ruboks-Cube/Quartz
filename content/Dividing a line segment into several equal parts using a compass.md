---
{"publish":true,"created":"2024-11-21T06:17:24.000-05:00","modified":"2025-08-17T17:05:21.933-04:00","cssclasses":""}
---

#math/geometry/creating , [[compass]], [[Geometry]], [[line]]

- While this method does not give us exact coordinates like [[Dividing line segments based on ratios]] does, it can still be useful to estimate 
- ? How can we divide line segment $AB$ into equal parts with a compass? (example w/ 5)
	- 1. Draw a [[Ray]] at any [[Angles\|Angle]] from $A$ roughly the same length as $AB$ 
		![[Files/Pasted image 20240729210742.png|Diagram|200]]
	- 2. Place the compass and adjust the width to around $\frac{1}{5}$ of $AB$
	- 3. Set the compass along the line making 5 [[arc\|arcs]], name the last one $C$
		![[Files/Pasted image 20240729210920.png|200]]
	- 4. With [[compass]] width set to $CB$ draw an arc below $A$ 
		![[Files/Pasted image 20240729211012.png|200]]
	- 5. With compass arc set to $AC$ draw another arc from point ${} B  {}$below $A$ creating point $D$
	- 6. Draw a line between $D$ and $B$
		![[Files/Pasted image 20240729211148.png|200]]
	- 7. Using the compass width used on $AC$ (1/5 $AB$) make $4$ arcs along $DB$
	- 8. Draw lines between the corresponding points on $AC,DB$
		![[Files/Pasted image 20240729211348.png|200]]
		done, the line segment $AB$ is separated into $5$ congruent segments 
- Proof
	![[Files/Pasted image 20240729211712.png|diagram|400]]
	- First prove that $AC$ and $DB$ are [[parallel]]
		- $AC=DB$ -> By construction, we set the compass equal to $AC$ when drawing $DB$ (step 5)
		- $AD=CB$ -> By construction, we set the compass width to $CB$ when drawing an arc to represent point $D$ for $AD$ (step 4)
		- $ACBD$ is a [[parallelogram]]. -> [[quadrilateral]] with [[congruent]] opposite sides is a [[parallelogram]]
		- $AC,DB$ are [[parallel]]. -> Opposite sides of a [[parallelogram]] are [[parallel]]
	- Then prove that $PE$ and $QF$ are [[parallel]] 
		- $PQ=EF$ -> Drawn with same compass width
		- $PQ,EF$ are [[parallel]] -> $AC$ and $DB$ are parallel
		- $PQFE$ is a [[parallelogram]] -> [[Proving a quadrilateral is a parallelogram with coordinate algebra]]
		- $PE$ and $QF$ are [[parallel]] -> Opposite sides of a [[parallelogram]]
	- Prove that [[Triangle]] $AQK$ is [[similar]] to and twice the size of $APJ$ 
		- $\angle APJ = \angle AQK$ -> [[corresponding angles]]. ${} AC {}$ is [[Angles and parallel lines\|transversal]] across the [[parallel\|parallels]] $PE,QF$
		- $\angle AJP = \angle AKQ$ -> [[corresponding angles]]. $AB$ is a [[Angles and parallel lines\|transversal]] across parallels $PE,QF$ 
		- [[Triangle\|Triangles]] $AQK$ and $APJ$ are [[similar]] -> [[AA, SAS, and SSS Criteria for Similar Triangles\|AA]] 
		- $\triangle AQK$ is twice the size of ${} \triangle APJ {}$ -> $AP=PQ$ -> Both are drawn with same compass width
	- Prove that $AJ=KJ$
		- $AK$ is twice $AJ$ -> $\triangle AQK$ is twice the size of $\triangle APJ$ -> $AP=PQ$ -> both are drawn with same compass width. 
		- $AJ=JK$ -> $J$ must be the midpoint of $AK$ -> Both $AJ$ and $JK$ are drawn with same compass width
	- We've proved the first 2 segments along the given line are [[congruent]], js do the same for each successive triangle now. We can show $\triangle ALR$ is similar to and is $3$ times $\triangle APJ$. This means that $AJ$ is $\frac{1}{3}$ $AL$
		- We can continue to show all segments are congruent.
		- $AJ=JK=KL=LM=MB$
 	

