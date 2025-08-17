---
{"publish":true,"created":"2024-11-21T06:17:20.000-05:00","modified":"2025-08-17T17:05:14.858-04:00","cssclasses":""}
---

#math/geometry/2d/shape/Triangle #math/geometry 
- Here is a theorem:
	- The altitude to the [[Hypotenuse]] of a [[Right Triangle]] divides the triangle into two triangles that are [[similar]] to the original [[Triangle]] and to each other.
	- This is important because we can use it to prove the [[Pythagorean Theorem]], but first we have to prove this one


- Prove The altitude to the Hypotenuse of a right triangle divides the triangle into 2 triangles that are similar to the original triangle and to each other
	- Given $\triangle ABC$ with $\angle ABC = 90^{\circ}$ prove $BC^2=AC*DC, AB^2 =AC *AD$
		1. Draw $\overline {BD} \perp \overline {AC}$
			![[Files/Images/Pasted image 20240711191433.png|Diagram|200]]
		2. $\angle ABC \cong \angle BDC$ -> [[Angles]] with the same measure are [[congruent]]
		3. $\angle BCA \cong BCD$ -> [[Reflexive property of equality\|Reflexive Property of Congruence]]
				![[Files/Images/Pasted image 20240711191612.png|diagram|200]]
		4. $\triangle ABC \sim \triangle BDC$ -> AA criterion for [[similar\|similarity]]
		5. $\frac{BC}{DC}=\frac{AC}{BC}$ -> [[corresponding sides]] of [[similar]]--[[Triangle\|triangles]] are [[Proportion\|Proportional]] 
		6. $BC^2=AC*DC$ -> cross multiplication
		7. $AB^2=AC*AD$ -> similar steps but instead of doing $\triangle BDC$ we do $\triangle ABD$
			![[Files/Images/altitude of a triangle 2024-07-11 19.26.48.excalidraw]]
	- Now we prove the Pythagorean Theorem
		8. $BC^2=AC*DC$ -> Proved Earlier
		9. $AB^2=AC*AD$ -> Proved earlier
		10. $AB^2+BC^2=AC*AD+AC*DC$
		11. $AB^2+BC^2=AC(AD+DC)$ -> [[Distributive Property]] / [[Factoring]]
		12. $AB^2+BC^2=AC*AC$ -> Segment addition
		13. $AB^2+BC^2=AC^2$ 
			
	 