---
{"publish":true,"created":"2024-11-21T06:17:23.000-05:00","modified":"2025-08-17T17:05:19.338-04:00","cssclasses":""}
---

#math/Probability_Permutations_Counting [[Counting]]


# Key Idea

# Problems

## AOPS as source:
### Party pairs of people
This guy had a party, and he instructed every person who was invited do bring someone with him. He wonders how many pairs of people there were, but everyone was already muddled in a group, so instead he counted how many people there were including himself and the person he brought. He counted 56 people. He then realizes he counted each pair exactly twice, so he fixes his overcounting by dividing by 2. This tells him that there are 28 couples.

Now, this guy also wants every person to high five every other person. What he does is instead of high fiving randomly, he makes people go in a row, like at the end of basket ball games. Then one person goes up and high fives everyone. He, being the host, gets to high five everyone first, and high fives everyone so he gets 55 high fives. Then he goes to sit down. Then, another person gets out of line, which brings the number of people in the line to 54, and then they run through high fiving everyone. Then, the next person gets out, and there are 53 people for them to high five. This keeps going on, until 4 people are left in the line. One of them get out, high five 3 people. Then 2 high fives, then 1 high five.

The total number of high fives would me $55+54+53+\dots+4+3+2+1$


We could add this up by just adding it up, use algebra, or you could even use a formula for it. (If you don't know a formula, I suggest you find one out.)


#### First Apparent Solution
n+(n-1)+(n-2)...+3+2+1
And now we see, we can do n+1+n+1+n+1+n+1, by rearranging everything.

There are 55 numbers in the list, which means that there is going to be exactly one number in the middle since 55 is odd, but each number has a pair.

Use the [[Median]] knowledge to know that 55/2=27.5, so the median will be 28.

So we know the middle number is 28.
So now it's 55+54+54+...+28+...+4+3+2+1

Since the middle number is 28, that means that there is 27 pairs of n+s=56, which means the expression would be $56*27+28=1540$.

#### The number 28
We know that 55+1, is 56. 56/2 is 28, which means there are 55 28's, which means that the sum of everything would be $55*28=1540$
#### Counting Solution
We can start to think how many high-fives each person got. 

Each person high fives 55 people. Meaning that, the first person high fives 55 people, then the next person high fives 54, but that person next also got 1 high five from the first person, bringing the total to 55.

There's 56 people, so if each person high fived 55 times, that would mean that would be $55*56$, however, this can't be the correct answer since we have 55 numbers in the list and every number is less than 55.

Well, lets think about it, when we high five someone, we count it once for us. But that person also high fives us, so we're counting each high five twice.

We have to divide by 2, so our actual expression would be $\frac{55*56}{2}$, which is the same as all the other solutions because of how [[Fraction\|Fractions]] work.
