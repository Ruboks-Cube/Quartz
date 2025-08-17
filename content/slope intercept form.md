---
{"publish":true,"created":"2024-11-21T06:17:33.000-05:00","modified":"2025-08-17T17:05:39.591-04:00","cssclasses":""}
---

#math/graphing #math/algebra #math/geometry, [[Cartesian coordinate system]], [[slope]], [[intercept]]


# What is Slope Intercept Form?

# Problems

## Key ideas
- The [[intercept\|Intercepts]] can help with graphing
- [[Why multiplying slope by x gives us y\|Why changing x by 1 changes y by slope]]
- $y=mx+b$ is called slope intercept form, where $m=$slope and $b$ is the [[intercept\|y intercept]] It's very useful
	- We know $m$ is slope because we know [[Why multiplying slope by x gives us y]]
	- We know $b$ is the [[intercept\|y intercept]] because when $x=0$ we're left with $b$ so $b$ MUST be the $y$ intercept
	- [[parameterization]]

## 8.18, finding out a new, useful form!
- We can find some [[intercept\|intercepts]] and discover another useful form to express our [[line\|lines]].
![[Files/Images/Pasted image 20240618104515.png]]
- (a) Let $x=0$, $x=1$, and $x=2$, we find 3 points on the line: ${} (0,-7) {}$, $(1,-4)$, and $(2,-1)$. We could, of course, find many many many other points on the line.
- (b) Using 2 of these points we find that the slope is $3$... [[Calculating Slope]]
- (c) The [[slope]] is $3$, and the [[Coefficient]] of $x$ in the given equation is ALSO 3, is this a coincidence??? Maybe... Maybe not ;)
- (d) The [[intercept\|y intercept]] is the point where the line meets the $y$-axis. Points on the $y$-axis have $x$ values of $0$. If we let $x=0$ in our equation we get $-7$ for $y$. This means that the $y$intercept is $-7$. Notice how THAT matches with the [[constant]] in the equation... 
	- ! [[intercept\|Intercepts]] are just points, so they can be referred with an [[ordered pair]]. Sometimes they can just be referred to with the coordinate that does matter, like the y intercept for this one is $-7$. 
- (e) The $x$-intercept is where the line meets the $x$-axis so the $y$ coordinate has to be $0$. Solving the given equation for when $y=0$ gives $x=\frac{7}{3}=2 \frac{1}{3}$. This means that the $x$ intercept is $\left( 2 \frac{1}{3},0 \right)$ Writing this as an [[improper fraction]] makes finding the point itself on the [[Cartesian coordinate system]] WAY easier.
- (f), we've found 2 points (the intercepts) so we can just graph it! ![[Files/Images/Pasted image 20240620121405.png]]
## 8.19, finding out what slope intercept form is fr
- In the last problem, we found that the coefficient for $x$ in the [[equations\|Equation]] form $y=mx+b$ matched with the slope, and that $b$, the [[constant]] matched with the [[intercept\|y intercept]]. Is this a coincidence?
![[Files/Images/Pasted image 20240620121537.png]]
- ~ solution
	- the [[slope]] of a [[line]] measures how much $y$ changes as $x$ changes. From $y=mx+b$ we know that increasing $x$ by $1$ increases $y$ by $m$. [[Calculating Slope]] 
		- EG slope is $\frac{1}{3}$ when $x$ changes by $3$ $y$ changes by $1$ so when $x$ changes by $1$ $y$ changes by $\frac{1}{3}$. We see that if $x$ changes by $1$ $y$ just changes by the SLOPE
	- ! [[slope]] is just the ratio of change of $y$ to change of $x$ ✨
	- $ MY EXPLANATION:
		- ? how do we know multiplying the slope by $x$ gives us $y$
			- [[Why multiplying slope by x gives us y]] --I like this explanation, the book tries to prove [[using algebra]] that $m$ is slope so I'll also go over that
		- ? how do we know "$b$" is the [[intercept\|y intercept]]
			- We know that the $y$ intercept is when $x=1$ and when $x=1$ in $y=mx+b$ the $mx$ is just $0$, leaving us with $b$, the $y$ intercept 😎
	- ! Book Explanation
		- The slope of a line measures how much $y$ changes as $x$ changes. In $y=mx+b$ we see that changing $x$ by $1$ changes $y$ by $m$ because [[Why multiplying slope by x gives us y\|The slope is a ratio and trying to find the unit rate just gives us the ratio again leaving us free to multiply by any scale factor we want]]. 
		- This means that the change in $y$ divided by the change in $x$ is $\frac{m}{1}$ ($y$ changes by $m$ while $x$ changes by $1$). 
		- The book addresses the $b$ being [[intercept\|y intercept]] the same way I did
