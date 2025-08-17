---
{"publish":true,"created":"2024-11-21T06:17:30.000-05:00","modified":"2025-08-17T17:05:33.278-04:00","cssclasses":""}
---

#math/geometry/2d/shape/quadrilateral #math/geometry/2d/Perimeter_Area [[2 dimensional shape values]]

A parallelogram is a shape that has 2 sets of [[parallel]] lines. A [[Perfect Squares\|Square]], [[Rectangle]] and [[Rhombus]] could be examples of parallelograms.
>[!example] Parallelograms? Squares?
>Every square is a parallelogram but not every parallelogram is a square!


- [[Congruent Sides and parallel sides = parallelogram]]
### Angles of a parallelogram
#### Introductory Problem
$ABCD$ is a parallelogram in which $\angle A=41^{\circ}$ Find the measure of all angles of $ABCD$

- Start by making a diagram
![[Files/Images/parallelogram 2024-03-03 18.57.12.excalidraw]]
-  $\angle A+\angle B$ has to equal $180$ because $\overline{AD} \parallel \overline {BC}$  why?
	- Think of $AD$ and $BC$ as lines that go on forever, then think that $\overline{AB}$ intersects them, making a [[Angles and parallel lines\|transversal line]], they would then be corresponding
- Angle B is $180-41$ which is 139

- Our diagram now looks like this:
![[Files/Images/parallelogram 2024-03-03 19.05.56.excalidraw]]
- We can do the same thing to the other side
	- $\overline {AB} \parallel \overline{DC}$ so $\angle A + \angle D =180$ and $\angle B+\angle C=180$
	- The difference would be the same as the others so our diagram looks like this:

![[Files/Images/parallelogram 2024-03-03 19.08.35.excalidraw]]
We have found all the angles in the parallelogram with just one angle but notice something, the opposite angles are equal, is that something that happens to ALL parallelograms or is this one ⭐Special ⭐

#### Rules
##### Parallelograms have opposite angles equivalent
> [!info] Opposite Angle Parallelogram Rule
> in a parallelogram opposite angles are equivalent due to [[Angles and parallel lines\|transversal lines]] 
###### Explanation
- I noticed in the Introductory Problem that the [[Angles]] that were opposite to each other were equal, we will figure it out with [[variable math\|Variables]] to see if it's true for ALL parallelograms
>[!tip] Variables and rules
>Use variables when finding rules in math to see if they are true

Lets start with a diagram! My favorite tool in [[Geometry]]!
![[Files/Images/parallelogram 2024-03-03 19.17.49.excalidraw]]
And we know the rule is true!
- $\angle A$ is $x^{\circ}$, we know that $\angle D$ will be $(180-x)^{\circ}$ because $\angle A + \angle D = 180$ due to [[Angles and parallel lines\|transversal lines]] property and [[Straight angles\|supplementary angles]]
- $\angle B$ is the same thing where we use [[Angles and parallel lines\|transversal lines]] to get $(180-x)^{\circ}$
- Wrapping our mind around $\angle C$ is a bit trickier, we know that something plus $(180-x)^{\circ}$ will be $180^{\circ}$ and that must be $x$
	- We also know that $\angle B$ has $x$ as its "outside" angle, if we think that $\overline {DC}$ and $\overline {AB}$ go on forever and $\overline {BC}$ as the transversal line, the x would me correlating then using [[Vertical Angle]] property.
>[!tip] Angles? Transversal!
>When getting a problem about angles for a shape, try thinking about transversal lines and making [[parallel]] lines!

So yes! opposite angles are the same in a parallelogram!

>[!faq] If a [[quadrilateral]] has opposite angles being equal to each other, does that mean it's a parallelogram? 


##### Opposite Angles equivalent mean equal parallelogram?
>[!faq] do opposite angles being equivalent in a [[quadrilateral]] means that that shape is a parallelogram?

Is $PQRS$ a parallelogram? 
![[Files/Images/parallelogram 2024-03-03 19.40.03.excalidraw]]
this sure looks like a parallelogram but how can we we prove that $\overline {PQ} \parallel \overline {RS}?$

