---
{"publish":true,"aliases":"slope of perpendicular lines","created":"2024-11-21T06:17:31.000-05:00","modified":"2025-08-17T17:05:54.008-04:00","cssclasses":""}
---

#math/geometry [[Cartesian coordinate system]], [[slope]]

- We wonder how the [[slope]] of 2 [[Perpendicular]] lines on a [[Cartesian coordinate system]] are related
- 
## AOPS
- Lets have 2 equations
	- $y=m_{1}x+b$
	- $y=m_{2}x+b$ where $m_{1}$ and $m_{2}$ are slopes that make it so the lines are perpendicular. How are $m_{1}$ and $m_{2}$ related.



- We take this question from [[introduction to algebra AOPS]]: ![[Files/Images/Pasted image 20240702173740.png]]
- Here are the graphs:                                                                                                                                                   ![[Files/Images/Pasted image 20240702173749.png|300]]
## Course
- How do the slopes of [[Perpendicular]]-[[line\|lines]] compare?
	- Prove that perpendicular lines have slopes that are the [[Negative Number\|Negative]]-[[Reciprocal]] of each other with a [[2 column proofs\|2 column proof]]
		- Given: $\overleftrightarrow {AC} \perp \overleftrightarrow {CB}$
		- Prove: [[slope]] of $\overleftrightarrow {AC}* \text{slope of } \overleftrightarrow {CB} =-1$ 
		1. Draw a line [[parallel]] to ${} x\text{-axis} {}$ through $C$ -> Construction
		2. Draw lines [[parallel]] to $y\text{-axis}$ through $A$ and $B$. Label the points of [[Intersect\|intersection]] with [[line]] through $C$ as $D$ and $E$, respectively
			![[Files/Pasted image 20240728191031.png|diagram|200]]
		3. $m\angle ADC=90^{\circ}$, and $m\angle BEC=90^{\circ}$ -> $\overleftrightarrow {DE} \parallel x\text{-axis}$ and $\overleftrightarrow {AD} \text{ and } \overleftrightarrow {BE} \parallel y\text{-axis}$ 
			![[Files/Pasted image 20240728194503.png|diagram|200]]
		4. $m\angle DCA+m\angle ACB+m\angle BCE=180^{\circ}$ -> $\overleftrightarrow {DE}$ is a straight [[line]] 
			![[Files/Pasted image 20240728195327.png|diagram|200]]
		5. $m\angle DCA+m\angle BCE=180^{\circ}-m\angle ACB$ -> [[subtraction\|subtraction]] property of equality 
		6. $m\angle ACB=90^{\circ}$ -> Given
		7. $m\angle DCA+m\angle BCE=90^{\circ}$ -> [[substitution property of equality]] 
		8. $m\angle DCA+m\angle CAD=90^{\circ}$ -> [[Complementary Angles]] in [[Right Triangle]] $ADC$
		9. $m\angle CAD=m\angle BCE$ -> [[Transitive Property]] and [[Subtraction property of equality]]  
		10. $m\angle ADC=m\angle BEC=90^{\circ}$ -> [[substitution property of equality]] (from step 3) 
		11. $\triangle ADC$ and $\triangle CEB$ are similar -> [[AA, SAS, and SSS Criteria for Similar Triangles]]
		12. $\frac{AD}{CE}=\frac{DC}{BE}$ -> [[similar triangles\|Similar triangles have proportional side lengths]]
		13. $\frac{AD}{DC}=\frac{CE}{BE}$ -> [[property of proportion]] 
		14. [[slope]] of $\overleftrightarrow {AC}=-\frac{AD}{DC}$ -> definition of slope (for [[Positive Numbers\|positive]] slope)
		15. slope of $\overleftrightarrow {CB}=\frac{BE}{CE}$ -> definition of slope (for a [[Positive Numbers\|positive slope]])  
		16. slope of $\overleftrightarrow {AC}*\text{slope of } \overleftrightarrow {CB}= -\frac{CE}{BE}* \frac{BE}{CE}$ -> multiplying the [[slope\|slopes]]
		17. slope of $\overleftrightarrow {AC}*\text{slope of } \overleftrightarrow {CB}=-\frac{CE}{BE} * \frac{BE}{CE}$ -> [[substitution property of equality]] (from step 15)
		18. slope of $\overleftrightarrow{AC} *$ slope of $\overleftrightarrow{CB}=-1$ -> simplifying the right side 
 