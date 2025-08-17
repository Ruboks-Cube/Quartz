---
{"publish":true,"aliases":"square root #math/arithmetic/exponent/radical","created":"2024-11-21T06:17:32.000-05:00","modified":"2025-08-17T17:05:36.024-04:00","cssclasses":""}
---

#math/arithmetic/exponent/radical #tag 
[[Exponents]]
# Square roots
## Canvas representation
![[Square Roots.canvas|Square Roots]]
## What is square root?
The square root of something is what we multiply by itself to get that something.

When we square, we call that a [[Exponents\|Exponent/Power]] of 2. It's when we [[Multiplication\|Multiply]] a number by itself. Sometimes we want to go in the other direction, what number we multiplied by itself x amount of times (for square root it's 2) to get a number. <mark class="hltr-green">We start with a</mark> [[Perfect Squares\|Square]], <mark class="hltr-green">then find which number we multiplied by itself to get that.</mark>

Say, we multiply 9 by itself twice to get 81, 9 times 9 equals 81.

But what if we ask, "What number do we multiply by itself twice to get 81?" The answer is 9

![[Files/Images/square root 2024-01-25 19.50.40.excalidraw\|100]]
This symbol is called a radical, and this is the square root of 81, it asks us, what number did we square to get 81?

You may say that -9 squared is also 81, so would it also be considered a solution to the square root of 81? No, if we square root something, we always take the positive output.

- The square root of a positive number is a positive number.
	- We do this because it would be unnecessarily painful to have to say we want to positive output
	- "Length of a side of a square is the square root of 16 inches" is way easier to say than, "Length of a side of a square is the square root of 16 inches, where we mean the positive value of 16 inches"
- We cannot find the square root of a negative number, because if we multiply a negative number by itself, it will be positive
- When we "Evaluate", "Calculate", or "Simplify" a square root expression, we try to make it so there is no radical
- 2 [[Exponent Rules!\|Exponent Rules]] in particular are important to understand square roots, [[Power to a power exponent rules\|Power to a power]] and [[Product of Powers, quotient of powers]] rule
## Examples of evaluating square roots
[[square root of a cube]]
[[Finding big square roots]]
[[negatives in square roots]] 
[[separating and combing radical expressions]]
[[Square of a square root]]



## applying in [[Equation]]s
Lets say we have the problem: $$\sqrt{3x-5}^{}=11$$
Where would we even start?
- We can try getting rid of the square root by squaring it$$\sqrt{\left(3x-5\right)^{}}^2=11^2$$
- We square both sides to keep them equal
	- We note that [[Square of a square root]] is just the base number, which is 3x-5
- So now we have:$$3x-5=121$$
- Now this is like any other [[Linear Equation]], after adding 5 to both sides and dividing we have $$x=42$$

#  What is Radical Notation?
## The basics
Square roots are written in radical notation, meaning they use the $\sqrt[y] x$. When we use that symbol, we assume that the $y$ is 2 if there is no number there, the 2 is saying what number do we multiply by itself twice, or [[Perfect Squares\|Square]] to get $x$?

We can have different numbers in the $y$ however. We can have $\sqrt[3]x$, now this is saying what number we cube to get x? And more and more. If we have $\sqrt[y]x$ this is asking us, what number are we multiplying by itself $y$ times to get $x$?


> [!NOTE] Note:
> $\sqrt [3]x$ is known as a [[cube root]]

### AAAAAA [[Fractional Exponent\|Fractional Exponents]]
#### Basic
Radical Notation and Fractional exponents are very closely related. Lets take the problem $x^{1/2}$, we know that this is equal to the [[Radicals and Square Roots\|square root]] of x.

We also have this way to write it $\sqrt[2]x$, or just $\sqrt x$, which is asking what times itself equals x? These two are the exact same thing since square roots are asking that as well.

