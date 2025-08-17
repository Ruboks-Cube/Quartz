---
{"publish":true,"created":"2024-11-21T06:17:28.000-05:00","modified":"2025-08-17T17:05:27.831-04:00","cssclasses":""}
---

#math/numbertheory #math/primenumbers #math/rule 


# what is least common multiple? 

The least common multiple refers to the smallest [[Multiple]] that 2 numbers have in common.


# How to find least common multiple
## example problem
For example, if we clap every 24 seconds and jump every 45 seconds, when would be the first time we jump and clap at the first time? We must find the least common multiple in this situation, since every time we clap is a multiple of 24, and everytime we jump is a multiple of 45, so we need to find the smallest multiple that both 24 and 45 have.


So how exactly *do* we solve this problem?

if we clap every 24 seconds and jump every 45 seconds, when would be the first time we jump and clap at the first time? 

Well, since this is about multiples, we know that $$24\cdot45$$
is a multiple of both numbers, however we do not know if it's the *least* common multiple. So how do we get the smallest multiple possible?

Well, [[Factor]] are something we should consider. They are like the opposite of multiples, but we know that any factor of a number is also a multiple of any number that can be multiplied by that number. Take this for example, 4 times 6 is 24, this is a multiple of both 4 *and* 6. However, 2 is a factor of 4 and 6, and 3 is a factor of 6, 24 is also a multiple of 2 and 3 since 4 and 6 are a multiple of 24. This is the [[Multiples Multiplied to Multiples]] rule.

So now we see, any multiple of the original number are the multiples of it's factors as well! So, all we need is the [[Prime factorization]] of 24 and 45, and we need the *bare minimum*, so the factors of 24 *and* 45, but only the factors we need. (so if all the factors of 24 exist and there are some factors of 45 that are part of 45 then we skip those factors) It's almost like we are interlocking the numbers, mushing them together and if a prime factor already exists, that gets out as waste.  

All multiples of a number contain the [[Prime factorization]] of a factor, so we need a number that contains the prime factorization of both numbers, and ONLY the prime factorization of both numbers. What I mean is that we do a combination of combining the prime factorization of both numbers, and taking away extra factors.
![[Files/Images/Least Common Multiple 2024-01-04 18.55.07.excalidraw]]
Through prime factorization and cancelling out what already exists, we get 360 from multiplying the prime factors together.


## how to find it
You first have to do prime factorization, and then take what both numbers need.

You take factors of 1 number, then add the other numbers' factor to it without adding extra factors, by extra we mean that if they exist in one number already, you don't need the extra numbers' factor. You take the highest power of every number.
# Finding the least common multiple with big numbers.
[[Least Common Multiple slick trick]]