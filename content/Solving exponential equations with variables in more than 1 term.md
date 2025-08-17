---
{"publish":true,"created":"2025-04-05T13:25:19.000-04:00","modified":"2025-08-17T17:06:01.044-04:00","cssclasses":""}
---

#math/arithmetic/logarithm 


- How to do $4^x=11^{x-2}$?
	- [[solving exponential equations with change of base]] or [[solving exponential equations by getting them to have the same base]] doesn’t work here
	- Instead, we have to take the $\log$ or [[Natural Log]] of both sides YES WE CAN DO THAT → [[taking the log of both sides]] 
	- Lets take the natural log because its 1 less letter to write
- Example Problem:
	- $\ln 4^x=\ln 11^{x-2}$
		- $x$ is in the exponent of the [[argument log\|argument]] of the log
		- We can use our [[power logarithm rule]]!!!
		- so now we have ${} x\ln 4=(x-2)\ln{11}$
		- Then we can [[Distributive Property\|distribute]] the right side to get $x\ln 4=x\ln 11 -2 \ln 11$ 
			- LOOK LOOK THIS IS NOW A [[logarithmic equation\|LOGARITHMIC EQUATION]] (kindof)
		- Get all the variable terms on one side $x \ln 4 - x \ln 11 = -2 \ln 11$
		- [[Factoring\|Factor out the x]] to get $x(\ln 4 - \ln 11)$ 
		- You can then put $x=\frac{-2 \ln 11}{\ln 4-\ln 11}$ 
- Steps:
	1. Take [[Logarithm]] or [[Natural Log]] of both sides
	2. $x$ will be in the exponent of the [[parameter\|argument]], so you can take it out using the [[power logarithm rule]]
	3. Now you js have like a bunch of logs, some w/ $x$’s some without
	4. Put the ones W $x$’s on one side and one without on the other
	5. [[Factoring\|Factor out]] the $x$’s, divide the log [[term\|terms]] 
		- You *can* condense the log terms with [[product logarithm rule]] and [[quotient logarithm rule]] but i dont think you have to
	6. you SHOULD have $x={\frac{\text{log term}}{\text{log term}}}$ which you can put in the [[Using Ti-84+ calculator\|calculator]]