We know that a [[quadrilateral]] has angles that add up to 360 due to the [[Polygon Angles]] formula where $n=$ *number of sides*, $(n-2)180=$ *sum of angles*

- $2x+2y=360$, so $x+y=180$
This means it's a parallelogram because $x+y=180$ means that it's a [[Angles and parallel lines\|transversal line]] and correlating so it must be parallel.
![[Files/Images/parallelogram 2024-03-03 19.47.08.excalidraw]]




### Area of a parallelogram

> [!NOTE] The area is:
> The area is the height of the parallelogram times the base, similar to a rectangle

#### First Method
![[Files/Images/parallelogram 2024-03-04 17.49.25.excalidraw]]
Here we have a parallelogram and we want to find out how to find the area of a parallelogram. What we can do is take the [[Triangle]] off of one end and put it on the other to make a [[Rectangle]]. We know it makes a rectangle because the angles will line up. The **sum** of the top left angle and the top right angle must be 180 degrees because they are a pair of parallel lines.

We find the area of a parallelogram by doing $h*b$, basically a rectangle where h is the line going through the triangle and b is the base side length.

Why is finding the area of a parallelogram different from finding the area of a [[Rhombus]]? After all, each rhombus is a parallelogram but it's different because in a rhombus all sides are equal. 


#### Second Method
What if we area unable to chop off a side and put it on the other side like in this problem:
![[Files/Images/parallelogram 2024-03-04 18.02.37.excalidraw]]
What we do here is make a rectangle OUTSIDE
![[Files/Images/parallelogram 2024-03-04 18.04.28.excalidraw]]
Are we able to prove that the area is still the base times the height? 
Yes, the area of the parallelogram is equal to $h*(x+b)-{hx}$ 
(area of the rectangle) minus the areas of the 2 triangles
Simplifying the expression gives:
$hx+hb-hx=h*b$, we once again get base times height.

### [[Line Segment\|sides]] and [[Angles]] of a parallelogram congruency
- ~ Side length proving
	- Prove that the opposite side lengths of a parallelogram for $A,B,C,D$ are congruent
		- Points $A,B,C,D$ form a parallelogram-> Given
			- $AB | | CD$ and $BC | | AD$ -> Definition of parallelogram
		- Draw $AC$. This segment is [[Angles and parallel lines\|transversal]] to [[parallel]] lines $BC$, $AD$  and $AB$ and $CD$ 
			- Diagram:                  ![[Files/Images/Pasted image 20240707204338.png]]
		- $\angle CAB \cong \angle ACD$, and $\angle BCA \cong DAC$ -> Alternate interior angles theorem
			- Diagram:                                                         ![[Files/Images/Pasted image 20240707204500.png]]
		- $\angle CAB=\angle ACD$ and $\angle BCA=\angle DAC$ -> [[congruent]] angles have equal measures
		- $AC=AC$ -> [[Reflexive property of equality]]
		- $\triangle ABC \cong \triangle CDA$-> [[ASA angle side angle]] 
		- $AB\cong CD$ and $BC=AD$ -> [[corresponding parts]] of [[congruent]] [[Triangle\|Triangles]] are [[congruent]]
			- Diagram:                                                                                                     ![[Files/Images/Pasted image 20240707204753.png]]
- ~ Angle proving (we already proved it above) BUT there is a different proof w/ [[Triangle\|Triangles]] so
	- [[quadrilateral]] $ABCD$ is a [[parallelogram]] prove $\angle BAD \cong \angle DCB$ and $\angle ABC \cong \angle CDA$
		- Diagram:                                          ![[Files/Images/Pasted image 20240706132123.png]]
	1. $ABCD$ is a [[parallelogram]] -> GIVEN
	2. $\overline {AB} \cong \overline {CD}$ and $\overline {BC} \cong \overline {AD}$ -> Opposite sides of parallelogram are congruent
	3. $\overline {AB}=\overline {CD}$ and $\overline {BC} = \overline {CD}$ -> Congruent means they have same side length
	4. Draw $\overline {AC}$ and $\overline {BD}$ -> Drawing [[Line Segment\|Line Segments]]
		- Diagram:                                          ![[Files/Images/Pasted image 20240706132546.png]]
	5. $\overline {AC}=\overline {AC}$ and $\overline {BD}=\overline {BD}$ -> [[Reflexive property of equality]]
	6. $\triangle ABC \cong \triangle CDA$ and $\triangle ADB \cong \triangle CDB$ -> [[SSS side side side]]
	7. $\angle BAD \cong \angle DCB$ and $\angle ABC \cong \angle CDA$ -> [[corresponding angles]] are [[congruent]]
