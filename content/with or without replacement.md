---
{"publish":true,"created":"2024-11-21T06:17:37.000-05:00","modified":"2025-08-17T17:05:46.170-04:00","cssclasses":""}
---

#math/Probability_Permutations_Counting 
[[Counting]]

# Key Idea

# Problems
## The liars club
This problem is quite hard to explain, so here's the actual source: https://artofproblemsolving.com/videos/prealgebra/chapter14/185

There is this new restaurant called the liars club. The liars club has this lottery system. What they do is they make people take 4 numbers from a basket, and if the 4 numbers are equal to the numbers on a ticket, they get a free meal. They take a ball out, there is a number written on it, they write it down, and then they put the number **back in**. This means a person can get 7777, or they can get all different numbers, 1234. Now, this is the *liars club*, so what they *actually* do is the owners have told their friends that the balls don't actually go into the basket. So what actually happens is that someone picks a number, writes it down, and *puts it aside* so the numbers do not get replaced. So the question is, how many useless tickets are there?

- The tickets have any number from 1-10, 4 times, meaning that there is $10^4$ different [[counting permutations\|Permutations]] for each ticket
	- It's important to note here that if the numbers were replaced, then the amount of combinations would also be $10^4$, but they are not
- Without replacement, they would have a choice of 10 balls, they pick 4, so using our knowledge from choices from the [[Counting with Multiplication]] we know it would be
  $10*9*8*7$, which would be equal to 5040
- $10^4$ or 10000 is the number of possible tickets, but of those tickets, only 5040 are actually useful, since any ticket with a repeating number would be considered useless, $10000-5040=4960$ tickets that are useless
And we're done!

Or are we???

Because if you look at the following expression $10000-5040$, you could see that 5040 is 7 factorial, and we got 5040 from doing $10*9*8*7$, so how did *this* happen? How could this be?

If we [[Prime factorization\|Prime Factorize]] this, we can rearrange the expression the be $7*6*5*4*3*2$, which is 7!

[[Factorial]]