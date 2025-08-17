---
{"publish":true,"aliases":"infinite solutions 0 solutions no solutions 1 solution","created":"2024-11-21T06:17:36.000-05:00","modified":"2025-08-17T17:05:44.450-04:00","cssclasses":""}
---

#math/algebra/inequality/equations , [[system of equations]], [[algebra]]
- there are 3 types of system of equations when there is a pair of [[2 variable linear equations]]

> [!Warning] IMPORTANT
> There are 3 main possibilities for when there is a pair of [[2 variable linear equations]]
> - No solutions, if the equations can be combined to produce an equation that is never true, such as $1=0$, then there is no solution for that system of equations
> - one solution, in this case, the equations can be manipulated to find unique values for the variables that satisfy both equations
> - Infinitely many solutions, if the equations can be combined to produce an equation that is always true, such as $0=0$, then the 2 equations have the same solutions (they are the [[equivalent]] equations)
> 

## 5.9, infinite and 0 solutions
![[Files/Images/Pasted image 20240428140131.png]]
- (a) we start by organizing the information
	- $-u+3v=8$
	- $-2u+6v=16$
		- simplify the second equation by dividing by 2 to get 
			- $-u+3v=8$
		- Uh oh! Both our solutions are the exact same, if we try to use [[Elimination]] we will get $0=0$, which is always true
	- We can solve the equation in [[solving multi variable equations in terms of another variable\|Terms of v]] to generate a formula, this is similar to what we did in [[2 variable linear equations#Introduction continued\|2 variable linear equations generating a formula]]
	- Our equation would be $u=-8+3v$, if we let $t$ represent $v$, we have $(-8+3t,v)$ for our solutions.
	- the variable $t$ is called a [[parameter]] here, we have a [[Functions in coding\|function]] where $t$ is the parameter, entering anything for $t$ gives us a solution for $v$ and $u$
- (b) We start by organizing AGAIN
	- $-r+2t=1$
	- $-2.5r+5t=7$
	- We get rid of decimal from second equation by multiplying by 2
		- $-5r+10t=14$
	- Multiply 1st equation by $-5$ to set up [[Elimination]]
		- $5r-10t=-5$
		- $-5r+10t=14$
	- Uh oh! When we add these equations, we get $0=9$, last time I checked this is not true
		- This happened because  on the left side we have $5r-10t$, (same left side just multiply by -1), and on the right side we have either $-5$ or $14$.
		- For this to be true $5r-10t$ would have to equal $-5$ and $14$ at the same time, there is no pair of $(r,t)$ that satisfies this

# The solutions and their graphs
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
# Graphing the systems
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