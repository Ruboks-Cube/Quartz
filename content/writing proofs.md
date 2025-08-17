---
{"publish":true,"aliases":"algebraic proofs","created":"2024-11-21T06:17:37.000-05:00","modified":"2025-08-17T17:05:46.340-04:00","cssclasses":""}
---

#math/geometry #math/algebra #math 
 
 - [[math]], [[mathematical proofs]]


## What's a proof how do I write one
- When you write a proof you start with the given information that you can assume to be true.
	- Then you build statements to connect what you are given to what you have to prove [[using algebra]]
	- Each step is based on a reason, like a [[algebra#1. Follow the Rules\|Property in algebra]], [[Definition]], [[axiom\|Postulate]], or another [[Theorem]]. 
## Types of justifications
- Here are some basic properties used to justify [[math\|mathematical]] steps, many of these are so basic that you might think they don't even need names, but they have them:
	- [[Reflexive property of equality]]  
	- [[Symmetric Property of equality]]
	- [[Transitive Property]] -> 3 numbers
	- [[substitution property of equality]]
	- All the same thing
		- [[Addition Property of equality]]
		- [[Subtraction property of equality]]
		- [[Multiplication property of inequality]]
		- [[Division property of inequality]]
## Types of proofs
- there are 3 different types of proofs in [[Geometry]]
	- The most common is a [[2 column proofs\|2 column proof]]
	- The next is a [[flow diagram proof]]
	- The last is [[paragraph proofs]]


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

## Paragraph Proofs
### [[congruent]] [[Straight angles\|supplementary angles]] theorem
- We can state that if 2 angles are congruent and are [[Straight angles\|supplementary]] then they are both $90^{\circ}$ 
	- Image                                                                                                       ![[Files/Images/Pasted image 20240703190116.png]]
	- Lets try making a 2 column proof for this before a paragraph proof
		- $BAC+CAD=180$ -> Given + definition of supplementary
		- $BAC=CAD$ -> Given + Definition of [[congruent]]
		- $BAC+BAC=180$ -> [[substitution property of equality]]
		- $2BAC=180$ -> [[Combining Like terms]] 
		- $BAC=90$ -> [[Division property of inequality]]
		- $CAD=90$ 0 -> [[substitution property of equality]]
		- $BAC=CAD=90$ -> conclusion
- Here is the image they use in the proof: ![[Files/Images/Pasted image 20240703192904.png]]
- Let $\angle 1$ and $\angle 2$ be [[congruent]] and [[Straight angles\|supplementary angles]]. Since $\angle 1$ and $\angle 2$ are [[Straight angles\|supplementary]], $\angle 1 + \angle 2 = 180$ due to the definition of supplementary angles
	- Since $\angle 1$ and $\angle 2$ are [[congruent]] $\angle 1=\angle 2$. 
	- Through substitution we get $\angle 1+\angle 1=180$
	- By the [[Division property of inequality]] we have $\angle 1=90$
	- Since $\angle 1=\angle2=\angle 90$ through the [[Transitive Property]] of equality. 
	- Therefore by definition of [[Right Angle]] $\angle 1$ and $\angle 2$ are both [[Right Angle\|Right angles]]. 