---
{"publish":true,"created":"2024-11-21T06:17:32.000-05:00","modified":"2025-08-17T17:05:37.515-04:00","cssclasses":""}
---

#math/geometry/2d/shape/quadrilateral  #math/geometry/2d/shape/Triangle 


> [!faq]- What's a rhombus?
> A [[quadrilateral]] in which all 4 sides have the same length
> - ! Every [[Perfect Squares\|Square]] is a rhombus but not every rhombus is a square



![[Files/Images/Rhombus 2024-02-29 20.28.08.excalidraw\|200]]

### Finding the area of any Rhombus
For this rhombus the side length of the diagonals are $x$ and $y$.
![[Files/Images/Rhombus 2024-03-01 14.11.57.excalidraw]]
The rhombus is split into 4 [[congruent]] [[Triangle\|Triangles]]. Finding the area of it would be
$$
\begin{align*}
(4)(\frac{1}{2}\left( \frac{y}{2}* \frac{x}{2} \right))
\end{align*}
$$
We can simplify it to be
$2\left( \frac{y*x}{4} \right)$
Then simplify even more to get $\frac{{yx}}{2}$ This looks a lot like the [[Triangle]] formula. This is because a rhombus is half the rectangle that makes it because it's made up of triangles.
![[Files/Images/Rhombus 2024-03-01 14.19.09.excalidraw]]


### Angles of a Rhombus
$ABCD$ is a rhombus
![[Files/Images/Rhombus 2024-03-01 14.23.52.excalidraw]]
- $\angle D \cong \angle B$ because the sides are the same and are symmetrical
- The top half of $\angle D$ and the bottom half of $\angle B$ are equal
- $\overline{DA} \parallel \overline{CB}$ because they are going in the exact opposite directions
- $\overline{DC} \parallel \overline{AB}$ because the bottom half of $\angle D$ and the top half of $\angle B$ are the same, so the sides are going the exact opposite ways
- A Rhombus has two pairs of [[parallel]] lines which means that it is also a [[parallelogram]]

>[!tip] Rhombus? Parallelogram?
>Every Rhombus is a [[parallelogram]] but every parallelogram doesn't necessarily have to be a rhombus   


### Problems
Source

  <div class="nifty-link-card-container">
	<a class="nifty-link-card" href="https://artofproblemsolving.com/videos/prealgebra/chapter12/266" target="_blank">
		<div class="nifty-link-card-text" style="width: 100%;">
			<div class="nifty-link-card-title">Videos</div>
			<div class="nifty-link-card-description"></div>
			<div class="nifty-link-href">
			<img class="nifty-link-icon" src="https://artofproblemsolving.com/apple-touch-icon.png">
				https://artofproblemsolving.com/videos/prealgebra/chapter12/266
			</div>
		</div>
		
	</a>
  </div>
##### Introduction Problem

Find the area of a rhombus where each side length is 25 and one diagonal has side length 30.
here is what the diagram looks like: 
![[Files/Images/Rhombus 2024-02-29 20.32.00.excalidraw]]
  >[!tip] How to approach these problems in the future
  >For any geometry problem, make a diagram!
  
  - We use the rule of [[isosceles right triangle]]s to find side lengths 15 for the diagonal that is 30
  - We the [[Pythagorean Theorem]] to find the length of the height.
$$
\begin{align*}

15^2+b^2=25^2\\
b^2=625-225\\
b^2=400\\
b=\sqrt{ 400 }\\
b=20
\end{align*}

$$ 
- We have the side length of 20 our diagram now is:
![[Files/Images/Rhombus 2024-03-01 14.02.38.excalidraw]]
Each [[Triangle]] that is part of the Rhombus is [[congruent]] Since we make each triangle from the same side lenghts.

Since they are congruent we can take the area of one triangle and multiply it by 4.

$(4\left( \frac{1}{2} \right)20*15)$ 
We multiply $4* \frac{1}{2}$ to get $2$.
$2(20*15)=600$

The area of this rhombus is $600units^2$


