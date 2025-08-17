---
{"publish":true,"aliases":"finding the domain","created":"2024-11-21T06:17:24.000-05:00","modified":"2025-08-17T17:06:02.124-04:00","cssclasses":""}
---

#math #math/algebra 


- all the possible $x$ values for a [[function]]
	- Includes only [[Real Numbers]]
	- Undefined and [[Imaginary Numbers]] are not included
- You can find the domain for a function by first assuming ALL REAL NUMBERS then taking out numbers not part of the domain
	- We know that we get undefined if we have $0$ in the denominator
	- We know we get [[Imaginary Numbers]] if we have a [[Negative Number]] in a [[Radicals and Square Roots\|radical]]
- These 2 situations are called **Domain Busters**
	- If $x$ is in the denominator, solve for when the denominator will equal $0$, these are the numbers that are not part of the domain
	- If $x$ is in a radical, solve for when the radical equals $0$. From there you can go either direction, left or right on the [[Number Line]]
	- If the radical turns negative then you know that’s not a possible solution for $x$

## Problems

### Key points
- If variable in denominator solve for when denominator = 0
- If we have a radical we test the values either side of the solutions for when the values equal 0
	- We test for the **solutions for when the radical equals 0** 
	- We then test what’s **between our 2 solutions**
	- Then test for the **left side and the right side**
- When we have a radical in the denominator, it’s the same process for a normal radical but also the solutions for when it’s 0 does not work as well
### key points
- Whenever there is a [[Radicals and Square Roots\|radical]] and you’re trying to find domain, ALWAYS ALWAYS ALWAYS (Even if $x$ isn’t in radical) make sure that the radical is not imaginary
	- if it is it probably makes the whole function a [[Complex Numbers\|complex number]] (unless something cancels it out) 
### Problem 1, denominator
- Find the domain:
![[Files/Pasted image 20240908141029.png|200]]

- For this we see that we have $x$ in the [[Denominator]] 
	- We cannot allow the denominator to be equal to $0$ so lets search for when it is by setting $x^2-1$ equal to $0$
		- $x^2-1=0$ → This is a [[quadratic equations\|quadratic]] so lets factor 
			- $(x-1)(x+1)$ are our 2 factors
		- $x=1,-1$ are our solutions
	- When $x=1$ or $x=-1$ the denominator is $0$ so our solution is:
	- $R \space x\neq 1,-1$ the $R$ signifies all real numbers but the symbol when you write it will look like:
		![[Files/Domain 2024-09-08 14.14.23.excalidraw\|100]]



### Problem 2, radicals

- Find the domain:
![[Files/Pasted image 20240908141536.png|200]]
- For this, we see that we have $x$ in a [[Radicals and Square Roots\|radical]]
	- We know that if what’s inside the radical is equal to a [[Negative Number]] then that is not part of the domain
	- First start by solving when what’s inside the radical $=0$
		- $x^2-9=0$ (divide both sides by $-1$) 
		- $x=3,-3$ 
	- We can make a number line for the possible solutions, and test the numbers here is my work:
		![[Files/Domain 2024-09-08 14.18.13.excalidraw]]
	- ! There is basically $3$ zones we have to test for, well 4 actually
		- We test for the **solutions for when the radical equals 0** (in this case they are included cause if what’s inside the radical is 0, it’s still a solution ($\sqrt 0=0$))
		- We then test what’s **between our 2 solutions**, in this case $0$ is between $-3$ and $3$ → We see that $0$ is included so everything else is too 
		- Then test for the **left side and the right side**, we see that those are not included (the numbers I tested were $-4$ and $4$)
	- We write our solution in **Interval notation** → [[interval notation]], OR as an [[Inequalities\|inequality]] (my teacher prefers interval notation)
	- We have $x=\text{[-3,3]}$ since $-3$ and $3$ are both included 

### Problem 3, Radical inside denominator
- Find the domain for the following function 
$$
f(x)=\frac{2}{\sqrt{x^2+9x+20} }
$$
- Here we have a radical INSIDE the denominator meaning that when whats inside equals 0, they that value of $x$ will not be part of the domain
	- Start by solving for when $x^2+9x+20=0$
		- $(x+4)(x+5)$  which means $x=-4,-5$
	- Since $(x+4)(x+5)$ is simply just an easier form of the denominator [[Expression]], we can just replace that, so we have 
		- $\frac{2}{\sqrt {(x+4)(x+5)}}$ in the denominator
		- Our values are $-5,-4$, so we can test these values $\textcolor{red}{-6},-5,\textcolor{red}{-4.5},-4,\textcolor{red}0$ 
		- We already know that $-5$ and $-4$ are not included lets plug the rest into $\sqrt {(x+4)(x+5)}$ 
			- $\sqrt{(-6+4)(-6+5)}$ → this works
			- $\sqrt {(-4.5+4)(-4.5+5)}$ → This does not work
			- $\sqrt{(0+4)(0+5)}$ → This works
	- Our solution is $\text{(}-\infty,-5\text{]} \cup \text{[}-4, \infty \text{)}$ 

### Problem 4, multiple? 
- Find the domain for the following function
$$
f(x)=\frac{6}{\sqrt x^2 } 
$$
- You might see this and say, hey that simplifies to $\frac{6}{x}$ so the domain is ARN and $x\neq 0$
	- THIS IS WRONG
	- If variable is in radical and/or the denominator but the function can be simplified to not have one, you have to add on the domain of the un-simplified version too
	- If the domain changes along the way while you’re simplifying it, you add those too
- ? Why?
	- The original and the simplified version will have different graphs, and different domains based on the operations it has E.G:
		- This is graph of $\frac{6}{\sqrt x^2 }$:
		![[Files/Pasted image 20240919193608.png|200]]
		- This is graph of $\frac{6}{x}$:
			![[Files/Pasted image 20240919193713.png|200]]
	- Since taking the square root of a negative will not be part of the domain but it’s part of the function, we do that first
- The actual domain of this would be $(0, \infty)$ since 0 isn’t included either.
	
### Problem 5 a little bit impossible 
- Find the domain of the following function:
$$
f(x)=\frac{1}{x^2+3}
$$
- We see that we have $x^2+3$ in the denominator, so we solve for when $x^2+3=0$
	- We get $x=\sqrt {-3}$ 
	- What? We got an [[Imaginary Numbers\|imaginary]] solution 
		- This means that no real number for $x$ will make $x^2+3=0$, so the domain is just ARN, no more work

### Problem 6, even more impossible, radical
- If we have: $f(x)-\sqrt{x-2}$, $g(x)=x^2+9$ and $h(x)=\frac{1}{x^2}$
	- Determine the domain of $\frac{h(x)}{g(x)}-f(-1)$ WHY IS THIS PROBLEM BUILT LIKE THIS
	- Start with $-f(-1)$, this equals $-\sqrt -3$
	- Plugging in values for $h(x)$ and $g(x)$ we now have
	- $\frac{\frac{1}{x^2}}{x^2+9}-\sqrt -3$ using some rules we can figure out that this is $\frac{1}{x^4+9x}-\sqrt {-3}$ 
	- Wait a sec, this is easy
	- We have an [[Imaginary Numbers\|Imaginary number]] IN the function, this means that for any [[Real Numbers\|real number]] that we have for $x$, the imaginary number will always make that $y$ value a [[Complex Numbers\|Complex number]] (Not a real number!) which means that the domain for $x$ is NO DOMAIN 
	