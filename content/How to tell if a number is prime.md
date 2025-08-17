---
{"publish":true,"created":"2024-11-21T06:17:27.000-05:00","modified":"2025-08-17T17:05:25.789-04:00","cssclasses":""}
---

#math/primenumbers #math/numbertheory 

# Example Problem 

is 281 prime?

Being a [[Prime Numbers]]-s means that you have no divisors except 1 and itself, so we have to test the numbers.
![[Files/Images/How to tell if a number is prime 2023-12-28 14.54.09.excalidraw]]Using our [[Divisibility Rules]] (except for 7, no slick tricks for 7...), we have found out that numbers from 1-10 do not work. Since all numbers except the primes are multiples of these numbers, the only numbers to check are the primes. So do we have to test ALL the primes?? I don't wanna!!! But lets try and see if we can find a pattern! Lets start doing [[Division]] with [[Prime Numbers]]

![[Files/Images/How to tell if a number is prime 2023-12-28 15.03.35.excalidraw]]
	Welp, I certainly don't want to be testing this any longer. Long [[Division]] is boring. HMMM lets pay attention to the quotient/answer of the division problems. As the [[Divisor]] gets bigger, the quotient gets smaller. Which makes sense since as you divide by a bigger number, it can fit less in the [[Dividend]]. So, we divide by 11, and we get 25, 13,21, 17,16. Since the quotient is getting smaller, it's also going to get smaller as we divide by bigger prime numbers right?


If you are dividing a number by something, both the quotient and the divisor are [[Factor]] of that number, since they do [[Multiplication]] to make that original [[Dividend]].  So, since we are doing prime numbers, and they are getting bigger, but the quotient is getting smaller, and since the quotient has to multiply with the prime number to get to the [[Dividend]], or "281" in this case, we can stop testing!

281 is prime since the quotient will keep getting smaller, and we know that no integers below 16 that are factors of 281.

# The rule
To see  if a number is prime, after checking all the numbers from 2-9, you have to test the primes. You can stop testing the primes