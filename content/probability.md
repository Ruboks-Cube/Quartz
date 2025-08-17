---
{"publish":true,"created":"2024-11-21T06:17:31.000-05:00","modified":"2025-08-17T17:05:35.191-04:00","cssclasses":""}
---

#math/Probability_Permutations_Counting [[Counting]]


# Key Idea 
Probability is the likelyness of something to happen. To calculate probability, you get the  number of possible desired outcomes over the number of possible outcomes.

# Problems

## 1 yellow face cube, intro to probability
There is a toy cube. 5 of the faces are blue while 1 of them are yellow. We want the probability (how likely something is to happen) for getting the yellow face after we toss it. To get the probability, we divide the desired outcome with the total amount of possible outcomes. 

We're making a [[Fraction]], and you can think of it as a [[Parts to a Whole]] fraction, almost like a ratio. The desired outcome is one part, while the total possible outcomes is the desired plus everything else. In this case we have $\frac{1}{6}$. Meaning that there is a $\frac{1}{6}$ or $16.5$% chance that we get the yellow face every time we throw and catch the toy cube.


> [!warning] Make sure you are counting the right thing
> Some people may say that the possible outcomes here are blue or yellow, so they would do 1/2 instead of 1/6, this is wrong since each face of the cube in this problem is a possible outcome.

## Probability of just having 1 yellow face
This guy has 6 squares. Each square has one face thats blue, and one face thats yellow. He can assemble a cube with these 6 squares. Whats the probability that when he assembles a cube he ends up with just 1 yellow face?

What are the possibilities here? There is a possibility of him having 0 yellow faces, 1, 2, 3, 4, 5, or 6. So there are 7 possibilities, meaning there is a $\frac{1}{7}$ chance for him to get only 1 yellow face.


> [!warning] THIS IS WRONG
> In this problem you have to think about each face since each face is an independent thing. The probability for getting 0 yellows is much lower than getting 1 yellow, since that 1 yellow face could be in any face of the cube.



> [!check] correct way:
> Each face is independent event.

Since there are 6 ways to build the 1 yellow face, we know the number of desired outcomes. So the question remains, what is the number of ways to build the cube? Each face has a 1/2 probability of being either blue or yellow. We have 2 "choices" which ties back to [[Counting with Multiplication]]. Each face is an independent event, 2 choices for the first face, 2 for second, 2 for third, and so on until the 6th face.

So we have 2^6 number of ways to build the cube. $2^6=64$, so we have 64 ways to build the cube.

Put our desired outcomes over possible outcomes and we get $\frac{6}{64}$ which simplifies to $\frac{3}{32}$ chance of 1 face being yellow.

Whats the probability of getting 2 yellow faces? 3? 4? This is an easy problem now that we know how to do the other problem. 6 choices for the first yellow face, then 5 for the second yellow face. 6+5=11 which gives us $\frac{11}{64}$

