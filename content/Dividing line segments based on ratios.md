---
{"publish":true,"created":"2024-11-21T06:17:24.000-05:00","modified":"2025-08-17T17:05:22.011-04:00","cssclasses":""}
---

#math/geometry #math/geometry/2d , [[line]], [[Ratio]], [[Division]]

> [!important]
> If point $C$ divides $\overline {AB}$ in the ratio $a:b$ the points' [[ordered pair\|coordinates]] are $\left( x_{c}=\frac{{ax_{b}-bx_{a}}}{a+b} \right)$    and $\left( y_{c}=\frac{{ay_{b}+by_{a}}}{a+b} \right)$ 
- DERIVING HOW TO DO IT
	![[Files/Pasted image 20240729142818.png]]
	- Their explanation: Find the coordinate of $C$ when $\overline{AB}$ is in the [[Ratio]] 
		- We have the [[Length and Width\|length]] of $\overline {AB}$ and we have the points $A(x_{A},y_{A})$ and $B(x_{B},Y_{B})$. We also know that the [[Ratio]] of $\overline{AB}$ is $a:b$ 
			- We can use the [[Ratio]] to find the distance from $A$ to $C$
				- ? How
					- [[Ratios come in groups]]
						- The [[whole of a group]] is $a+b$ since we're splitting $AB$ into parts $a$ and $b$. The [[part of a group\|parts of the ratio]] are $a$ and $b$. 
					- The whole [[Length and Width\|length]] of $AB$ is $a+b$. The ratio of $AC$ to $AB$ is $a:a+b$.  -> $a:a+b=AC:AB$ 
					- This means that $\frac{a}{a+b}=\frac{AC}{AB}$. To find the length of $AC$ we just multiply both sides by $AB$. 
			- Then use the [[Distance]] from $A$ to $C$ to find the [[ordered pair\|coordinates]] of $C$
				- ? How?
					- We know that $AC=\left( \frac{a}{a+b} \right)AB$ we get this from using our ratio $\frac{a}{a+b}=\frac{AC}{AB}$ and solving for $AC$. 
					- First lets consider simple [[horizontal]] and [[vertical]] lines
							![[Files/Pasted image 20240729192203.png|300]]
					- For a horizontal [[Line Segment\|segment]] like $AB$ the $y$-[[ordered pair\|coordinate]] is the same at all points
					- As the diagram shows, $AB=x_{B}-x_{A}$ and $x_{C}=x_{A}+AC$. This means
						- $x_{C}=x_{A}+\left( \frac{a}{a+b} \right)AB$ 
						- ! $x_{C}=x_{A}+\left( \frac{a}{a+b} \right)(x_{B}-x_{A})$  -> $x_{B}-x_{A}=AB$ because we find the [[Distance]] with finding the [[Finding the distance between 2 numbers\|difference]]. 
						- So we have $x_{C}$ equals the original $x$ value + the distance travelled
					- It's js like a [[Number Line]] 
					- We can do the same thing to a [[vertical]] line
						![[Files/Pasted image 20240729195920.png|300]]
						- In the case of a vertical segment, the $x$ coordinates stay the same 
							- ! We have $y_{C}=y_{A}+\left( \frac{a}{a+b} \right)(y_{B}+y_{A})$ 
				- Using these 2 formulas we can derive the general formula for the [[ordered pair\|coordinates]] of a [[point]] dividing the [[Line Segment]] by a [[Ratio]] 
		- Let us put together the steps to find the [[ordered pair\|coordinates]] of [[point]] $C$ which divides $\overline {AB}$ in the ratio $a:b$ for any [[orientation]] of $\overline {AB}$
		1. Write a [[Fraction]] $r$ corresponding to the [[Ratio]] $r=\frac{a}{a+b}$ 
		2. Find the differences of the x and y coordinates of $A$ and $B$ separately: $X_{AB}=x_{B}-x_{A}$ and $Y_{AB}=y_{B}-y_{A}$
		3. Multiply the differences by the fraction $r$ -> Why? Because you're multiplying it by how many [[part of a group\|parts of the total group]] giving you the [[Length and Width\|length]] of the side length that separates the original by the ratio $r$
		4. Add the differences of the [[ordered pair\|coordinates]] of $A$ to get the coordinates of $C$: $x_{C}=x_{A}+r(x_{B}-x_{A})$, and $y_{C}=y_{A}+r(y_{B}-y_{A})$ -> These are the formulas
		- The formulas can simplify things but as long as you know how it's derived you're good :) 
	- My explanation:
		- Lets say $C$ divides the line $AB$ into ratio $a:b$ meaning that $AC:CB=a:b$ 
			- This means that point $C$ is $\frac{a}{a+b}$ the distance from $A$ than $B$. If we separate the [[line]] $AB$ into $a+b$ parts, $AC$ makes up $\frac{a}{a+b}$ parts
		- We want to find the [[ordered pair\|coordinates]] of $c$. The coordinates of $A=(x_{1},y_{1})$ while the coordinates of $B=(x_{2},y_{2})$ 
		- If we take the total horizontal distance between $x_{1}$ and $x_{2}$ we js have $x_{1}-x_{2}$
		- If we multiply this distance by our ratio $\frac{a}{a+b}$ (which is what we get when we make $\frac{a}{b}$ into a [[Parts to a Whole]] ratio) we will get a new length which is the length of one "side" of $x_{1}-x_{2}$
			![[Files/Dividing line segments based on ratios 2024-07-30 10.11.05.excalidraw]]
		- So what we're doing here is finding the length of $AC_{1}$ which we can then add onto $x_{1}$ to get the $x$ coordinate of $C_{1}$ which is the $x$ coordinate of $C$ 
		- We can do the same process for $y$ where we take $y_{2}-y_{1}$ and now we find the distance from $D$ to $C_{2}$
			- We know that $\overline {DC_{2}}:\overline{DB}=a:a+b$ so we multiply $DB$ by $\frac{a}{a+b}$ which gives us $DC_{2}$ which we can then add to $D$ to get $C_{2}$ which in turn gives us our $y$ coordinate of $C$
		- Now, you may be wondering something. How do we know that $AC:AB=AC_{1}:C_{1}D=DC_{2}:DB$, how do we know all the ratios stay the same? 
	- How to think about it
		- If we want to solve for $C$ that splits $AB$ into the ratio $a:b$, we can think of the coordinates of $C$ as $\left( x_{A}\pm \frac{a}{a+b}(x_{A}-x_{B}), y_{A}\pm \frac{a}{a+b}(y_{A}-y_{B}) \right)$ 
			- The original $x$ coordinates plus OR minus the differences of $x$ times the [[Fraction]] of the original line
			- The original $y$ coordinate plus OR minus the differences of $y$ times the [[Fraction]] of the original line
			- I say plus OR minus because it depends on the direction you're going. 
- [[Dividing a line segment into several equal parts using a compass]]
