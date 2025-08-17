---
{"publish":true,"created":"2024-11-21T06:17:22.000-05:00","modified":"2025-08-17T17:05:18.952-04:00","cssclasses":""}
---

#math/geometry/2d/shape/Triangle 

- [[midpoint]]

- What happens if we connect the [[midpoint\|midpoints]] of 2 sides of a [[Triangle]]? Such a [[Line Segment]] is called a [[midsegment]]
- How can we prove that $DE$ is parallel to $AC$?
	- ~ [[using algebra]] Solution -> Proving DE is parallel to AC
		- $\triangle ABC$ has [[vertex\|vertices]] $A(x_{1},y_{1})$, $B(x_{2},y_{2})$, and $C(x_{3},y_{3})$ 
		- We let $D$ be the midpoint of $\overline {AB}$ and $E$ the midpoint of $\overline {BC}$ as shown: ->  ![[Files/Images/Pasted image 20240706110430.png]] -> Defining midpoints
		- $D=\left( \frac{{x_{1}+x_{2}}}{2}, \frac{{y_{1}+y_{2}}}{2} \right)$, and $E=\left( \frac{{x_{2}+x_{3}}}{2}, \frac{{y_{2}+y_{3}}}{2} \right )$  -> [[Definition]] of [[midpoint]]
		- The [[slope]] of $\overline{AC} =\frac{{y_{3}-y_{1}}}{x_{3}-x_{1}}$ and the slope of $\overline {DE} =\frac{{\frac{{y_{2}+y_{3}}}{2}-\frac{{y_{1}+y_{2}}}{2}}}{\frac{{x_{2}+x_{3}}}{2}-\frac{{x_{1}+x_{2}}}{2}}=\frac{{y_{3}-y_{1}}}{x_{3}-x_{1}}$ 
		- [[slope]] of $\overline {AC}=$ [[slope]] of $\overline {DE}$ -> [[Transitive Property]] 
		- $\overline {AC}$ is [[parallel]] to $\overline {DE}$ -> [[Definition]] of [[parallel]] [[line\|lines]]. 
		- Similarly: If $F$ is [[midpoint]] of $\overline {AC}$, then $DF$ is [[parallel]] to $\overline {BC}$ and $\overline {EF}$ is [[parallel]] to $\overline {AB}$ like this:               ![[Files/Images/Pasted image 20240706111433.png]]
	
- How can we prove $DE$ is half of $AC$? 
	- ~ Geometric solution -> Proving DE is half of AC
		- Prove that a midsegment is half of the line that it is parallel to:                 ![[Files/Images/Pasted image 20240706111653.png]]
		- $\overline {DE}$ and $\overline {DF}$ are [[midsegment\|midsegments]] of $\triangle ABC$ -> given
		- $D$, $E$, and $F$ are the [[midpoint\|midpoints]] of their respective side lengths -> Defining Midpoints
		- We choose $\overline {DE}$ to prove that it is half of $\overline {AC}$
		- $\overline {DF} | | \overline {BC}$ and $\overline {DE} | | \overline {AC}$ -> The proof right ontop of this one
			- $\overline {AB}$ is [[Angles and parallel lines\|transversal]] [[Intersect\|Intersects]] $\overline {DF}$ and ${} \overline {BC} {}$
			- $\overline {AB}$ transversal intersects $\overline {DE}$ and $\overline {AC}$
		- $\angle FAD \cong \angle EDB$
		- $\angle ADF \cong \angle DBE$ -> [[Terminology of transversal lines\|Corresponding Angles ]]
			- $AD=BD$ -> definition of midpoint
		- $\triangle DBE \cong \triangle ADF$ -> [[ASA angle side angle]]
		- $AF=\frac{1}{2}AC$ -> Definition of midpoint
			- $\overline {DE}= \overline {AF}$ -> [[corresponding parts\|Corresponding sides]] of a [[Triangle]] are [[congruent]]
		- $DE=\frac{1}{2}AC$
		- Similarly $DF=\frac{1}{2}BC$ and $EF=\frac{1}{2}AB$ -> follow steps but choose different line