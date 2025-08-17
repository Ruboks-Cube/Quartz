---
{"publish":true,"created":"2024-11-21T06:17:21.000-05:00","modified":"2025-08-17T17:05:16.794-04:00","cssclasses":""}
---

#math/Probability_Permutations_Counting  [[Counting]]
We know how to count how many choices, ways, or [[counting permutations\|Permutations]] we have, but what if we want to count how many ways we have to get from point A, to point B?

# Key Ideas
Casework counting is when we take a case that stays consistent and count how many possibilities are in that case. Most of the time there are more than 1 case, so we count all the case possibilities together.

The idea of casework counting is being as organized as possible, narrow down each case, but have as few cases as possible. How do you know which case you should do? You think of the thing that is most relevant in the problem, and base your case off that. In the introduction problem, the cases were x, y, z, since they were the ones stopping A from being a clean line to B. In the cube problem, the cases were each integer less than 10 since integers less than 10 were the only thing that could be less than $1000$. 

# Problems
## Introduction Problem
https://artofproblemsolving.com/videos/prealgebra/chapter14/186
![[Files/Images/Pasted image 20240326173519.png|300]]
How many ways are there to get from point a to point b?
At the start, we have 6 choices. Then we have 11 choices to get to B from X, Y, or Z.
So you might think that we can multiply 6 by 11. But you're wrong, since of those 6 choices, only 3 could go from x, only one could go from y, only 2 could go from z. So what we have to do is count each case individually.

The cases we have are x,y, z
3 choices at the start for x, then 2 to get to b, which gives us 6
1 choice for y, 4 choices to get to b after
2 choices for z, 5 choices to get to b after, gives us 10

Now we add 4, 10, and 6 to get 20

We are counting each case, for when we take x, y or z.

What we did here was casework counting, we listed out our cases, x y or z, and made sure that they did not overlap.
## Cubes
How many numbers less than 1000 can be written as a sum of 2 positive cubes? 

Instead of taking a number and seeing if it's a sum of 2 positive cubes, we can take the sum of 2 positive cubes and see if they are less than 1000.

First, what else do we know about the problem? What is the greatest sum? We know that nothing can be more than $10^3$, since $10^3=1000$, the next integer down is $9$.

$9^3=729$
$1000-729=271$
This means that the cube you add to $9^3$ must be less than 271.
$8^3$ is 512, so no
$7^3=343$, that doesn't work either
$6^3=216$, thats less than 271, and this also means that any number less than 6 works.

This means that $9+6^3$, ${} 9^3+5^3\dots {}$ $9^3+1^3$ all work.

What if we try 8?

$8^3$ is 512,  so $7^3\dots 1^3$ all work

$7^3$ is 343, $8^3$ and all numbers below work, however, this means that we count $8^3+7^3$ twice, so lets make each "case" the largest.

We have a case where 9 is the largest, 8 is the largest, and so on.

So for 7, $7^3\dots 1^3$ all work.

This is true for all the other numbers too.
$6^3\dots 1^3$, since now each number is starting to be less than the sum of itself cubed.

Now we count all of the sums altogether. We have 6 for 9, 7 for 8, then 7, 6,5,4,3,2,1.

Adding this gives us $6+7+7+6+5+4+3+2+1=41$, so we know that there are 41 sums of positive [[integer]] cubes that are less than 1000, all with casework counting.

## How many rectangles?
![[Files/Images/Pasted image 20240326181912.png]]
Here is a classic problem, that we can solve with casework counting.
The case in this problem could be the dimensions of the rectangle, and we can further each case by making it the height.

We start with 1 as the height/row
there are 9 1x1s
there are 6 1x2's
there are 3 1x3's
there is 1 1x4
there are no 1x5's (only 4 columns)
Total of 19 rectangles with 1 row

Then we can move onto 2
There are 5 2x1's
There are 3 2x2's
There is 1 2x3
Total of 9 rectangles with 2 rows

Then we move onto 3
There is 1 3x1
There are no 3x2's

Now we can count up all of them, and we get 29 rectangles.
## 3 digit Numbers

What is the number of 3 digit numbers that the average of the 1st and last digit of each number is the middle digit.

Which cases should we consider?

Lets think about the middle digit, since that's the special one, it's the average of the others. We consider the middle digit and see how many ways it could be the middle digit while also being the average of all the other digits.  What else we do to organize it even more is the first digit is 1, then 2, then 3 and so on.

![[Files/Images/casework counting 2024-03-26 18.48.13.excalidraw]]
count all them up and we get 45
