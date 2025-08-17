---
{"publish":true,"created":"2024-11-21T06:17:26.000-05:00","modified":"2025-08-17T17:05:25.348-04:00","cssclasses":""}
---

#math/algebra , #math/geometry , #math/algebra/inequality/equations , [[Linear Equation]], [[algebra]], [[Geometry]], [[Cartesian coordinate system]], [[2 variable linear equations]], [[multi variable equations]] 

- ~ We know how to use the [[Cartesian coordinate system]] to graph [[ordered pair\|Ordered Pairs]], so lets try to draw whole [[equations]] on it.
	- When We plot all $(x,y)$ that satisfy an [[2 variable linear equations\|2 variable linear equation]] we get a **graph** of the equation.
		- ~ Note: We can also use "Graph" as a verb, which is "to produce a figure on the [[Cartesian coordinate system]] that represents a [[Linear Equation]]" 
	- ! In [[algebra#5. Multi Variable Linear Equations\|Chapter 5, multi variable linear equations]], we introduced [[2 variable linear equations]], now we learn why they are called "linear" 🤭

# Problems
[[slope\|Problem 8.7 tells us what slope is!]]
## Key Ideas
- [[slope]] is the constant ratio of the difference in y value to the difference in x value. [[Calculating Slope]]
- ! We cannot have $\frac{y_{2}-y_{1}}{x_{1}-x_{2}}$, we are finding the difference in the wrong order.
## 8.5

> [!warning] IMPORTANT
> The graph of an equation of the form $Ax+By=C$ where $A$, $B$, and $C$ are constants is a straight line.
- We know that all points will go in the same direction because if we solve the above in terms of $y$ we get $y=-\frac{a}{b}x+c$. If we take the point where $x=0$, we have $y=c$, so our ordered pair is $(0,c)$. If we take another point, where $x=d$, we have the [[ordered pair]] of ${} \left( d,-\frac{a}{b}d+c \right) {}$. To get from $(0,c)$ to $\left( a,-\frac{d}{b}d+c \right)$, we take $d$ steps to the right, and $-\frac{a}{b}d$ steps up. This is true for any value of $d$.
	- ! The point at which $x$ is $0$ is called [[intercept\|y intercept]]
- Graphing [[Linear Equation\|Linear equations]] is relatively easy, all we do is find at least 2 points that satisfy the equation, and connect them forming a [[line]]. 
- $ It's best to draw at least 3 points since this will reduce the number of errors, if 1 of the points do not go in the direction of the line, you did something wrong.
## 8.6 
![[Files/Images/Pasted image 20240526211827.png]]
- ~ Solution
	- We start by finding a few solutions, solutions where $x$ and $y$ are both [[integer\|Integers]] to make plotting easier. To find the solutions, we solve for $y$ in terms of $x$, [[solving multi variable equations in terms of another variable]].
	- We get $y=2x-6$. We can now build a table of solutions by choosing values for $x$. ![[Files/Images/Pasted image 20240527103615.png]]
	- $ These are the same points that [[Graphing Linear Equations#8.5\|Hopsalot]] visits in [[Graphing Linear Equations#8.5\|Problem 8.5]]. 
		- ? These points all lie in a straight line, but what about other solutions to the [[equations\|Equation]], are they in a straight line as well?
			- $ If we let $x=\frac{1}{2}$, and we plug it into $y=2x-6$ we get $-5$. This means our [[ordered pair]] is $\frac{1}{2},-5$. From the point $0,-6$, we took $\frac{1}{2}$ step to the right, $1$ step up, we made half the move that Hopsalot made, but it's still in the same direction! 
			- To go from $(0,-6)$ to $\left( \frac{1}{2},-5 \right)$ we move in the same direction as we do going from $(0,-6)$ to $(1,-4)$, so $\left( \frac{1}{2},-5 \right)$ is on the line as well. 
		- All the solutions to $y=2x-6$ are on this line:                                                                                                                                                      ![[Files/Images/Pasted image 20240527104347.png]]
		- ~ We can see why if we let $x=a$. If we have a value for $a$, our [[ordered pair]] will just be $(a,2a-6)$. This means that for any value of $a$, that is our ordered pair. So if we wanted to get from $(0,-6)$ to the point $(a,2a-6)$, we take $a$ steps to the right and $2a$ steps up. In other words, we make $a$ of hopsalots hops, $a$ hops going $1$ right $2$ up in the same [[Ratio]]. Meaning that the increase in $y$ is double the increase of $x$.
		- $a$ can be any number, a [[Fraction]], [[Negative Number]], anything. If we take $a$ is a [[Negative Number]], we just take the hops in the exact opposite direction. 
### Other examples
- We wonder if $y=2x-6$ is the only equation that creates a straight line. We graph similar equations: ![[Files/Images/Pasted image 20240527121932.png]]
	- In Each case, we see that the graph is a line. We can follow the same steps as we did in [[Graphing Linear Equations#8.6\|Problem 8.6]] to get a feel for why this is true
	- For example, when we solve $3x-y=4$ in terms of $x$, we get $y=3x-4$. If $x=0$, $y=-4$, so we have $(0,-4)$. This means that if $x=a$, which means each ordered pair would be $(a,3a-4)$. To get from $(0,-4)$, to $(a,3a-4)$, we take $a$ steps right and $3a$ steps up. All the moves are in the same direction. 

> [!warning] IMPORTANT
> The graph of an equation of the form $Ax+By=C$ where $A$, $B$, and $C$ are constants is a straight line.



## 8.7
## 8.7, introduction to the SLOPE! 
![[Files/Images/Pasted image 20240603192741.png]]
- ~ Solution
	- Start by solving the equation in terms of $y$, we get $x=2y+8$. We take any 2 points ![[Files/Images/Pasted image 20240603192837.png]] on a list we make and find the ratio. We find that it is always $\frac{1}{2}$, no matter what order they are in. 
	- We wonder if it's for any 2 points on the line. So we take the ratio between difference of $y$ and difference of $x$ to get $\frac{y_{2}-y_{1}}{x_{2}-x_{1}}=\frac{1}{2}$. We get this by plugging in $2y+8$ for the $x$ values, essentially just [[substitution]] and then simplify the thing to get $\frac{1}{2}$. 


## 8.11
![[Files/Images/Pasted image 20240603193409.png]]
- If we have $2$ points we know that we can easily graph the points but we only have 1 point. We have the slope here, and it's the difference of the $y$ values over the difference of the $x$ values. Since our slope is $-\frac{1}{4}$ we have $\frac{y_{2}-y_{1}}{x_{2}-x_{1}}=-\frac{1}{4}$. We can simply create another point. We can move from $(-3,1)$ $-1$ down and $4$ to the right. This gives us a second point, $1,0$ since we have $(x,y)$ so we add $4$ to the $x$ value and subtract $1$ from the $y$ value. 
- Here is the graph:                                                      ![[Files/Images/Pasted image 20240603193751.png]]

## 8.12
![[Files/Images/Pasted image 20240626081558.png]]
- ~ Solution
	- We start by naming the points so we can talk about them with more ease
		- $A=(32,5)$
		- $B=(24,18)$
		- $C=(22,21)$
		- $D=(17,29)$
	- We can check what points lie on the same line by checking the slopes. For example, if $A$ and $B$ have the same slope as $A$ and $C$, then $A$, $B$, and $C$ are all on the same line because A to C has the same [[Ratio]] of $\triangle y$ to $\triangle x$ as $A$ to $B$ so it must be on the same line. 
		- We need to compute some slopes, so whats wrong with this bogus solution: ![[Files/Images/Pasted image 20240626081912.png]]
		- When [[Calculating Slope\|Calcuting the slope of]] $\overline {AC}$ instead of doing $\frac{{y_{1}-y_{2}}}{x_{1}-x_{2}}$ we did $\frac{{y_{1}-y_{2}}}{x_{2}-x_{1}}$, we didn't keep it consistent so the slope will be wrong. We also never showed that $B$, $C$, and $D$ are actually on the same line, so we never finished.
	- ! **WARNING:** We cannot have $\frac{y_{2}-y_{1}}{x_{1}-x_{2}}$, we are finding the difference in the wrong order.
	- With this in mind, we compute the slopes of $A$ and every other point
		- [[slope]] of $AB$: $\frac{{18-5}}{24-32}=-\frac{13}{8}$
		- [[slope]] of $AC$: $\frac{{21-5}}{22-32}=-\frac{16}{10}=-\frac{8}{5}$
		- [[slope]] of $AD$: $\frac{{29-5}}{17-32}=-\frac{24}{15}=-\frac{8}{5}$
	- We see that the slope of $AC$ and $AD$ are the same, so $ACD$ must all be on the same line. 
## 8.13
## key ideas
- To find the midpoint between 2 points we take the [[Mean\|Mean/average]] of the $x$ and $y
s
	- We can check our answer by making sure the [[Distance formula\|Distance]] is the same

## 8.13, Finding the midpoint between 2 points
![[Files/Images/Pasted image 20240603200419.png]]
- (a)
	- Lets call the midpoint $M$, intuitively we can sort of see how the $x$ coordinate of $M$ would be the average between the $x$ coordinates. and for the $y
s it would be the average between the $y$ coordinates. We have $\frac{2-7}{2}, \frac{{4-2}}{2}= -\frac{5}{2},1$
	- Another way to see this is to draw a diagram to see why it's the [[Mean\|Average]] between the coordinates. Also note how there is a [[Triangle]], this will become very important really. ![[Files/Images/Finding the midpoint between 2 points 2024-06-06 21.11.29.excalidraw]]
	- We take half the distance between the $x
s and add it to the original $x$, same for the $y$. Here is the expression $x_{1}+\frac{x_{2}-x_{1}}{2}=\frac{x_{1}+x_{2}}{2}$. The difference of the $x$ divided by 2 and added to the original $x$ gives us the midpoint and the average of the $x$ also gives midpoint.
	- ! In order to confirm that this is correct, we have to confirm that $M$ is in $\overline {PQ}$ and that it is the same [[Distance formula\|Distance]] from $P$ as it is $Q$. We can use [[slope]] for the first task and the [[Distance formula]] for the second task
		- Lets get all the points in order first
			- We have that $M=-\frac{5}{2},1$
			- $P=2,4$
			- $Q=-7,-2$
		- Check the slope of $M$ and $P$
			- $\frac{{1-4}}{-\frac{5}{2}-2}$, this gives us $\frac{2}{3}$
		- Check the slope of $Q$ and $M$
			- $\frac{{1-(-2)}}{-\frac{5}{2}-(-7)}$, this gives us $\frac{2}{3}$ too
			- We now know that $M$ is on line $\overline {PQ}$ because it has the same slope, meaning that the difference in $y$ over the difference of $x$ is the same for $M$ for both $P$ and $Q$
		- We now have to check the distance between the points using the distance formula.
		- Check the distance between $M$ and $P$. 
			- $\sqrt {\left( -\frac{5}{2}-2 \right)^2+(1-4)^2}=\frac{{3\sqrt 13}}{2}$
		- Check the distance between $M$ and $Q$
			- $\sqrt {\left( -\frac{5}{2}-(-7) \right)^2+(1-(-2))^2}=\frac{{3\sqrt {13}}}{2}$
	- Therefore, $M$ is on $\overline {PQ}$ and is the same distance from $P$ and $Q$
- (b) 
	- since $PT:TQ=1:2$ we can think of $\overline{PQ}$ as having $3$ parts. So $PT=\frac{1}{3}$ of $\overline {PQ}$
	- $T$ is on $\overline {PQ}$ so it has the same slope, the only difference between $Q$ and $T$ in relation to $P$ is that $T$ takes a different number of "steps." 
	- We know $PT$ is $\frac{1}{3}$ the [[Distance formula\|Distance]] of $PQ$, so we take $\frac{1}{3}$ the number of steps. 
	- From $P$, $Q$ is 9 steps left, 6 steps down. (Hence there is a slope of ${} \frac{6}{9} {}$)
	- We take $\frac{1}{3}$ the number of steps left and $\frac{1}{3}$ the number of steps down to get to $T$.
		- to get to $T$ from $P$ we take $9\left( \frac{1}{3} \right)=3$ steps left and $6\left( \frac{1}{3} \right)=2$ steps down.
		- $P$ is $2,4$ so taking $3$ steps left and $2$ steps down gives us $-1,2$ 
	- We guess that $T=-1,2$
	- To know that our answer is correct, we must show that $T$ is on $\overline {PQ}$ and that $TQ$ is double length of $PT$
		- To show that $T$ is on $\overline{PQ}$, $\overline{PT}$ must have the same slope as $\overline {PQ}$, we check this and the [[slope]] is $\frac{2}{3}$ for both
	- Next, we take the distance formula and find $PT$ and $TQ$
		- First note down all the points
			- $T=-1,2$
			- $P=2,4$
			- $Q=-7,-2$
		- We then take the distance of $\overline{TP}$
			- $\sqrt {(-1-2)^2+(2-4)^2}=\sqrt {13}$
		- Take the distance of $\overline{TQ}$
			- $\sqrt {(-1-(-7))^2+(2-(-2))^2}=2\sqrt {13}$
	- As expected, $\overline{TQ}$ is double the distance of $PT$
		
