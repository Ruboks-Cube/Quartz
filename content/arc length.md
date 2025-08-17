---
{"publish":true,"created":"2024-11-21T06:17:20.000-05:00","modified":"2025-08-17T17:05:15.289-04:00","cssclasses":""}
---

#math/geometry , [[2D shape]], [[arc]], #math/geometry/2d/shape/circle , [[Circle]]

- We can find the [[circumference]] by using the formula $2\pi r$
- However, in some instances we only need a part of a circle rather than the complete circle
	- A part of a circle is js called an [[arc]]
- [[concentric circles]]

 - ! to find arc length: 
	 - All we're doing is finding $\frac{{\angle AOB}}{360}$ and multiplying by $2\pi r$ -> The fraction we have of the circumference and multiplying BY the circumference
## Finding the length of an arc
- The length of an arc when given a [[central angle]] is proportional to the [[radius]] of the circle. 
- The [[circumference]] is the [[arc]] with a $360^{\circ}$ [[central angle]]
	- The central angle is js a [[Fraction]] of $360^{\circ}$ meaning the arc length will js be a [[Fraction]] of the [[circumference]]
- Using this knowledge we can set up a proportion:
	- $\frac{\text{arc length}}{\text{ circumference}}=\frac{\text{measure of central angle}}{360^{\circ}}$ 
- We know the measure of a [[central angle]] is js the [[Angles\|angle]] of the [[arc]]. We also know the [[circumference]] is js $2\pi r$. We can change our proportion:
	- $\frac{\text{arc length}}{2 \pi r}=\frac{\text{measure of arc}}{360^{\circ}}$ so:
	- $\text{arc length}=\frac{{\text{measure of arc}*2\pi r}}{360^{\circ}}$ 
- You can use this [[equations\|Equation]] to calculate the arc when given the [[radius]] and measure of [[arc]] 
	![[Files/Pasted image 20240805114928.png|200]]
- EG: In the diagram we can calculate $\overparen{AB}$ by doing $\frac{{\angle AOB*2\pi r}}{360}$  
	- ! All we're doing is finding $\frac{{\angle AOB}}{360}$ and multiplying by $2\pi r$ -> The fraction we have of the circumference and multiplying BY the circumference

## Problems
### Problem 1
![[Files/Pasted image 20240805115418.png|200]]
- Each length unit on the diagram represents $\frac{1}{10}$ of a mile. What is the total length, in miles of the track for the turn of $B$? Use $3.14$ for $\pi$ and round answer to 3 [[decimal]] places
- ! Bogus Solution
	- First, get the side lengths we DO know, $8,6,5$ -> Save these for later
	- Notice that all the [[arc\|arcs]] have the same [[radius]] which means all of them have the same [[circumference]]. 
		- Find the circumference, $3.14*6=18.84$
	- Now find each arc length:
		- ${} A=\frac{90}{360}*18.84=4.71 {}$
		- ${} B=\frac{102}{360}*18.84=5.338 {}$
		- $C=\frac{138}{360}*18.84=7.222$ 
	- Add everything we have-> $8+6+5+4.71+5.338+7.222=36.27$ -> 36.27 is our answer
	- ! Wrong, this is bogus because we didn't read the question properly 
- $ Correct solution
	- The radius of the circle is $0.3$ miles, we find the circumference and get:
		- $2(3.14)(0.3)=1.884$
	- Multiply this by $\frac{102}{360}$ and get $0.5338$ miles as our answer
