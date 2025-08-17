---
{"publish":true,"created":"2024-11-21T06:17:22.000-05:00","modified":"2025-08-17T17:05:18.542-04:00","cssclasses":""}
---

#math/geometry #math/geometry/2d/shape/Triangle 

- [[median (Geometry)]] for [[Triangle\|Triangles]]--[[Intersect]] each other in an interesting way.          ![[Files/Images/Pasted image 20240706114800.png|300]]
	- ~ Given $\triangle ABC$ prove that the medians of $\triangle ABC$ are [[concurrent]]
		- Here is $\triangle ABC$:                 ![[Files/Images/Pasted image 20240706115740.png]]
		1. We define the [[vertex\|vertices]] of $\triangle {ABC}$ to have $3$ unique points $A(x_{1},y_{1}), B(x_{2},y_{2}), C(x_{3},y_{3})$ 
		2. Use [[Rigid Transformations]] to transform $\triangle ABC$ to $\triangle A'B'C'$ to that $\triangle A'$ is at [[origin]] and $\overline {A'C'}$ lies on the $x$-axis in the [[Positive Numbers\|positive]] direction. 
			- Diagram:                                                                                            ![[Files/Images/Pasted image 20240706120300.png]]
		3. Any property that is true for $\triangle A'B'C'$ is true for $ABC$ -> definition of [[congruent\|Congruence]]
		4. We let $r$,$s$, and $t$ be [[Real Numbers]] so the [[vertex\|vertices]] of $\triangle A'B'C'$ are $A'(0,0),B'(2r,2s), C'(2t,0)$ 
			- Diagram:                      ![[Files/Images/Pasted image 20240706120546.png]]
		5. Let $D'$ be the midpoint of $\overline {A'B'}$, $E'$ be the midpoint of $\overline {B'C'}$, and $F'$ the midpoint of $\overline {A'C'}$
			- Diagram:                                                                              ![[Files/Images/Pasted image 20240706120750.png]]
		6. We find the coordinates of the midpoints by finding the [[Mean]] of the [[vertex\|vertices]], ${} D'=()r,s) {}$ , $E'=(r+t,s)$ , $F'=(t,0)$
		7. OK I DON'T FEEL LIKE TYPING EVERYTHING OUT BUT ALL YOU NEED TO KNOW IS WE [[finding an equation of a line\|Found the equation of the lines]] by finding their [[slope]] and then solved the [[system of equations]]! 
		8. MEDIANS ARE [[concurrent]]