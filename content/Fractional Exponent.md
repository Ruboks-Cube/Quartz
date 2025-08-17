---
{"publish":true,"created":"2024-11-21T06:17:26.000-05:00","modified":"2025-08-17T17:05:25.104-04:00","cssclasses":""}
---

#math/arithmetic/exponent #math/arithmetic/exponent/radical 

We know how [[Exponents]] work, and we also know how [[Negative Exponents]], but how do Fractional Exponents work? 
# Key Point
To deal with fractional exponents, the denominator of the fractional exponent has to nicely cancel out with the [[substitution\|substituted]] version of the number that has the power of the exponent. 
# Figuring it out
## Intro, 1/2
- What is $36^{1/2}$?
	- We know that $6^2$ is $36$.
	- We can use the [[Power to a power exponent rules\|Power to a Power]] rule to turn this into $(6^2)^{1/2}$, and now suddenly, we have $36^{1/2}=6$!

- Okay, so what if we have $(x^2)^{1/2}$, thats just going to be $x$.

- So if we have $49^{1/2}$ we get $7$.
- So we can define $x^{1/2}$ as the number we [[Perfect Squares\|Square]] to get $x$, this is just a [[Radicals and Square Roots\|square root]]. Where x is [[Positive Numbers\|Positive]], since something like $-36$ wouldn't work. $x$ wouldn't be $-6$ since $(-6)^2\neq 36$
ok, but what about 1/3
## Different denominators, 1/3 and y

What if we have the problem $125^{1/3}$, will it be something cubed?

Well if $x$ is the number we cube to get 125, we have $(x^3)^{1/3}$, this simplifies to $x$. $x$ so happens to be 5.

Now, what if we have $y$ as the denominator??

$x^{1/y}$, what would this be?  If we define $z$ as $z^y=x$, we get $(z^y)^{1/y}=z$. So, fractional exponents with the numerator is just the [[Radicals and Square Roots\|radical]].


## Different numerators
Lets take the problem $16^{3/2}$, we have a number that is not 1 in the numerator. Lets try to see what we do in this situation.

4 is the [[Radicals and Square Roots\|square root]] of 16 so we have $(4^2)^{3/2}=4^{6/2}=4^3=64$.

We just follow our exponent rules like normal.


Another example $9^{2/3}*9^{5/6}$
We can use our [[Same Base rule\|Same Base Rules]] to combine the exponents. 
- First convert $9^{2/3}$ to $9^{4/6}$ then add to get $9^{9/6},$ this is equal to $9^{3/2}$.
- [[substitution\|Substitute]] $9$ for $3^2$ to get $(3^2)^{3/2}$
- Multiply the exponents $3^{6/2}$, this is equal to $3^3$ which is $27$.
- very happy that 27 is a nice number

> [!Tip] TIP!
>If you solved these individually, they individually would have been not nice numbers, thats why we took the product Saumya

### [[Negative Exponents]] that are also fractionaL
$27^{-2/3}$. Wow, just wow.
- The cube root of 27 is what we need for the denominator of the fraction to nicely cancel out.
	- It's 3
- Substitute to get $(3^3)^{-2/3}$
- Multiply $3^{-6/3}$, $3^{-2}$
- $3^{-2}=\frac{1}{9}$ through the [[Negative Exponents]] rule


# Advanced Problems

## -125/25

$\left( -\frac{125}{25} \right)^{1/3}$

This expression is equal to the cube root of ${} -\frac{125}{27} {}$.

- First, deal with the sign, if we cube a negative number we get a negative, positive, positive, so we know the cube must be negative, so our expression is equal to this:
	- $-\left( \frac{125}{27} \right)^{1/3}$
	- this is a [[Product of Powers, quotient of powers\|power of a quotient]], which we can write as a [[Quotient of Powers (same exponent)]]. 
	- We know have $-\left( \frac{125^{1/3}}{27^{1/3}} \right)$ 
	- Take the cubes and we get $-\frac{5}{3}$

## Big Number $1728000^{2/3}$
- We don't really know the [[cube root]] of $1728000^{2/3}$
- We can try breaking it up
	- $1728000=1728*1000$
	- We have $(1728*1000)^{2/3}$, this is just a [[Product of Powers, quotient of powers\|Power of product]]
	- The 1000 is easy to deal with because $1000=10^3$.
- to deal with the 1728, we start by [[Factoring]] it in a process similar to [[Prime factorization]].
	- $1728=2*864=2^4*108=2^5*54=2^6*3^3$
- We now have $(2^6*3^3)^{2/3}*10^2$
- ${} 16*9*100=144*100=14400 {}$