- The form $y=mx+b$ is called slope intercept form of a [[line]]
## 8.20 
![[Files/Images/Pasted image 20240622174743.png]]
- (a) We can find the slope by finding 2 points on the equation and then [[Calculating Slope]] OR we can do the cooler way and convert the [[equations\|Equation]] into slope-intercept form
	- We do the latter by [[solving multi variable equations in terms of another variable\|Solving the equation in terms of x]] which gives: $y=\frac{3}{5}x-\frac{7}{5}$
	- From this equation we can easily see that the [[slope]] is $\frac{3}{5}$.
	- ! Always be on the lookout for ways to rearrange [[equations\|Equations]] into more convenient forms. EG when trying to figure out the slope of a line slope-intercept form makes it very very easy.
- (b) the slope is negative of the [[Ratio]] of the [[Coefficient]] of $x$ to the [[Coefficient]] of $y$. $-\frac{3}{-5}=\frac{3}{5}$.
	- This is not at all a coincidence, and we're gonna prove why
		- ? Me trying to figure it out:
			- We know that this [[standard form for 2 variable linear equations\|Standard form]] is just a rearranged form of the slope intercept form, and that it shows the equation in an [[Inverse Proportion]]
			-  Slope is difference of y over difference of x
			- Why don't I just try proving it [[using algebra]] huh? 
				- $Ax+By=C$ (we let $A$ and $B$ represent [[Coefficient]] of $x$ and $y$ respectively and they don't equal 0 and $C$ just represents some [[constant]])
				- Solvin' (slang hahahaha or what idk) the equation for $y$ gives:${} y=-\frac{A}{B}x+C {}$ and $-\frac{A}{B}$ HAS to be slope since if we multiply $x$ by it it gives $y$ just like how any other slope intercept form works
			- ? Is there a way to understand intuitively though?
			- We notice that we're basically [[substitution\|substituting]] $A$ and $B$ for the different differences. We have $y=\frac{{y_{1}-y_{2}}}{x_{1}-x_{2}}x+b$ and we can turn it back into standard form. $(x_{1}-x_{2})y=(y_{1}-y_{2})x+b$ which turns into $-(y_{1}-y_{2})x+(x_{1}-x_{2})y=b$   
			- Here's a mouthfull: The negative difference of y's times $x$ plus the positive difference of the x's times $y$ gives us $b$, the $y$ intercept. 
			- This is kind of making sense, the difference of $y$'s and the $x$'s will always be the same (they are taking the simplified version always since thats what the slope does). If $x$ increases by 1, $y$ increases by slope
			- ! Nope I'm not doing this
		- ! Book explanation
			- Ok all the book does is gimmie a hint
			- It says to note that if $B$ *does* equal 0 we're left with $Ax=c$. This line has a [[0 slope and undefined slope\|undefined slope]] since the left side will always equal $c$ so $x$ will always be the same thing so the denominator in the slope formula is 0 so it's undefined
			- Also, $C$ is supposed to be the $y$ intercept? But how will there ever be a $y$ .
			- intercept if the vertical line isn't on the $y$ axis itself.
			- Taking a look at if $A=0$ we're left with $By=c$ and this is when it's [[0 slope and undefined slope\|0 slope]] since there is a horizontal line. #revisit  
			- random stuff: ![[Files/Images/slope intercept form 2024-06-26 07.11.04.excalidraw]]
## 8.21
![[Files/Images/Pasted image 20240622181700.png]]
- ! my thinking
	- I'd find the equation of the lines too even though I read it first
		- We have a slope and a point so for one of them we have $(15)=5(10)+b$,  solving for $b$ gives $15-50=-35=b$. We find the $x$ intercept of this line by just plugging in when $y=0$ since *thats what the x intercept is*. We have ${} 0=5(x)-35 {}$ and $x=7$. --Make sure you do [[Inverse Operation]] correctly I did it wrong twice and it saved me
		- For the other one with slope 3 we have $y=3x+b$, plug in the point we have to get $b$ and we get $15=3(10)+b$ so we have $-15=b$. Plug in 0 for $y$ and solve for $x$ to get $0=3x-15$ which gives $x=5$. One of them is $7$
		- 3one of them is $5$ so the distance is 2
- ~ Solution 1, find the equations of the lines
	- It's basically what I did but I'll go over what they said anyway
	- The line with slope $3$ and passes through $(10,15)$ is $y-15=3(x-10)$ or $y=3x-15$. The $x$ intercept of this line is when $y=0$ which would give us $0=3x-15$, solving for this gives us $x=5$ when $y=0$ so our $x$ intercept is $(5,0)$ 
		- Above we immediately go from $\frac{{y-15}}{x-10}=3$ to the above equation, just a faster way of [[finding an equation of a line]]
	- Similarly, the line with slope $5$ passes through $(10,15)$ is $y-15=5(x-10)$ or $y=5x-35$, Setting $y=0$ we find that the $x$ intercept of this line is $(7,0)$. The distance between our [[intercept\|Intercepts]] is $2$
- ~ Solution 2, use the slopes
	- The $x$ intercepts are when the line crosses the $x$ axis. To get to the $x$ axis from $(10,15)$ we have to go down $15$. The [[slope]] is just $\frac{{\triangle y}}{\triangle x}$. So as the line with slope $3$ goes down 15 from $(10,15)$ we have $\frac{{-15}}{\triangle x}=3$. 
		- Therefore, the change in $x$ is $-5$ (find this by [[Solving Linear Equations\|Solving the linear equation]]). This means that when $y$ goes down by $15$ $x$ goes down  by $5$, starting from the point $(10,15)$ and subtracting 15 from $y$ and $5$ from $x$ the [[intercept\|x intercept]] is $(5,0)$
	- Similarly, the line with slope 5 goes $15$ units downward from $(10,15)$, we have
		- $\frac{-15}{\triangle x}=5$
	- The line with slope $5$ goes left $3$ as it goes down $15$. This means the [[intercept\|x intercept]] must be $(7,0)$ when we subtract the values from $(10,15)$. 
	- ! Understanding what [[slope]] and [[intercept\|intercepts]] are can help you come up with less algebraic solutions
## 8.22 
![[Files/Images/Pasted image 20240626075201.png]]
- ~ Solution 
	- We know how to tell if $3$ points are in a straight line from [[Graphing Linear Equations#8.12\|problem 8.12]], the slope of the first and second point must equal the slope of the first and third. We have to find a way to write the location of the runners as coordinates.
	- We use their lanes for $y$ coordinates (we could also do $x$). We let $t$ be the desired time (when all of them are in a straight line). After $t$ seconds Jon is at $(3t,1)$, his lane is 1 and he's moved $3t$ meters. Similarly, Laura is at $(4t,2)$. Ellis has moved $6t$ meters but he started 100 meters down the track at $(100,4)$. He runs back towards Jon and Laura a total of $6t$ meters. Therefore, he is at $(100-6t,4)$
	- Now that we have the coordinates of our runners so we can find the required slopes:
		- Slope between Jon and Laura:
			- $\frac{{2-1}}{4t-3t}=\frac{1}{t}$
		- Slope between Jon and Ellis: 
			- $\frac{3}{100-9t}$
	- In order for them to be in a straight line, the [[slope\|slopes]] must be equal so we have $\frac{1}{t}=\frac{{3}}{100-9t}$. We multiply both sides by $(100-9t)t$ to get $100-9t=3t$. This gives us $t=8 \frac{1}{3}$ seconds. 
	- So after $8 \frac{1}{3}$ seconds they are all in a straight line with same slope and everything.
	- A key step to solving this was to write the $x$ coordinate in [[solving multi variable equations in terms of another variable\|terms]] of another [[variable math\|variable]]. This is called [[parameterization]]
## 8.5.7 practice problem
![[Files/Images/Pasted image 20240626124238.png]]
- ~ Me tryna find a solution:
	- This can be a formula, we let $y$ be the number of her code, $m$ be her favorite number, and $b$ be her mothers favorite number:
		- $y=mx+b$ ($x$ is just the original letter placement)
		- From this, we know 2 things are true, $65=6m+b$ and $177=20m+b$
	- Now this is just a [[system of equations]] and we can solve with substitution. have $b=65-6m$ and $b=177-20m$. So $65-6m=177-20m$. 
	- $-112=-14m$. 