---
{"publish":true,"created":"2024-11-21T06:17:23.000-05:00","modified":"2025-08-17T17:05:21.517-04:00","cssclasses":""}
---

#math/geometry/transformation , [[Transformation]]

- Here:                                                                                                     ![[Files/Images/Pasted image 20240627101043.png|200]]

- Shrinking or growing figures. 
# Messing around with edmunten


- When you dilate something there is a [[Scale Factor]]. Much like how when you try to scale [[Ratio\|ratios]] there is a scale factor.
	- To make something bigger the scale factor has to be more than 1. 
	- To make something smaller the scale factor has to be less than 1
	- To make the [[image (transformation)]] same as the [[preimage]] the scale factor would be 1
- Multiplying the scale factor by the points of the [[preimage]] will give us the [[image (transformation)]]
- The [[Angles]] will stay the same because the whole figure is being scaled up or down, the angles do not need to change.

- The scale factor can also be [[Negative Number\|negative]]. ![[Files/Images/Pasted image 20240627104038.png]]
- If it is negative the resulting image would be the original multiplied by the positive scale factor and [[Rotation\|rotated]] $180^{\circ}$

# Explanation
- A dilation is a [[Rigid Transformations\|Non-Rigid]]--[[Transformation]] that produces an [[image (transformation)]] that is [[similar]] to the [[preimage]]. Dilation changes the [[size]] of the figure but leaves the [[2D shape\|shape]] as it is. 
- Any dilation is defined by 2 ideas
	- The [[Scale Factor]] $n$, which specifies the magnitude of the [[Transformation]]
	- a [[center of dilation]], $D$. 
- ! Mathematical [[Definition]]
	- The [[image (transformation)]] of $A'$ of any point $A$, dilated from point $D$, is on [[Ray]], $\overrightarrow{DA}$. 
	- The length of $\overline {DA'}$ is $n$ (the [[Scale Factor]]) times the length of $\overline {DA}$. ![[Files/Images/Pasted image 20240627104742.png|200]]

- A dilation preserves the [[Angles\|Angles]] of the [[preimage]]. 
- A dilation also preserves the [[slope]] of every [[Line Segment]] of the [[preimage]]
- When we have a figure, the length of the [[corresponding sides\|Corresponding line segments]]-> [[image (transformation)]] will be $n$ (the [[Scale Factor]]) times the [[preimage]]
	- ? The slope one kinda makes sense but why is this one true?
		My think: ![[Files/Images/Dilation 2024-07-10 16.54.21.excalidraw]]
	- We might be able to prove this but I'm not sure...
		- $(x_{1},y_{1})$ 
		- $(a_{1},b_{1})$  These are arbitrary points before a dilation
		- $(x_{2},y_{2})$
		- $(a_{2},b_{2})$ These are points after a dilation from an arbitrary [[center of dilation]] which we can say is $C(w,z)$
		- ![[Files/Images/Dilation 2024-07-10 17.02.20.excalidraw]]
	- $ OKOKOK WE CAN REALLY EASILY SEE IT!!! We have to use the [[Pythagorean Theorem]] to prove this!
		- We know that the distance between 2 points is just the [[Distance formula]]
		- When we have a scale factor ($n$) we have $(na)^2+(nb)^2=$something and we are trying to figure out if that something is related to $n$ and why the length of the [[Line Segment]] increases by a factor of $n$
		- So we have $a^2+b^2=c^2$
		- We can simplify our [[Expression]] ($(na)^2+(nb)^2$) to be $n^2a^2+n^2b^2$ which is $n^2(a^2+b^2)$.
		- We know that $a^2+b^2=c$ so the other side of our [[equations\|Equation]] must be $n^2(a^2+b^2)=n^2(c^2)$
		- And there is our proof, taking the [[Radicals and Square Roots\|square root]] of everything for the [[Distance formula]] will give us the original distance between our points times $n$.
	- [[Why the distance between 2 points after a dilation is the original distance times scale factor]]
		
	

- A practice problem:
	- IMAGE ![[Files/Images/Pasted image 20240627105132.png]]
	- Answer:
		- The [[Polygon]] was enlarged by a [[Scale Factor]] of $4$