How do we write other fractional exponents in Radical Notation?
$27^{1/3}$, is equal to the number that when multiplied by itself 3 times, is 27
- Using our previous knowledge, this would be the [[cube root]].

Okay, but what about something like $100^{1/5}$, this is asking us what number do we multiply by itself 5 times to get 100? This is equal to $\sqrt[5]{100}$, since that [[Expression]] is also equal to the number we multiply by itself 5 times to get a 100. It's just how we notate that in math.

So we know if we have $x^{1/y}$, we just have $\sqrt[y]x$.

What if we have different [[Numerator\|Numerators?]]

#### Different Numerators

- Write $3^{2/3}$ in radical notation

There are a couple ways to go about this problem
1. [[Power to a power exponent rules\|Power to a power]]
	- we take the [[cube root]] of 3, lets just say it's $x$.
	- $(x^3)^{2/3}=x^2$
	- We also know that the [[cube root]] of 3 is $\sqrt[3]3$, we can [[substitution\|Substitute that back in]]
	- $\sqrt[3]3^2$
	- This equals $\sqrt[3]{3^2}$ as well since it is equal to $\sqrt[3]3*\sqrt[3]3$ which is $(3^2)^{1/3}$, can be inside or since [[Power to a power exponent rules]] says so
		- this is equal to $\sqrt[3]9$
2. Splitting the exponent [[Same Base exponent rules]].
	- $3^{2/3}=3^{1/3}*3^{1/3}=\sqrt[3]3*\sqrt[3]3=\sqrt[3]3^2$ which we know is equal to $\sqrt[3]9$
3. Splitting the exponent into a different [[Power to a power exponent rules\|Power to a Power]]
	- Richard, the guy who makes the AOPS videos, saw this problem and was like, hmm, $3^{2/3}=3^{2*1/3}=(3^2)^{1/3}$, we can split the exponent this way because of [[Power to a power exponent rules]]
	- This in turn is equal to $9^{1/3}=\sqrt[3]9$

What about $x^{m/n}$? How can we prove this? We can go through the same steps to prove this.
#### Fractional exponent key ideas
$x^{m/n}=x^{m*1/n}=(x^m)^{1/n}=\sqrt[n]{x^m}$
EXPLANATION:
- We use our [[Power to a power exponent rules]] to turn $x^{m/n}$ into $x^{m*1/n}$, and then into $(x^m)^{1/n}$.
- Now if we substitute $x^m$, if we set $x^m=z$, we get $z^{1/n}$. This is asking us, what number do we multiply by itself $n$ times to get $z$? Which is equal to $\sqrt[n]z$, plug $x^m$ back in and we get $\sqrt[n]{x^m}$





# Radical Notation Problems
## Computing bigger numbers
Compute: $\sqrt[4]{625}$
This means we're looking for the [[Positive Numbers\|Positive Number]] that when is multiplied by itself 4 times equals 625.
Maybe you know this by the top of your head, maybe not, but if you don't, lets [[Prime factorization\|Prime Factorize]] this.

- $\sqrt[4]{625}$, we can factor out a 5 to get $\sqrt[4]{125*5}$
- You should be able to see now that $125$ is a multiple of 25 so we get
	- $\sqrt[4]{25*5*5}$
	- pull out one more 5 to get $\sqrt[4]{5^4}$
We can draw the same conclusion from this expression in many different ways.
- 5 to the power of 4 equals 625, which means our answer is just 5, this is just using logic
- $\sqrt[4]{5^4}=(5^4)^{1/4}=5^{4*1/4}=5^1=5$, this is just [[using algebra]].





## [[decimal\|Decimals]], o no I'm scared

