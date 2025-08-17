---
{"publish":true,"created":"2024-11-21T06:17:22.000-05:00","modified":"2025-08-17T17:05:53.923-04:00","cssclasses":""}
---

#math/geometry/2d/shape/circle , [[radian]], [[degrees]]

- How do we convert between degrees and radians?
	- first, always remind yourself what a radian is:
		- It's js the amount of [[radius\|radii]] that can fit in a given [[arc length]]
	- This means the amount of radians for the whole [[circumference]] of a circle is js $2\pi$ since $2 \text{ radii}$/$1\space\text{diameter}$ times $\pi$ is js the whole circumference
	- So this means that $2\pi \space \text{Radians}=360^{\circ}$ 
	- $1=\frac{360^{\circ}}{2\pi \text{R}}$
	- $1=\frac{180^{\circ}}{\pi \text{R}}$ → this is a [[Conversion Factors\|conversion factor]], multiplying by this number means multiplying by 1
- We have an angle $x^{\circ}$ that we want to convert to radians
	- $x^{\circ}*{\frac{\pi R}{180^{\circ}}}=\frac{x\pi R}{180}$, multiply so the [[degrees]] cancel out

- What is $60^{\circ}$ in radians?
	- $60^{\circ}*{\frac{\pi R}{180}}=\frac{1}{3}\pi R$
	- $\frac{1}{3}\pi$ Radians 
- 
