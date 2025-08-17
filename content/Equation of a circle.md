---
{"publish":true,"created":"2024-11-21T06:17:25.000-05:00","modified":"2025-08-17T17:05:22.966-04:00","cssclasses":""}
---

#math/geometry #math/geometry/2d #math/graphing , [[Cartesian coordinate system]], [[Circle]], [[equations\|Equation]]

- We know that [[analytical geometry]] brings [[Geometry]] and [[algebra]] together
	- We can [[finding an equation of a line\|Find the equation of a line]]
	- ? What about a [[Circle]]?
### Standard form deriving
- By definition all points of a [[Circle]] are equidistant. 
	- The [[equations\|Equation]] of a circle probably utilizes the [[Distance formula]]
	- ! Lets start with a special case where the center of a circle is at [[origin]], [[point]] $O(0,0)$. 
		- For any [[point]] $P(x,y)$ that lies on the circle the distance from the center would be $d=\sqrt {(x-0)^2+(y-0)^2}=\sqrt {x^2+y^2}$
		- This distance has to be equal to the [[radius]] so we can set ${} \sqrt {x^2+y^2}=r {}$ where $r$ is the length of the radius.
		- [[Perfect Squares\|squaring]] both sides gives $x^2+y^2=r^2$, the standard [[equations\|Equation]] for a circle if the center is at [[origin]] -> [[Pythagorean Theorem]]
		![[Pasted image 20240725204219.png|diagram|200]]
		- Looking at the diagram, we get the same equation by applying the [[Pythagorean Theorem]] with the [[Right Triangle\|Right triangles]] which both have [[Line Segment\|side length]] $r$. 
- We know the [[equations\|Equation]] of a circle centered at origin but what about a circle that's not?
	- If we let $(h,k)$ represent the center of the [[Circle]], the equation of a circle will be $(x-h)^2+(y-k)^2=r^2$ where $r$ represents the radius
	- ? Why does this equation work?
		- This equation is simply a use of the pythagorean theorem. We find the [[Finding the distance between 2 numbers\|difference]] of $x$ [[Perfect Squares\|Squared]] + difference of $y$ [[Perfect Squares\|Squared]] which equals the [[Hypotenuse]] squared which is in this case the [[radius]]. 
	- ! This equation is known as the standard form 
### [[completing the square]] to get standard form
- Sometimes you may want to find out the standard form of a circle but they actually give something called general form.
	- The equation: $Ax^2+By^2+Cx+Dy+E=0$ where $A,B,C,D,E$ are [[Real Numbers]]. 
	- When the equation is given in this form is more difficult to find the center of a circle. 
	- To change the circles equation we need to make use of [[completing the square]]. 
- ~ Lets look at an example 
	- This is a general form equation: $3x^2+3y^2-6x+12y-12=0$, lets convert it to a standard form
		- $x^2+y^2-2x+4y-4=0$ -> divide the equation by the [[Coefficient]] of $x$ or $y$
		- $x^2+y^2-2x+4y=4$ -> Move constant term to right side
		- $x^2-2x+y^2+4y=4$ -> Rearrange terms on left side 
		- $x^2-2x+1+y^2+4y+4=4+1+4$ -> [[completing the square\|complete the square]] 
		- $(x^2-2x+1)+(y^2+4y+4)=9$ -> Group the terms
		- $(x-1)^2+(y+2)^2=9$ -> Simplify using the identities $(a\pm b)^2=a^2\pm 2ab+b^2$
	- This process can be used for any general equation that is the equation of a circle. 

## Problems
### Key ideas
- Key points
	- Use the [[Distance]] formula to ensure you get the right radius
	- make sure you [[Perfect Squares\|Square]] the radius in the standard form equation
	- when completing the square insure that you:
		- Add the value that "completes the square" like this: $\left( \frac{b}{2a} \right)^2$ -> This ensures you don't mess up. Sometimes I accidentally do $\frac{\frac{\frac{b}{a}}{2}}{2}^2$ which makes no sense but it happens
		- Add $\left( \frac{b}{2a} \right)^2$ to both sides -> If you don't add to both sides, you're equation is js gonna be false!
