---
{"publish":true,"created":"2024-11-21T06:17:33.000-05:00","modified":"2025-08-17T17:05:39.011-04:00","cssclasses":""}
---

#math/geometry/2d/shape/Triangle #math/geometry/2d #math/geometry/2d/shape , [[Triangle]],[[similar]], [[2 dimensional]]
- Similar triangles have some interesting properties

- [[Area]]
	![[Files/Images/Pasted image 20240711223441.png|300]]
	- For a pair of similar triangles the [[Ratio]] of the [[Area]] of the triangles is the [[Perfect Squares\|Square]] of the ratio of the [[Line Segment\|sides]]. 
	- Prove "The ratio of the areas of two similar triangles is equal to the square of the ratio of corresponding side lengths."
		- $\frac{\triangle aABC}{\triangle aDEF}=\left( \frac{AB}{DE} \right)^2 = \left( \frac{AB}{DE} \right)^2= \left( \frac{AC}{DF} \right)^2 = \left( \frac{6}{2} \right)^2=9$
		- ![[Files/Images/similar triangles 2024-07-12 16.37.42.excalidraw]]
		- If we let $\triangle ABC$ represent a triangle with altitude $a$ and base $b$ the area of that one is $\frac{ab}{2}$!
		- If we let $\triangle A'B'C'$ represent a [[Triangle]] dilated by a scale factor of $m$ from [[preimage]] $\triangle ABC$ it has altitude ${} ma$ and base $mb$ 
		- The scale factor $m$ just represents the ratio of the [[Line Segment\|side lengths]] between the triangles because the ratio of the corresponding side lengths is the scale factor of the [[Dilation]]
- [[Perimeter]]
	- The ratio of the 2 [[Perimeter\|perimeters]] of 2 [[similar]]--[[Triangle\|triangles]] is equal to the ratio of their [[corresponding sides]]. 
	- Proof:
		![[Files/Images/Pasted image 20240712162804.png|diagram|200]]
		- $r=\frac{a}{d}=\frac{b}{e}=\frac{c}{f}$ -> defining [[Ratio\|Ratios]] (r) for the given [[Triangle\|Triangles]]
		- $rd=a,re=b, rf=c$ -> Cross multiplying 
		- $p_{1}=a+b+c$ -> Defining [[Perimeter]] for $\triangle ABC$ 
		- $p_{2}=d+e+f$ -> Defining [[Perimeter]] for $\triangle DEF$
		- $p_{1}=rd+re+rf$ -> [[substitution property of equality]]
		- $p_{1}=r(d+e+f)$ -> [[Factoring]]
		- $p_{1}=rp_{2}$ -> [[substitution property of equality]]
		- $\frac{p_{1}}{p_{2}}=r$ -> [[Division property of inequality]]