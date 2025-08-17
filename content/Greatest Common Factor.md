---
{"publish":true,"created":"2024-11-21T06:17:26.000-05:00","modified":"2025-08-17T17:05:52.424-04:00","cssclasses":""}
---

#math/numbertheory #math/divisibility 

# How to do it and what it is
The greatest common factor, or the greatest common divisor, is finding the greatest [[Factor]] of all numbers in a set. 
[[Finding Multiples and Divisors through prime factorization ]] is necessary!!!


Similar to [[Least Common Multiple]] in the sense that you have to do [[Prime factorization]], however what you do with those [[Prime Numbers]] is different. 

So through [[Finding Multiples and Divisors through prime factorization]], we know that any divisor of a number has to have the factors and *only* the factors of that number. Since 16 is 2 to the power of 4, 3 isn't a [[Divisor]]/[[Factor]] since it's not a part of 16.


We also know that the greatest divisor of a number is the number itself, which is the highest power of that number! So we need the highest power of each number possible, but be careful to not add any extra [[Factor]]s. If you add a factor from 1 number, then the "GCF" you get will apply to one number, but not the other, maybe it won't apply to any number in the list! 

So lets try this

# Problem
GCF(144, 224)

![[Files/Images/Greatest Common Factor 2024-01-08 20.59.24.excalidraw]]
So we do our [[Prime factorization]], and find that both numbers have 2^4, and we don't take 3^2, 7, or the 2^5 since then it wouldn't be a factor of 144 with all the extra factors. 

Our answer is 16


# Rule For GCF

[[Prime factorization]], taking the *lowest* exponent of each factor.