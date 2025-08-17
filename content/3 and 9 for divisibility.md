---
{"publish":true,"created":"2024-11-21T06:17:19.000-05:00","modified":"2025-08-17T17:05:13.417-04:00","cssclasses":""}
---

#math/numbertheory  #math/divisibility #math/rule 


# Problem Example
Take this problem:

Find all values of A where 6A34 is [[Divisible]] by 9.

we found the rules for [[2, 4, 5, and 25 for divisibily]] by relating 2,3,5, and 25 to [[Exponents]]/powers of 10.
So, how is 9 related to powers of 10?

10, is one more than 9, 100, is 1 more than 99, 1000, is one more than 999.

9+1 is 10. Using the [[Multiples Facts]], specifically the [[Multiples added to Multiples]], we can find which value of A leads to 6A34 being divisible by 9:
![[Files/Images/3 and 9 for divisibility 2023-12-25 11.52.20.excalidraw]]
We use the [[Distributive Property]] to notice that [[Multiples added to Multiples]] is going on, so now we only
need to worry about 6+A+3+4 being a multiple of 9, and since A must be 
$$0\le A<10$$
A can equal only 5 (no negatives, no values above 9), so A equals 5.

Does this work for all numbers? And what exactly is the "Rule?"
# The rule
So, does this rule work for all numbers?
Since we are asking about [[Divisibility Rules]] we worry only about the [[Absolute Value]]

Lets take a 4 digit number and see what it requires to be divisible by 9
![[Files/Images/3 and 9 for divisibility 2023-12-25 12.05.51.excalidraw]]
So we go through the same process with the variables, to deduce that the digits of the number are all that matters. If the digits added together are [[Divisible]] by 9, then the number itself is divisible by 9.

Notice also that 9 is a [[Multiple]] of 3, and since 9 is a multiple of 3, then x(999)+y(99)+z(9) is also a multiple of 3, so in order for xyzw to be a multiple of 3, x+y+z+w must also be a multiple of 3.  Using the [[Multiples added to Multiples]] fact, we have deduced the [[Divisibility Rules]] for 3 and 9.