Compute: $\sqrt[3]{-0.216}$
We may be able to guess the answer, we may not be able to. The first step is to deal with the [[Negative Number\|Negative]]
1. My way
	- The only way to get a negative number when you cube something is if you start off with a negative, so we have $-(\sqrt[3]{0.216})$
	- We don't really know how to deal with the cube root of decimals, but we do for [[Fraction\|Fractions]] since fractions are just the [[Product of Powers, quotient of powers\|Quotient of Powers]] rule in a different form.
	- Lets convert 0.216 into a fraction, that would be $\frac{216}{1000}$, we can [[Simplifying Fractions\|Simplify the fraction]] by dividing both the numerator and denominator by 2
		- $\frac{108}{500}$, again divide both by 2 to get $\frac{54}{250}$, we can do that again to get $\frac{27}{125}$, you may be able to recognise 27 and 125 as cubes of 3 and 5.
	- Our expression is now $-\sqrt[3]{\frac{27}{125}}$
	- This is equal to $-\left( \frac{27}{125} \right)^{1/3}$ which is also $-\left( \frac{{27^{1/3}}}{125^{1/3}} \right)$ since it's a [[Product of Powers, quotient of powers\|power of a quotient]]
	- we have $-\frac{3}{5}$ as our answer.
2. Richard's way [[Richard Rusczyk]]
	- He too converted 0.216 into a fraction. 
	-  So we have $\sqrt [3]\frac{216}{1000}$
		- We can immediately go to $\frac{{\sqrt[3]{216}}}{\sqrt[3]{1000}}$
		- $\sqrt[3]{1000}$ is easy since thats just 10
		- for $\sqrt[3]{216}$ we can do [[Prime factorization]], we just keep pulling twos out.
		- $\sqrt[3]{108*2}=\sqrt[3]{54*2^2}=\sqrt [3]{27*2^3}$
		- We have $\sqrt[3]{27}$ and $\sqrt[3]{2^3}$. $\sqrt[3]{27}$ is just 3, while $\sqrt[3]{2^3}=2$, so we have $3*2$ in our numerator which is 6
	-  Now we have $\frac{6}{10}$ which when simplified is $-\frac{3}{5}$


For Both answers we should probably convert $-\frac{3}{5}$ into $-0.6$ since we started with a decimal, we should also end with a decimal
## Fractional exponent inside a radical????
Simplify $\sqrt[3]{49^{3/2}}$

1. My attempt
	- we have $\sqrt[3]{49^{3/2}}$
	- This is equal to $\sqrt[3]{(7^2)^{3/2}}$ which due to the [[Power to a power exponent rules\|Power to a power rule]] we have $\sqrt[3]{7^{6/2}}$ which is just $\sqrt[3]{7^3}$
	- Of course, 7 would be the number we [[cube (exponent)\|Cube]] to get $7^3$, so our answer is just 7

2. My attempt but another way to think about it
	- In my previous attempt we thought of the fractional exponent as just a fractional exponent, but we can also think of it as a radical
	- $\sqrt[3]{49^{3/2}}$= $\sqrt[3]{\sqrt {49}^3}$
	- $\sqrt{49}=7$ so we have $\sqrt[3]{7^3}$ which equals $7$
3. yet another way to think about it is:
	- Another way to do it would be to turn the $\sqrt[3]{x}$ into a fractional exponent itself, so we have $(49^{3/2})^{1/3}$
	- We can deal with the fractional exponent inside the parenthesis first so we have $\sqrt{49}^3$ which is $7^3$, so now we have $(7^3)^{1/3}$, we use our [[Power to a power exponent rules\|Power to a power]] rule to get $7^{3*1/3}$ which is just $7^1$, which is just $7$
4. ANOTHER 
	- we have $(49^{3/2})^{1/3}$, we can multiply the exponents here with [[Power to a power exponent rules\|Power to a power]] to get $49^{3/2*1/3}$ which is $49^{3/6}$ which is $49^{1/2}$ which is $7$.

## 3 radical expressions all at the same time
Simplify ${} \sqrt[4]{48}+\sqrt[4]{243}-\sqrt [4]{768} {}$

