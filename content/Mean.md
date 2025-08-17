---
{"publish":true,"created":"2024-11-21T06:17:29.000-05:00","modified":"2025-08-17T17:05:29.637-04:00","cssclasses":""}
---

#math/statistics 

To find the mean/average, you add up all the data values, and then divide by how many there are.

For example, if you have the values, 3,4 and 5, the average would be $\frac{{3+4+5}}{3}$, the average is 4. 



## Another way to think about the average
source : https://artofproblemsolving.com/videos/prealgebra/chapter13/288

### Problem in video
The number of words I typed in the last 5 minute typing tests I took are, 73, 72, 81, 76 and 74. How many words would I have to type in the next one minute test to raise my average to 80 words per minute.

#### first Solution

Start off with writing MATH

We know that we need the average to become 80 words per minute, we get the average by adding up all the values and then dividing by how many values there are. So lets do that but with a [[variable math\|Variable]] since the next test is our unknown value.

$\frac{{73+72+81+76+74+x}}{6}=80$ 
Now we have a [[Linear Equation]] that we can solve. 

We can multiply the whole equation by 6 to get
$73+72+81+76+74+x=6*80$

Now we have to add up the left side, a nice way to do this is to notice that they are all close to 70. We have 5 70's and then add up all the extra values.

${} 70*5+(3+2+11+6+4)=350+26=376 {}$
We now have
$376+x=480$ (multiply 80 by 6 on the right side)

Subtract $376$ from both sides and we get
$x=104$

#### Slick Solution

Getting an average of 80 over 6 tests is like getting 80 6 times. The average of that would be 80 since there is only the value of 80.

Some of the tests were good and some of the tests were bad, but to get an average of 80, the sum of all of those tests have to be equal to the sum of all those 80's to get the average.

We have something like this:
$73+72+81+76+74+x=80+80+80+80+80+80$, it's the same equation, but now the way we see it is different. To get x, we start looking at how different the values we have are from 80. $-7,-8,+1,-4,-6$, most of the tests were lower than an average of 80, so the values are negative since they are lower than 80. Adding all of these up and we get $-24$. So the sum of the actual tests is 24 lower than the sum of all the 80's, meaning to get an average of 80, we just add 24 to 80 to make the sum equal to 24 again, which is 104.

To get the average of 80, the total amount ABOVE 80 has to equal the total amount BELOW 80, which is where the whole idea of average comes from.