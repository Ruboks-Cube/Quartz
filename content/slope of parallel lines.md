---
{"publish":true,"created":"2024-11-21T06:17:33.000-05:00","modified":"2025-08-17T17:05:39.687-04:00","cssclasses":""}
---

#math/geometry #math/algebra #math/graphing , [[analytical geometry]], [[Cartesian coordinate system]], [[slope]], [[Calculating Slope]], [[line]]
## [[slope]] of parallel lines
- How do the [[slope\|slopes]] of parallel lines compare with each other? 
	- By definition [[parallel]] lines never [[Intersect]] ]]
	- [[horizontal\|Horizontal]] lines are parallel to the $x$-[[axis]]. They have a [[0 slope and undefined slope\|slope of 0]]
	- [[vertical\|Vertical]]-[[line\|lines]] are [[parallel]] to the $y$-[[axis]]. They have an [[0 slope and undefined slope\|Undefined slope]] because the [[Denominator]] is $0$.
- Problem:
	- Prove that [[parallel\|parallel lines]] have the equal [[slope\|slopes]] with a [[2 column proofs\|2 column proof]]
	- Given: $\overleftrightarrow{AC} \parallel \overleftrightarrow {DF}$ 
	- Prove: [[slope]] of $\overleftrightarrow {AC} =$ slope of $\overleftrightarrow{DF}$ 
		1. Draw a line | | to the $x$-[[axis]] through $A$ and a line | | to the $y$-[[axis]] through $C$. Label the point of intersection $B$ -> construction
			![[Files/Pasted image 20240728103627.png|diagram|200]]
		2.  $\angle ABC$ is a [[Right Angle]] -> $\overline {AB} \parallel x\text{-axis and } \overline{BC} \parallel y \text{-axis}$ 
		3. Draw a line | | to the $x\text{-axis}$ through $D$ and a line | | to the $y\text{-axis}$ through $F$. Label the point of [[Intersect\|intersection]] of these 2 [[line\|lines]] $E$. Label the point where $\overleftrightarrow{BC}$ and $\overleftrightarrow {DF}$ [[Intersect]] $G$ -> construction
			![[Files/Pasted image 20240728104252.png|diagram|200]]
		4. $\angle DEF$ is a [[Right Angle]] -> $\overline {DE} \parallel x\text{-axis, and } \overline {EF} \parallel y\text{-axis}$ 
		5. $\angle ACB \cong \angle DGC$ -> corresponding [[Angles]] formed by [[Angles and parallel lines\|transversal]] $\overleftrightarrow {BG} \text{with} \space \overleftrightarrow{AC} \text{and} \space \overleftrightarrow {DF}$ 
			![[Files/Pasted image 20240728104657.png|100]]
		6. $\angle DGC \cong\angle DFE$ -> [[corresponding angles]] formed by [[Angles and parallel lines\|transversal]] $\overleftrightarrow {DG} \text{ with } \overleftrightarrow{FE} \text{ and } \overleftrightarrow {BC}$ 
		7. $\angle ACB \cong \angle DFE$ -> [[Transitive Property]] of [[congruent\|Congruence]] 
		8. $\angle ABC \cong \angle DEF$ -> All [[Right Angle\|Right angles]] are [[congruent]] 
		9. $\triangle ABC \text{ and } \triangle DEF$ are [[similar]] -> [[AA, SAS, and SSS Criteria for Similar Triangles\|AA criterion for similar triangles]] 
			![[Files/Pasted image 20240728105602.png|diagram|200]]
		10. $\frac{BC}{EF}=\frac{AB}{DE}$ -> pairs of [[corresponding sides\|corresponding side lengths]] in triangles have equal ratios 
		11. $\frac{BC}{AB}=\frac{EF}{DE}$ -> [[property of proportion]] 
		12. [[slope]] of $\overleftrightarrow{AC}=\frac{BC}{AB}$ -> [[Definition]] of [[slope]] 
		13. [[slope]] of $\overleftrightarrow {DF}= \frac{EF}{DE}$ -> [[Definition]] of [[slope]] 
		14. [[slope]] of $\overleftrightarrow {AC}= \text{slope of } \overleftrightarrow{DF}$ -> [[substitution property of equality]]
## Problems
- We proved the [[Theorem]] stating that [[parallel]]-[[line\|lines]] have equal [[slope\|slopes]]. 
	- This theorem allows us to use [[ordered pair\|coordinates]] to determine whether 2 lines are parallel or not 
	- Also helps us solve problems involving parallel lines

### Finding the equation of a [[line]] passing through a given point, [[parallel]] to a line with a known equation
 - Consider line $p$ which passes through $Q(5,3)$ and is [[parallel]] to $\overleftrightarrow {AB}$ whose [[equations\|Equation]] is $y=\frac{1}{2}x+\frac{7}{2}$. Find line $p$
	 - Recall that the [[slope intercept form]] is $y=mx+b$ 
	 - $\overleftrightarrow{AB} \to y=\frac{1}{2}x+\frac{7}{2}$ 
	 - $\overleftrightarrow{AB} \parallel \text{line} \space p$ so the [[slope\|slopes]] of the $2$ [[line\|lines]] are equal
	 - The equation for line $p$ would be $y=\frac{1}{2}x+b$
	 - To solve for $b$ we can [[Plugging in variables\|plug in]] our $y$ and $x$ values to get $3=\frac{1}{2}5+b$ 
	 - Solving for $b$ gives $\frac{1}{2}$
	 - The equation for $\text{ line } p$ is $y=\frac{1}{2}x+\frac{1}{2}$ 