### Parallelograms and their [[diagonals]]
- Take both these Theorems:
	- If a quadrilateral is a parallelogram, then its diagonals bisect each other.
	- If the diagonals of a quadrilateral bisect each other, then the quadrilateral is a parallelogram.
- ~ Proving the first one
	- Given that $A,B,C,D$ is a parallelogram prove the diagonals $\overline {AC}$ and $\overline BD$ [[bisector\|Bisect]] each other
	1. The points make a parallelogram-> Given ![[Files/Images/Pasted image 20240706135634.png]]
	2. $\overline {AB} | | \overline {DC}$ and $\overline {BC} | | \overline {AD}$ -> [[Definition]] of parallelogram
	3. Draw $\overline {AC}$ and $\overline {BD}$ these line segments are [[Angles and parallel lines\|transversal lines]] cutting $\overleftrightarrow{AB} | | \overleftrightarrow {DC}$ and $\overleftrightarrow{BC} | | \overleftrightarrow { AD}$                              ![[Files/Images/Pasted image 20240706135957.png]]
	4. We place a point where the diagonals intersect:                                  ![[Files/Images/Pasted image 20240706140138.png]]
	5. $\angle {EAB}$ is congruent to $\angle ECD$ and $\angle EBA$ is congruent to $\angle EDC$ 
		- Diagram:                                                                                            ![[Files/Images/Pasted image 20240706140220.png]]
	6. $\angle A=\angle C$ and $\angle B=\angle D$ -> Congruent angles have same measures
	7. $\overline {AB} \cong {\overline {CD}}$  -> Opposite sides of a parallelogram are [[congruent]]
	8. $AB=CD$ -> [[congruent]] side lengths have equal measures
	9. $\triangle ABE \cong \triangle CDE$ -> [[ASA angle side angle]] 
	10. ${} \overline {AE} \cong \overline {EC} {}$, and $\overline {BE} \cong \overline {ED}$ -> [[corresponding parts]] of [[congruent]] [[Triangle\|Triangles]] are [[congruent]]
	11. $AE=EC$, $BE=ED$ -> congruent line segments have equal measures
	12. Diagonals $\overline {AC}$ and $\overline {BD}$ bisect each other -> [[Definition]] of [[bisector\|Bisection]]
- ~ Proving the second one
	- Given that $\overline {AC}$ and $\overline {BD}$ [[bisector\|bisect]] each other, prove that [[Quadrilateral ABCD.png]] is a parallelogram:                                                ![[Files/Images/Quadrilateral ABCD.png|300]]
	- $AE=EC$ , $BE=ED$ -> [[Definition]] of [[bisector\|bisection]] 
	- $\angle AEB \cong \angle CED$, $\angle BEC \cong DEA$ -> [[Vertical Angle\|Vertical Angles]] theorem                 ![[Files/Images/Pasted image 20240708062430.png]]
	- $\triangle ABE \cong \triangle CDE$ , $\triangle BEC \cong \triangle DEA$ -> [[SAS side angle side]]
	- $\angle ACD \cong \angle CAB$, $\angle DBC \cong \angle BDA$ -> [[corresponding angles]] of [[congruent]] [[Triangle\|Triangles]] are [[congruent]]
	- $\overline {AB} | | \overline {CD}$ , $\overline{BC} | | \overline {AD}$ -> [[Converse]] of [[Terminology of transversal lines\|Alternate Interior angles]] 
	- Quadrilateral $ABCD$ is a parallelogram -> Definition of parallelogram.