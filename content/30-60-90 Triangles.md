---
{"publish":true,"created":"2024-12-12T17:30:32.000-05:00","modified":"2025-08-17T17:05:46.639-04:00","cssclasses":""}
---

#math/geometry/2d/shape/Triangle 
A 30-60-90 [[Triangle]] is a [[Right Triangle]] that has the angles 30 and 60. We can find the [[Area]] or [[Perimeter]] of these triangles from just one side length.

> [!NOTE] When thinking 30-60-90 Triangles think:
> Hypotenuse = 2 times small side
> Height = small side times $\sqrt{ 3 }$ 
> This is because a 30, 60, 90 triangle can become an Equilateral Triangle
> 
### Proof
![[Files/Images/30-60-90 Triangles 2024-02-29 17.45.21.excalidraw]]
In this proof we try to find the height $b$ by finding that the 30-60-90 [[Triangle]] by taking the triangle and flipping it. We see that this is an [[Equilateral Triangle]] and all the sides are equal to ${} 2x$ we can find the height by using the [[Pythagorean Theorem]].

$$
\begin{align*}
x^2+b^2=(2x)^2\\
b^2=4x^2-x^2\\
b=\sqrt{ 3x^2 }
b=x\sqrt{ 3 }
\end{align*}
$$
We plug in the values to the pythagorean theorem and get this. 



## Problems:
Source:
  <div class="nifty-link-card-container">
	<a class="nifty-link-card" href="https://artofproblemsolving.com/videos/prealgebra/chapter12/233" target="_blank">
		<div class="nifty-link-card-text" style="width: 100%;">
			<div class="nifty-link-card-title">Videos</div>
			<div class="nifty-link-card-description"></div>
			<div class="nifty-link-href">
			<img class="nifty-link-icon" src="https://artofproblemsolving.com/apple-touch-icon.png">
				https://artofproblemsolving.com/videos/prealgebra/chapter12/233
			</div>
		</div>
		
	</a>
  </div>
  
### Example problem in video

#### Starting problem
Find the area of ABC
![[Files/Images/30-60-90 Triangles 2024-02-27 19.14.01.excalidraw\|200]]
1 side length?! How do we do this trickery! Welp, if you remember [[Equilateral Triangle\|Equilateral Triangles]], then you know that an equilateral triangles [[Angles]] will be $60^{\circ}$ because all sides are equal, so all angles must be equal.

If we take $\triangle ABC$ and copy-paste it, flip it, and put it to the side, we will get an equilateral triangle, the top $30^{\circ}$ angles will turn into $60^{\circ}$ angles. The bottom side length would be 16 so the other 2 would also be 16. The formula for a triangle is $\frac{{h*b}}{{2}}$, but we can figure it out by doing the [[Pythagorean Theorem]]. $8^2+b^2=16^2$
$64+b^2=256$
$b=8\sqrt{ 3 }$


Now that we know that $b=8\sqrt{ 3 }$ we can use it to solve for the area!
$\frac{{8\sqrt{ 3 }*8}}{2}$ = $32\sqrt{ 3 }$

HEY! We double 8, we get 16, and the height of it is $8\sqrt{ 3 }$, is this always the case?

We can try to find the relationship between the 3 sides of a 30-60-90 triangle.

#### Last problem
Point X is on side $\overline{CD}$ of rectangle $ABCD$ such that segments $\overline{BX}$ and $\overline{BD}$ Trisect $\angle ABC$. If $Bx=4\sqrt{ 3 }$ Then what is $XD?$
![[Files/Images/30-60-90 Triangles 2024-02-29 18.35.24.excalidraw]]
Point x is on side cd so it trisects angle ABC, to trisect means to split into 3 equal parts so we can do that right here and add the side lengths we know.
![[Files/Images/30-60-90 Triangles 2024-02-29 19.01.59.excalidraw]]
The next step would be to find $\overline {BC}$ then we get $\overline{AD}$ which would help us get $\overline {AB}$ which is the same as $\overline {DC}$.

$(2\sqrt{ 3 })^2+b^2=(4\sqrt{ 3 })^2$
We can solve for $b$ to get $\overline {BC}$ and it will be
$12+b^2=48$
$b^2=36$
$b=6$

This means that $\overline {BC}=6=\overline{AD}$.
AD is 6 which means that $\overline{BD}=12$.

We use the wretched theorem again to find $\overline {DC}$.
$6^2+b^2=12^2$
$36+b^2=144$
$b^2=108$
$b=\sqrt{ 108 }$
Simplify and we get
$b=6\sqrt{ 3 }$.

Do get $\overline {DX}$ we simply do $6\sqrt{ 3 }-2\sqrt{ 3 }$ which is $4\sqrt{ 3 }$ and we're done!

or are we? BECAUSE THERE WAS A BETTER WAY TO DO IT, $\overline{DX}$ and $\overline{XB}$ are the SAME because angle D and angle B are the same making it an [[isosceles triangle]]. Eh, it was better to do it that way but WE STILL GOT THE ANSWER 👍

