---
{"publish":true,"created":"2024-11-21T06:17:19.000-05:00","modified":"2025-08-17T17:05:12.740-04:00","cssclasses":""}
---

#math/geometry [[mathematical proofs]]

- most common form of proof used to prove geometric theorems
	- What we did in [[writing proofs#Introductory problem\|This problem]]
- Series of statements on left column
- Reason that each statement is valid in the right column 

# Problems
## [[2 column proofs]]
### Introductory problem
- Problems
	- Here: ![[Files/Images/Pasted image 20240703161035.png]]
	- $AB=CD$ -> Given
	- $AB+BC=CD+BC$ -> [[Addition Property of equality]]
	- $AB+BC=CD+DE$ -> [[substitution property of equality]]
		- $AC=AB+BC$ -> Segment addition
		- $CD+DE=CE$ -> Segment addition
	- $AC=CE$ [[substitution property of equality]]



### [[Straight angles\|Linear pair]] proving
- In an edmunten activity I saw that if 2 [[Angles]] form a linear pair then there is a [[Straight angles\|supplementary angle]]. This observation is called our Hypothesis 
- Linear Pair Theorem—If two angles form a linear pair, then the angles are supplementary.
- Figure:                                           ![[Files/Images/Pasted image 20240703163345.png]]
	- Let $\angle ADB$ and $\angle BDC$ represent a [[Straight angles\|Linear pair]] as shown in the figure -> given
	- $\overrightarrow{DA}$ and $\overrightarrow{DC}$ form a straight [[line]] -> Definition of linear pair
	- $\angle ADC=180^{\circ}$ -> definition of [[Straight angles\|Straight angle]]
	- $\angle ADB+\angle BDC=\angle ADC$ -> Angle addition
	- $\angle ADB+\angle BDC=180^{\circ}$ [[substitution property of equality]]
	- $\angle ADB$ and $\angle BDC$ are [[Straight angles\|supplementary angles]] -> Definition of supplementary
### [[congruent]] [[Straight angles\|supplements]] theorem
- Use another 2 column proof to prove that: 
	- If 2 angles are [[Straight angles\|supplementary]] to the same [[Angles\|Angle]] then the 2 angles are congruent
- ~ My try
	- $\angle CBA+\angle GHI=180^{\circ}$ and $\angle FED+\angle GHI=180^{\circ}$ -> given
	- $\angle CBA+\angle GHI=\angle FED+\angle GHI$ -> [[Transitive Property]]
	- $\angle CBA=\angle FED$ -> [[Subtraction property of equality]]
	- $\angle CBA$ is [[congruent]] to $\angle FED$
- ~ Edmentum way:
	- EDMENTUM ![[Files/Images/Pasted image 20240703164734.png]]
### Vertical Angles Theorem
- I have to prove vertical angles theorem ;( 
	- "Vertical angles are always congruent."
	- [[Vertical Angle]]
	- Here is an image to help you:                               ![[Files/Images/Pasted image 20240703175344.png|200]]
	- $\angle AED$ and $\angle BEC$ are [[Vertical Angle\|Vertical Angles]] -> given
	- $\angle AED$ and $\angle BEC$ are formed by [[Intersect\|intersecting lines]] -> definition of vertical angles
		- $\angle AED$ and $AEB$ form a [[Straight angles\|Linear pair]] -> Definition of linear pair
		- $\angle AEC$ and ${} \angle BEC {}$ form a [[Straight angles\|Linear pair]] -> Definition of linear pair
	- $\angle AED$ and $\angle AEB$ are supplementary
	- $\angle AEB$ and $\angle BEC$ are supplementary
	- $\angle AED$ and $\angle BEC$ are equal -> [[congruent supplements theorem]]
		- (Here $\angle AED$ is supplementary to $\angle AEB$ and $\angle BEC$ is also supplementary to $\angle AEB$ to they must be the same) 