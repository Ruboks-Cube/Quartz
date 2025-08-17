---
{"publish":true,"created":"2024-11-21T06:17:37.000-05:00","modified":"2025-08-17T17:05:54.981-04:00","cssclasses":""}
---

#math/geometry/2d/shape/Triangle/trigonometry [[Trigonometry]]

- When we have $\sin^2 C+\cos^2 C$ in [[How to solve a right triangle#Law of cosines\|Proving the law of cosines]], we simplify to 1. How does that happen? -> [[what sine^2(angle means)]]
	- Lets see why!
	- We take a [[Right Triangle]] with lengths, $a,b,h$ where $a$ represents the [[Line Segment\|side length]]--[[adjacent]] to [[Acute Angle]] $\theta$. $\overline b$ represents the side opposite and $h$ is the [[Hypotenuse]].  -> [[defining stuff in proofs]]
		![[Files/Images/why sin+cos of the same angle equals 1 2024-07-16 20.57.41.excalidraw\|200]]
		- $\sin \theta=\frac{b}{h}$ and $\cos \theta=\frac{a}{h}$
		- $\sin^2\theta+\cos^2\theta=\frac{b}{h}^2+\frac{a}{h}^2=\frac{b^2}{h^2}+\frac{a^2}{h^2}=\frac{{b^2+a^2}}{h^2}$ -> This is all just [[simplifying in math]] and using the [[adding fractions with different denominators\|common denominator]]. 
		- Now, $\frac{b^2+a^2}{h^2}=\frac{h^2}{h^2}$ due to [[Pythagorean Theorem]]. Try it out! $a^2+b^2=h^2$ and then [[substitution]]
		- $\frac{h^2}{h^2}$ just equals $1$ and there you have it.