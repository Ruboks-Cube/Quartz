---
{"publish":true,"created":"2024-11-21T06:17:34.000-05:00","modified":"2025-08-17T17:05:41.997-04:00","cssclasses":""}
---

#math/algebra #math/algebra/inequality/equations, [[Expression]], [[expressions with one variable]].

Substitution is a technique used a lot in [[algebra]], where we replace one thing with another thing, it is very powerful, and can turn complex things to simple things.


## Substitution in system of equations
We can use substitution to solve system of equations, showing how powerful it is

### Introductory problem
![[Files/Images/Pasted image 20240427101918.png]]
- We first solve $x+3y=4$ in [[solving multi variable equations in terms of another variable\|Terms of y]] to get $x=4-3y$
- We know that $x$ is equal to $4-3y$ so we plug that in the second equation to get $-2(4-3y)+5y=-30$
	- Now the second equation has only one variable
	- Solve the second equation
		- $-8+6y+5y=-30$
		- $y=-2$
	- Plug in our value for $y$ in any of the 2 equations, lets do the first one, $x+3(-2)=4$, solving gives us $x=10$
- Our ordered pair is $(10,-2)$
	- Additionally, we can check our answer by plugging in our values in each equation $10+3(-2)=4$, $10-6=4$ is correct
	- $-2(10)+5(-2)=-30$, $-20-10=-30$ is correct as well

### 5.4 practice problem
![[Files/Images/Pasted image 20240427103559.png]]
- We can choose which [[variable math\|variable]] in which [[equations\|Equation]]  we solve for
	- We do the $y$ in the second equation so we do not have to deal with fractions
	- $5x-y=9$
		- $-y=9-5x$
		- $y=-9+5x$
	-  plug this value into $3x-2y=7$ to get $3x-2(-9+5x)=7$ 
		- [[Distributive Property\|distribute]] $-2$ to get $3x+18-10x=7$ 
		- [[Combining Like terms\|Combine Like terms]] to get $-7x=-11$
		- divide $-7$,  $x=\frac{11}{7}$
	- Plug in $\frac{11}{7}$ into $5x-y=9$ to get $5\left( \frac{11}{7} \right)-y=9$
		- $\frac{55}{7}-y=9$
		- $55-7y=63$
		- $-7y=8$
		- $y=-\frac{8}{7}$
	

### 5.5 2 practice problems
![[Files/Images/Pasted image 20240428124903.png]]
- (a) We have 2 equations:
	- $3r+\frac{s}{2}=\frac{33}{2}$
	- $-\frac{5r}{2}-2s=\frac{37}{2}$
		- Simplify both equations first by multiplying by 2, this is to get rid of the fraction
	- Turns the equations to
		- $6r+s=33$
		- $-5r-4s=-37$
	- We solve the first equation in terms of $r$ to get $s=33-6r$
	- We plug this in our second equation
	- We plug $s=33-6r$ into $-5r-4s=-37$
		- This gives $-5r-4(33-6r)=-37$
		- We solve this equation to get $r=5$ EWW since now we know $\frac{95}{19}=5$ 🤮
		- We plug $r=5$ into any equation, lets to the first one
		- $6(5)+s=33$, which is $30+s=33$, $s=3$
	
		- We have our [[ordered pair]], $(5,3)$

> [!NOTE] Note
> You might be wondering what happens if we input  for  in the first equation, this will not help us since the  values will just cancel out, so don't do this
- (b) We start with organizing the equations to put all the variables on one side and the constants on another side
	- $1.2y+0.3x=0.93$
	- $2x-0.8y=1.8$
		- The easiest variable to solve for is x in the second equation, we have 
		- $x=0.9+0.4y$
	- Substituting this into our first equation gives $1.2y+0.3(0.9+0.4y)=0.93$
	- We solve this equation, giving ${} y=0.5 {}$
		- Plug in the value for $y$ for $x=0.9+0.4y$ to get $x=0.9+0.4(0.5)$
		- this gives $x=1.1$
	- Our [[ordered pair]]/solution is $(1.1,0.5)$