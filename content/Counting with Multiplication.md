---
{"publish":true,"created":"2024-11-21T06:17:23.000-05:00","modified":"2025-08-17T17:05:19.505-04:00","cssclasses":""}
---

#math/Probability_Permutations_Counting 
Connections: [[Counting]], [[counting permutations]]

### Points
- To find how many possible combinations there are for something, we use [[Multiplication]] to represent possible outcome
- having x choices in the first choice, then y choices in the second choice, leads to x times y since if you choose an x, there are y choices you can have, so you have y times x choices
![[Files/Images/Counting with Multiplication 2024-03-20 19.30.29.excalidraw\|100]]
In this diagram, there are 2 choices at the start, then 3 choices. You can see there are 6 points at the end, two groups of 3.

When activities are not dependent on each other, meaning that they are independent and don't affect each other, to find the number of combinations, just multiply it all together. Try to visualize the graph in your mind or just draw it out, and it will make sense.
### Problems
##### Part 1

A man has 4 shirts, 3 pairs of shoes, and 5 hats. How many possible combinations are there for him.
He has 4 available choices for shirts, for every shirt he picks, there are 3 pairs of shoes. So there is $4*3$ combinations of shirts and shoes, and he also has 5 hats, so he has $4*3*5$ which would be 60 possible combinations.

Diagram of the problem:  
![[Files/Images/Counting with Multiplication 2024-03-22 07.19.48.excalidraw\|200]]
The dots represent shirts, the white lines represent shoes, and the red lines represent hats. 1 shirt, you pick 1 shoe from 3, and you pick 1 hat from 5, allowing for 60 combinations.


##### Part 2

this guy was wondering what he does every day, and if it's the same thing over and over again.

- He wakes up
- He does some work on the garden
	- There are 4 different areas that he could clean up
	- 5 different areas where he could mulch and put stuff down for the plants
- He then walks the dog, he can take the dog on one of 3 trails

This would be $4*5*3=60$

- He then has breakfast
	- He picks one of 3 different kinds of fruit
	- He then picks one of 4 different cereals
This would be $4*3=12$

- He then deals with his correspondence, phone calls, messages, that kinda thing
	- First deals with private messages, usually has around 5, and he only answers one
	- Then he usually has 2 phone calls, he has time to answer only one
	- He then has 20 emails, he usually answers all but one, which means out of 20, one will be left unanswered
This would be $5*2*20=200$

- After correspondence, he goes to his studio to make short math lessons
- he usually has 12 lessons figured out, and he has to pick one to shoot
- He also has to pick a shirt, he has 9 shirts
This gives $12*9=108$ combinations to choose from.

- It's then lunch time
- 4 main courses to choose from
- 2 drinks
- 12 desserts
$4*2*12=96$ ways to do lunch

He then goes on to do this for the rest of the day, and says, "how many different days can I have?"

Since each activity is independent, how should we do this? 
- What he eats for breakfast doesn't affect what what he has for lunch
- Because each activity is independent, we just multiply each thing, $60*12*200*108*96$
- 60 ways to start his morning, 12 breakfast options, 200 correspondence options, 108 studio work things, and 96 ways to do lunch
