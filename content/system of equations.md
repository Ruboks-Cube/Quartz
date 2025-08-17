---
{"publish":true,"created":"2024-11-21T06:17:34.000-05:00","modified":"2025-08-17T17:05:42.931-04:00","cssclasses":""}
---

#math/algebra/inequality/equations , #math/algebra , [[Linear Equation]], [[2 variable linear equations]]

- A system of equations is when we have a group of [[multi variable equations]] and we want to find a solution or [[ordered pair]] that is a solution to all equations.

- There are 2 main ways to solve systems, (3 if you count trial and error one)
	- [[substitution#Substitution in system of equations\|substitution]]
	- [[Elimination]]
		- [[Elimination#Why it works\|Why Elimination WORKS]]
[[Types of solutions in system of equations]]
- [[More than 2 equations in a system of equations]]

# Problems
## How do we create a system of equations problem?
- Making a problem for a system of equations with only 2 [[Linear Equation\|equations]] seems easy enough, but what about when there are 3? What has to happen?
	- How do we find the equations of 3 lines that intersect at the exact same [[point]]. 

- First, lets think about 2 equations, maybe that will help us with 3
	- Lets think about this in [[slope intercept form]]
	- We want the solution to be (3,1)
	- We have 2 [[equations\|Equations]] $1=m(3)+b$ and $(1=m_{1}(3)+b_{1}$
		- We can make the [[slope]] be anything we want for the first 2, and then solve for the [[intercept\|y intercept]].
		- We can also do it the other way around
## An advanced practice problem
![[Files/Images/Pasted image 20240428133108.png]]
- We start by organizing the information, putting all the variables on one side and the constants on the other, we have:
		- $5x-2y=12$
		- $3y-9x=-22$
	- Solving for one variable looks messy, but we can multiply the first equation by $3$ and the second by $2$ so the $y$'s cancel out, we have
		- ${} 15x-6y=36 {}$
		- $-18x+6y=-44$
	- Add both to get $-3x=-8$
		- $x=\frac{8}{3}$
	- We plug in $x$ to either equation, we get $y=-\frac{2}{3}$
	- Our ordered Pair is $\left( \frac{8}{3},-\frac{2}{3} \right)$


## More than 2 variables?

### 5.16, 3 variables??????
![[Files/Images/Pasted image 20240429193525.png]]
- We know how to solve $2$ [[variable math\|variable]] systems, we can try eliminating the 3rd one through [[substitution]] or [[Elimination]] and solve a 2 variable one
	- Here are all of our equations:
		- $x+3y-4z=25$
		- $-2x+5y+7z=-66$
		- $3x-2y+3z=7$ 
	- We solve the first equation for $x$ giving:
		- $x=25-3y+4z$
	- [[Plugging in variables\|Plug this in]] to the 2nd and 3rd equations to get
		- $-2(-3y+4z+25)+5y+7z=-66$
		- $3(-3y+4z+25)-2y+3z=7$
			- Expanding then simplifying left side gives:
				- $11y-z=-16$
				- $-11y+15z=-68$
			- Adding these equations gives
				- $14z=-84$
			- Dividing by 14 gives
				- $z=-6$
			- Substituting $z$ in either of the $2$ equations gives $y=-2$
		- We substitute $y=-2$ and $z=-6$ in any of the $3$ original equations to get $x=7$
	- Our [[ordered pair]] is $(x,-2,-6)$

### 5.17 Without Substitution
![[Files/Images/Pasted image 20240429194639.png]]
- Substitution isn't the only way to convert a 3 variable equation into a 2 variable equation
	- We are unable to solve for a variable without introducing fractions, so we search for a way to eliminate a variable with [[Elimination]]
	- We focus on eliminating $y$ since all [[Coefficient\|Coefficients]] can be multiplied to $6$, we multiply the first one by 2, second one by 3
		- $4x-6y+12z=-24$
		- $15x+6y-24z=87$
		- $7x+6y+4z=49$
	- Add first two equations to eliminate $y$
		- $19x-12z=63$
	- Adding first and 3rd equation also eliminates $y$
		- ${} 11x+16z=25 {}$
	- these Two Equations form a system
		- $19x-12z=63$
		- $11x+16z=25$
			- Multiplying first equation by 4 and second by 3 allows us to eliminate $z$
				- $76x-48z=252$
				- $33x+48z=75$
				- $109x=327$
				- ${} x=3 {}$
			- Substituting this into $11x+16z=25$ gives
				- $z=-\frac{1}{2}$
		- Substituting $x=3$ and $z=-\frac{1}{2}$ into any of the original 3 equations gives $y=5$
	- $(x,y,z)$ is $\left( 3,5, -\frac{1}{2} \right)$

### 5.18 The Word Store
- Deleted due to my stupidity ✨

### 5.19, 4 variables, 1 equation
![[Files/Images/Pasted image 20240429203340.png]]
- We see that when substituting 0 for $x$ we are left with $B=D$, showing that $B$ and $D$ are equal no matter what
- This also shows that $A=C$ no matter what since both sides are just the same thing, it's like $Ax=Cx$ if we subtract $B$ or $D$ from both sides since they are the same thing, so we see that $Ax$ and $Cx$ are the same thing

# Graphing systems

## Key ideas
- When two lines on the [[Cartesian coordinate system]] - [[Intersect]] that is the solution for a [[system of equations]]. 
- ! If one equation can be manipulated to be the same as the other equation it is 
		1. A system with [[Types of solutions in system of equations\|infinite solutions]]
		2. The graph of the "2" equations is just the same
- ! If the lines have the same [[slope]] either they are the same line or are [[parallel]] since they have the same [[orientation]]. 
	- If they are not the same line they are a system with [[Types of solutions in system of equations\|No solutions]]
## 8.23, an introduction to graphing systems
![[Files/Images/Pasted image 20240627170907.png]]
- ~ Solution
	- The [[Graphing Linear Equations\|Graph]] of the 2 lines are shown:            ![[Files/Images/Pasted image 20240627170941.png]] 
	- We can see that $(1,-3)$ appears to be on both lines. We can [[checking your answer\|check our answer]] by [[Plugging in variables\|plugging in]] $1$ for $x$ and $-3$ for $y$ in both equations
		- $5(1)-2(-3)=11$
		- $-2(1)+3(-3)=-11$ 
	- Because $(x,y)=(1,-3)$ satisfies we see that $(x,y)=(1,-3)$ is the solution to both of our [[equations\|Equations]] and therefore the solution to our system of equations.
	- This is another way to solve a system of equations, but I don't think I will be using it much. However, this does help visualize the solutions for systems of equations, which is where I think the book is heading.
		- We see that both lines cross the point $(1,-3)$, and that $(1,-3)$ is a solution for both lines which is why it's the solution for our system.
## 8.24, [[Types of solutions in system of equations\|infinite solutions]]
![[Files/Images/Pasted image 20240627202649.png]]
- ~ Solution
	- We start by graphing $x-2y=7$:                                                                                                                                       ![[Files/Images/Pasted image 20240627202807.png]]
	- When we graph $3x=21+6y$ we see it's the EXACT SAME LINE! 
		- We see that $3x=21+6y$ is just $x-2y=7$ times $3$. The 2 equations are the exact same so they produce the same graph
		- They have the exact same solutions, and this system has [[Types of solutions in system of equations\|infinite solutions]]

## 8.25, [[Types of solutions in system of equations\|No solutions]] 
![[Files/Images/Pasted image 20240627200450.png]]
- (a) We write each [[equations\|Equation]] in [[slope intercept form]] to find the [[slope\|slopes]]. Our system becomes:
	- $y=\frac{3}{5}x+\frac{1}{5}$
	- $y=\frac{3}{5}x-\frac{4}{5}$
	- We see that the 2 lines have the same [[slope]], $\frac{3}{5}$. 
- (b) The [[line\|lines]] appear to never [[Intersect]]. We try to find their intersection point by [[using algebra]] through [[substitution]] or [[Elimination]] but that yields $1=0$. 
	- ! This [[equations\|Equation]] is never true, and does not have solutions
	- the system [[Types of solutions in system of equations\|has no solutions]]. This means that there is no [[point]] where the [[line\|lines]] meet so the lines are [[parallel]]. 
- (d) Inspired by this example we wonder if any 2 lines with the same [[slope]] must be [[parallel]]. We can analyze 2 non-[[vertical]] lines with the same [[slope]] by using [[slope intercept form]]. 
		- This form allows us to use the information that the slopes of the lines are equal. 
			- Let the slopes be $m$ and the [[intercept\|y intercepts]] be $(0,b_{1})$ and $(0,b_{2})$ respectively. 
				- $y=mx+b_{1}$
				- $y=mx+b_{2}$
			- We [[Elimination\|Eliminate]] both $x$ and $y$ from the system when we subtract the second [[equations\|Equation]] from the first. This leaves $0=b_{1}-b_{2}$
		- We have 2 possible cases
			1. *Case 1*: $b_{1} \neq b_{2}$
				- If $b_{1}\ne b_{2}$ then $0=b_{1}-b_{2}$ has no solutions
				- This means there is no [[ordered pair]] that satisfies both equations
				- The graphs of these [[line\|lines]] never meet, meaning they are [[parallel]]
			2. *Case 2*: $b_{1}=b_{2}$
				- This makes both of the equations the exact same leading to the same situation we have in this problem: [[system of equations#8.24, Types of solutions in system of equations infinite solutions\|Infinite solutions case]] [[system of equations#8.25, Types of solutions in system of equations No solutions]]
- The fact that 2 lines with the same [[slope]] are [[parallel]] or are the same [[line]] shouldn't be surprising
	- They have the same slope so they are [[orientation\|oriented]] in the same direction




## 8.26
![[Files/Images/Pasted image 20240702172140.png]]
- (a) The slope for the first one (${} x=-2y+10 \rightarrow y=-2x+10 {}$) is $-\frac{1}{2}$ while for the second (${} 2x-y=5 \rightarrow y=2x-5$) is $2$ 
	- My work:
		- ![[Files/Images/system of equations 2024-07-02 17.22.43.excalidraw\|200]]
- (b) The 2 lines are [[Perpendicular]] but Idk why 
- (c) When 2 lines have [[slope\|slopes]] that are the [[Negative Slope\|negative]] [[Reciprocal]] of each other they are [[Perpendicular]] -> [[perpendicular lines on cartesian coordinate plane]] 