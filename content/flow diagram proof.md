---
{"publish":true,"created":"2024-11-21T06:17:26.000-05:00","modified":"2025-08-17T17:05:24.878-04:00","cssclasses":""}
---

#math/geometry #math , [[writing proofs]]



- In a [[2 column proofs\|2 column proof]] statement 2 might imply statement 5 independently of statement $3$ and $4$. Taken together, statements $3,4$ and $5$ might imply statement $6$. 
	- This can make [[2 column proofs]] hard to follow
- Another proof for geometric theorems is a flow diagram proof, which lets you lay out the proof in a way that lets you follow the connections -> like obsidian!
- They use a series of boxes and arrows to prove something, arrows connect boxes in logical order and reasoning behind each connection is inside the box.
- EG: ![[Files/Images/Pasted image 20240703182314.png|300]]

# Problems
## Flow diagram
### Common [[Line Segment\|Segment]] theorem
- If $A,C,B,D$ are colinear points and $\overline {AB}= \overline {CD}$ then $\overline {AC}=\overline{BD}$

- We can compare a flow diagram to a 2 column proof
	- $\overline {AB}= \overline {CD}$ -> Given
	- $AB=CD$ -> definition of [[congruent]] [[Line Segment\|Line segments]]
	- $BC=BC$ -> [[Reflexive property of equality]]
	- $AB+BC=CD+BC$ -> [[Addition Property of equality]]
		- $AB+BC=AC$ -> Segment addition
		- $CD+BC=BD$ -> Segment addition
	- $AC+BD$ -> [[substitution property of equality]]
	- $\overline {AC}= \overline {BD}$
- Here is what the flow diagram looks like:
	- Image:                                                                    ![[Files/Images/Pasted image 20240703184600.png]]