1. Richard ruszcyk's way
	- Lets just focus on one of them first, we have $\sqrt[4]{48}$, we've simplified [[Radicals and Square Roots\|square roots]] by pulling out factors of 2, we found [[Square of a square root\|square root of a square]] so we had [[Perfect Squares]]. Now lets try to find perfect 4ths, or whatever they call it, we start by prime factorizing this
		- $48=8*6=2^4*3$, so we have $\sqrt[4]{2^4*3}$, this is equal to $\sqrt[4]{2^4}*\sqrt[4]3$ because of the [[separating and combing radical expressions]].
		- we have $2\sqrt[4]3$, which cannot be simplified any further.
	- We now have ${} 2\sqrt[4]3+\sqrt[4]{243}-\sqrt[4]{768} {}$
	- Lets simplify $\sqrt[4]{243}$
		- we know 243 is divisible by 9 because of our [[Divisibility Rules]] so lets pull out the 9 and prime factorize the rest
		- $243=9*27=3^2*3^3$, combine those into $3^5$ through our [[Same Base exponent rules]] and we have $3^5$, the rest of the expression is $\sqrt[4]{3^5}$ which is equal to $\sqrt[4]{3^4}*\sqrt[4]3$ since we can [[separating and combing radical expressions\|Separate this]]
		- Now we have $3\sqrt[4]3$ which cannot be simplified any further
	- The rest of our expression is ${} 2\sqrt[4]3+3\sqrt[4]3-\sqrt[4]{768} {}$
	- Now lets simplify $-\sqrt[4]{768}$
		- [[Prime factorization\|Prime factorize]] 768 by seeing that it's a factor of 3 through our [[Divisibility Rules]] and we have $768=3*256$, [[Prime factorization\|Prime factorize further]]
			- $3*256=3*2*128=3*2^2*64=3*2^2*8^2=3*2^8$
		- We now have $-\sqrt[4]{3*2^8}$, split this by doing $-(\sqrt[4]{2^8}*\sqrt[4]{3})$, we simplify the $\sqrt [4]{2^8}$ by splitting it into $\sqrt[4]{2^4}*\sqrt[4]{2^4}$ and we have $2*2=4$, so we have $-(4\sqrt[4]3)$ which is equal to $-4\sqrt[4]3$
	- The rest of our expression is $2\sqrt[4]3+3\sqrt[4]3-4\sqrt[4]3$, we have a bunch of terms with a $\sqrt[4]3$, meaning we have a bunch of [[Combining Like terms\|Like terms]] that we can combine since we can [[Factoring\|factor out]] $\sqrt[4]3$
	- Our expression is equal to $\sqrt[4]3$

## A variable as an exponent
For what value of $n$ is the following equation true:
$2^n=\sqrt[3]{4}*\sqrt{32}$
Hmm, so we have to write the right side as 2 to the power of something.

1. My attempt
	- $\sqrt[3]4*\sqrt {32}$, lets try simplifying the $\sqrt {32}$ 
		- $\sqrt {32}=\sqrt{4*4*2}=\sqrt {2^5}$
		- $\sqrt{2^5}=\sqrt {2^2}*\sqrt {2^2}*\sqrt 2$, we can split it like this because of [[separating and combing radical expressions]]
		- Now we have $2^2\sqrt 2$
	- The rest of the expression is $2^2\sqrt[3]4\sqrt 2$ 
	- $\sqrt[3]4=\sqrt[3]{2^2}$. we have $2^2(\sqrt[3]{2^2}\sqrt 2)$, we have to simplify $\sqrt[3]{2^2}\sqrt 2$, it equals $(2^2)^{1/3}(2)^{1/2}$
		- we have a [[Power to a power exponent rules\|Power to a power]], we can simplify the expression to $2^{2/3}2^{1/2}$, now we have a [[Same Base exponent rules]] case so we can add the exponents to get $2^{7/6}$
		- So we have $2^2*2^{7/6}$, this also a [[Same Base exponent rules]] case where we can just add the exponents to get $2^{19/6}$