---
{"publish":true,"created":"2024-11-21T06:17:30.000-05:00","modified":"2025-08-17T17:05:32.973-04:00","cssclasses":""}
---

#math/geometry/2d/shape/Triangle , [[parallel]], [[Triangle]], [[Line Segment]]

- ? What happens when 1 [[Line Segment\|side]] of a [[Triangle]] is [[parallel]] to a [[Line Segment]] that [[Intersect\|Intersects]] the other 2 [[Line Segment\|sides]]?
	![[Files/Images/Pasted image 20240711072157.png|Like this|300]]
- If a line is parallel to one side of a triangle and intersects the other two sides, then it divides the other two sides [[Proportion\|Proportionally]].
	- The ratio of $AD:DB=CE:EB$ 
	- ? BUT WHY??? You ask?
		- Thankfully Edmentum gave a proof
		- $\overline {DE} | | \overline {AC}$ -> given
			![[Files/Images/Pasted image 20240711194410.png|200]]
		- $\angle CAB \cong \angle EDB$ and $\angle ACB \cong \angle DEB$ -> [[Angles and parallel lines\|transversal lines]] -> [[corresponding angles]]
		- $\triangle ABC \sim \triangle DBE$  -> Angle angle criterion for similarity
		- $\frac{AB}{DB}=\frac{CB}{EB}$ -> Corresponding sides of [[similar]] triangles are [[Proportion\|proportional]] 
		- $AB=AD+DB$ and $CB=CE+EB$ -> segment addition
		- $\frac{{AD+DB}}{DB}=\frac{{CE+EB}}{EB}$ -> [[substitution property of equality]]
		- $\frac{AB}{DB}+1=\frac{CE}{AB}+1$ -> [[Division]]
		- $\frac{AB}{DB}=\frac{CE}{AB}$ -> [[Subtraction property of equality]]
- What if we take the [[Converse]] of the previous statement? If a line divides 2 sides of a triangle proportionally? Is that line parallel to the other lines? Lets see...
	- Problem with investigation:
		![[Files/Images/Pasted image 20240711082922.png]]
		![[Files/Images/Parallel lines and similar triangles 2024-07-11 08.40.13.excalidraw]]
		- Later on in the activity we see that a [[line]] passing through $D$ and $E$ is parallel to $\overline {BC}$ and now we wonder if it's always true... 
	- We'll now construct a proof
		![[Files/Images/Pasted image 20240711090717.png|150]]
		- Given $\triangle ABC$ with $\frac{AD}{DB}=\frac{CE}{EB}$ prove $DE | | AC$
			- $\frac{AD}{DB}=\frac{CE}{EB}$ -> Given
			- $\frac{AD}{DB}+1=\frac{CE}{EB}+1$ -> [[Addition Property of equality]]
			- $\frac{{AD+DB}}{DB}=\frac{{CE+EB}}{EB}$ -> Using [[adding fractions with different denominators\|common denominators]]
			- $AB=AD+DB$ and $BC=EC+BE$ -> Segment addition
			- $\frac{AB}{DB}=\frac{CB}{EB}$ -> [[substitution property of equality]]
			- $\angle ABC \cong \angle DBE$ -> [[Reflexive property of equality\|Reflexive property of congruence]]
			- $\triangle ABC \cong \triangle DBE$ -> [[SAS side angle side]] 
			- $\angle BAC \cong \angle BDE$ -> [[corresponding angles]] of [[similar]] triangles are [[congruent]] 
			- $\overline {DE} | | \overline {AC}$ -> [[Angles and parallel lines\|transversal lines]] 