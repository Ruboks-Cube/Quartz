---
{"publish":true,"created":"2024-11-21T06:17:36.000-05:00","modified":"2025-08-17T17:05:45.320-04:00","cssclasses":""}
---

#math/Probability_Permutations_Counting
Venn diagrams can be useful tools to help people who do math [[Counting\|Count]] values.
###### Relations
[[statistics]] - Working with data to find values, similar
### Example Problems
#### Houses with pets
This dude asked a person to go around the neighborhood, how many pets they have, and see who has pets, and who doesn't have pets.

This is the following information:
14 cats
19 dogs
6 both
5 neither (and no pets)
##### Diagram Solution


Lets make a diagram
![[Files/Images/using Ven Diagrams in math 2024-03-20 18.40.41.excalidraw]]
- The box represents EVERY house
- Outside the circles is where people without pets go
- The left circle is for people with cats, the right dogs
- In the middle is where people who have both go

- We know there are 5 people without dogs or cats
- We can't put people with cats or dogs yet since we don't know how many there are
	- 6 houses have both, so we can put that in the middle
![[Files/Images/using Ven Diagrams in math 2024-03-20 18.42.55.excalidraw]]

- We know that there are 14 cats in total, 6 houses have both cats and dogs, so 8 cats have only cats
- There are 19 houses with dogs in total, 6 have both cats and dogs, so there are 13 houses with only dogs
![[Files/Images/using Ven Diagrams in math 2024-03-20 18.47.02.excalidraw]]

- There are 8 houses with cats, 13 with dogs, 6 with both, and 5 with none, add all them up together and we get 32 houses in total, 27 pets

##### Subtraction solution
The fast way to do this would be to see that there are 14 houses with cats, and 19 houses with dogs.
14+19 = 33, but we count the houses with both twice, so we simply subtract 6 from 33 to get 27.
#### friends
- 42 friends
- 23 know math
- 21 are good looking
- 18 don't know math and are not good looking
How many of the good looking friends know math?

- 42-18 = 24, 24 friends are the friends that either know math, or are good looking

- Of this group 23 know math, which means 1 person of this group doesn't know math
- Of this group 21 are good looking, which means that 3 people of this group aren't good looking

- 3 people are only good at math
- 1 person is only good looking
- this leaves 20 people know math and are good looking

- we are able to make this information into an [[equations\|Equation]]
	- Here we are solving for the value "both" if "both" is x that means:
		- $18+(23-x)+x+(21-x)=42$
		- 18 + "number of people who are only good at math" + both + number of people who are only good looking = 42
		- We solve this [[Linear Equation]] to get our answer, 42

