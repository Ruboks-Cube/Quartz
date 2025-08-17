---
{"publish":true,"aliases":"#math/Probability_Permutations_Counting number of values in a list","created":"2024-11-21T06:17:23.000-05:00","modified":"2025-08-17T17:05:19.580-04:00","cssclasses":""}
---

#math/Probability_Permutations_Counting #tag #math/numbertheory 

Counting, 1,2,3. We can count the values of things.

Some things we can count are [[probability]], and the amount of possible values or [[counting permutations]]

Other topics in "counting"
[[Venn Diagrams with 2 categories]]
[[Counting with Multiplication]]
[[Factorial]]
[[counting permutations]]
[[with or without replacement]]
[[casework counting]]
[[Counting in Pairs]]
[[probability]]
#### Introduction To counting (lists)
##### Figuring it out
If we have a list like 1,2,3, ... ,20
How many numbers are in the list? You would say 20 right?

Now what if we have a list like this 73, 74, 75, ... , 121
How many numbers are in *this* list? 

There are 2 different strategies that we can use here. The first way is to do 121-73. What this does is give us the difference, or what we add to 73 to get us 121. The difference is 48, meaning if we add 1 to 73 48 times, we will get 121. This means that the numbers in the list are 49, because the difference of 48 doesn't count 73 in how many numbers there are in the list.

The other way to count this is to turn it into the previous list. How do we turn 73, 74, 75 into 1, 2, 3?

We subtract 72 from all the values, so now we have a list like this:
1, 2, 3, ... , 49. You can see here that both strategies give us the same answer, and that finding 121 - 72 gives us the answer, we do not count 73 by doing 121-73, so we subtract one to count for that as well.

Okay... So what if we have a list like this: 
-1.3, -0.3, 0.7, ... 201.7

We start from -1.3 and keep adding 1, so how many numbers are in *this* list?
We can again start by trying to convert this list into the easy, 1, 2, 3 list. We do that by adding 2.3 to -1.3, which gives us 1. Now add 2.3 to every other value and we get:
	1, 2, 3, ... , 204. And now we know that we have 204 numbers in this list?

But what about the finding the difference strategy? Does that work? 201.7- -1.3 gives us 201.7+1.3, which is 203. Again, 1 digit off. We add 203 to -1.3 to get 201.7, which is like adding 1 to -1.3 203 times, so there is 203 whole numbers between -1.3 and 201.7, add one more to count for the first number in the list (-1.3) and we get... 204! So both strategies work in this case. 

But I like the "turning this list into 1, 2, 3" strategy more because it's simply more intuitive in a problem like this, while the strategy of finding the difference is more intuitive in the first problem we did.




##### The formula

Lets say we have something like
a, a+1,a+2, ... , b
How do we make this into 1, 2, 3?

To turn a into 1, we just subtract 1 less than a which would be -(a-1)
-a+1, we're subtracting one less than a.

So if we do this to all of them, we would get 1,2,3, ... , b-(a-1)
And now we know that there will be $b-(a-1)$ numbers in this list.