- If you have the center [[point]] of the circle you can find the left side of the standard form [[equations\|Equation]] of a circle very easily: $(x-h)^2+(y-k)^2$ where $(h,k)$ is the center point
	- You can check if your standard form equation is correct by expanding it back intro general form
### Problem 1
- Key points:
	- Use the [[Distance]] formula to ensure you get the right radius
	- make sure you [[Perfect Squares\|Square]] the radius in the standard form equation
![[Files/Pasted image 20240731132016.png|300]]
- The center is $(2,3)$ and the equation of a circle js the distance formula/[[Pythagorean Theorem]]
	- We have to have $(x-2)^2+(y-3)^2=r^2$. To find what $r$ is js use the distance formula for $(2,3)$ and $(8,11)$
	- $\sqrt {(2-8)^2+(3-11)^2}=10$ so the radius is 10. 
	- If we plug in $10$ for $r$ in $(x-2)^2+(y-3)^2=r^2$ we get:
		- $(x-2)^2+(y-3)^2=100$ so the answer is $B$ 
### Problem 2
- Key points:
	- when completing the square insure that you:
		- Add the value that "completes the square" like this: $\left( \frac{b}{2a} \right)^2$ -> This ensures you don't mess up. Sometimes I accidentally do $\frac{\frac{\frac{b}{a}}{2}}{2}^2$ which makes no sense but it happens
		- Add $\left( \frac{b}{2a} \right)^2$ to both sides -> If you don't add to both sides, you're equation is js gonna be false!
![[Files/Pasted image 20240731132348.png|400]]
- This is a general form [[equations\|Equation]], lets [[completing the square\|complete the square]] for this problem
	- $x^2+y^2-14y-51=0$ 
		- $x^2+y^2-14y=51$
		- $x^2+y^2-14y+\left( -\frac{14}{2} \right)^2=51+\left( -\frac{14}{2} \right)^2$
		- $x^2+(y-7)^2=10^2$  -> we get $10^2$ by doing $51+49$ and the [[radius]] of the circle equation is [[Perfect Squares\|Squared]]
	- The $x$ coordinate has to be $0$ and the $y$ coordinate has to be $7$. 
	- Our answer is $D$ 
### Problem 3
- If you have the center [[point]] of the circle you can find the left side of the standard form [[equations\|Equation]] of a circle very easily: ${} (x-h)^2+(y-k)^2 {}$ where $(h,k)$ is the center point
![[Files/Pasted image 20240731132805.png|300]]
- The center is $\left( \frac{1}{2} , -\frac{2}{3} \right)$ this means we can find the left side of the standard form with relative ease:
	- $\left( x-\frac{1}{2} \right)^2+\left( y+\frac{2}{3} \right)^2=r^2$ 
	- to find $r$ find the distance between $\left( \frac{1}{2},-\frac{2}{3} \right)$ and $\left( 0, \frac{5}{6} \right)$ 
	- $\sqrt {\left( \frac{1}{2}-0 \right)^2+\left( -\frac{2}{3}-\frac{5}{6} \right)^2}=\sqrt \frac{5}{2}$
	- So plugging in $\sqrt {\frac{5}{2}}$ for $r$ gives us: $\left( x-\frac{1}{2} \right)^2+\left( y+\frac{2}{3} \right)^2=\frac{5}{2}$ so our answer is $A$ 

### Problem 4
- Key points
	- You can check if your standard form equation is correct by expanding it back intro general form
![[Files/Pasted image 20240731134644.png|300]]
- We are given a general form equation 
	- $x^2+y^2-12x-10y+36=0$
	- We group the $x$ and $y$ terms and subtract $36$ from both sides 
	- $x^2-12x+y^2-10y=-36$ 
		- Add the terms that "complete the square" 
	- $x^2-12x+\left( -\frac{12}{2} \right)^2+y^2-10y+\left( -\frac{10}{2} \right)^2=-36+\left( -\frac{12}{2} \right)^2+\left( -\frac{10}{2} \right)^2$ 
		- Complete the square!
	- $(x-6)^2+(y-5)^2=25$ 
		- Recall that the equation for a circle is:
	- $(x-h)^2+(y-k)^2=r^2$ 
		- The radius for this one will be 
	- $5$
		- In addition we can check our answer to make sure it's correct, we do this by expanding our current equation and turning it into general form.