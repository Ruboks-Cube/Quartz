---
{"publish":true,"created":"2024-11-21T06:17:28.000-05:00","modified":"2025-08-17T17:05:28.116-04:00","cssclasses":""}
---

#math/statistics 

> [!Warning] Limits of statistics
> While basic statistics are important, it's important know the limits of their abilities in order to know which problems you can solve with them, and knowing that they are BASIC statistics, we would need additional information for other problems, other types of statistics.

## Problem in source

https://artofproblemsolving.com/videos/prealgebra/chapter13/290 -- this source gives us a problem, it's a 2 part video


We have 4 sacks of money, each with some envelopes and in each envelope there is a different amount of money, and apparently, one of the sacks of money are impossible. So we have to figure out which one is impossible.

|            | Sack A | Sack B | Sack C | Sack D |
| ---------- | ------ | ------ | ------ | ------ |
| [[Median]] | 0      | 900    | 1200   | 20     |
| [[Mode]]   | 3000   | 0      | 2000   | 10     |
| [[Mean]]   | 600    | 80000  | 900    | 85000  |
### Thoughts before looking at 2nd part
We can try to look at each sack of money and try to see if it is possible to make with the smallest amount of values possible.

Sack A, we have the [[Median]] being 0, the mode is 3000, and the mean is 600. This means that 0 is the middle number, 3000 appears at least twice, and the sum of all the numbers divided by how many numbers there are is 600. 

Assuming that 0 is the smallest value available, we have something like this
0,0,0,0,x,3000,3000

to find x we just do
$\frac{{3000+3000+x}}{7}=600$
Which is
$3000+3000+x=600*7$ HUH, this means that x would be NEGATIVE, which isn't really possible... So sack A is impossible?! 
##### Claclus 

> [!NOTE] I had a feeling...
> I had a feeling that it was gonna work out, but I PROVED IT WITH VARIABLES! Sometimes it's hard to know what you have to prove. Just make sure that when you are trying to prove that something happens for all cases, you go through the same steps, this is mostly seen when I say, "We are solving for y, so isolate it by doing", we are still solving for y in this case, the average.

You may say, Hey! What if we have a bunch of zeros, yes, I accounted for that, the mode is 3000, which means there would have to be more 3000's than 0's, so you would take the number of 0's (x) and the number of 3000's would be *at least* $x+1$.

Now we have 0,0 (x times), y *the variable that makes the average*, 3000, 3000, (x+1 times) and all that over (x)+1+(x+1), to equal 600. We get that extra one from the y variable. We can take the sum
$\frac{{0*x+y+3000(x+1)}}{2x+2}=600$, now we have $y+3000(x+1)=600(2x+2)$ 
We are solving for y, so isolate it by doing
$y=600(2x+2)-3000(x+1)$
We then get
$y=1200x+1200-3000x-3000$, subtracting these results in negative values, showing that y would have to be negative to make the average 600, no matter how many 0's there are.

### Second Part Video Solutions
https://artofproblemsolving.com/videos/prealgebra/chapter13/291
- He has the same table in the background, except one of the numbers are missing
- He says that if you watched the video before then you should know why sack A doesn't have a number in one of the columns 

|            | Sack A                                  | Sack B | Sack C | Sack D |
| ---------- | --------------------------------------- | ------ | ------ | ------ |
| [[Median]] | 0                                       | 900    | 1200   | 20     |
| [[Mode]]   | *no number* will find that it's 0 later | 0      | 2000   | 10     |
| [[Mean]]   | 600                                     | 80000  | 900    | 85000  |
SO I'm RIGHT!

Lets take a look at the rest of what he has to yap:

#### First Question
- Each of the 4 sacks has a 1001 envelopes, which one has the most money?
This one is pretty easy. We realize that the total is just the average times the number of envelopes because the average is the amount of money divided by the the number of envelopes, multiply the number of envelopes by both sides and we get the average multiplied by the number of envelopes is equal to the total amount of moolah.

Another way you can think about it is that in a previous example of working with [[Mean]], the average in this case for sack A is like saying we have the number 600 1001, times, the sums of all money divided by how much there is is equal to the sum of 600 1001 times. So if we have 600 1001 times (which we don't, but is a possible case of how we get an average of 600), then we multiply 600 by 1001. 

Since we're multiplying by the same factor (1001) we just take the one that has the highest average, which is Sack D.
#### Second Question, take away statistic
- Which sack has the most money?
This is a limitation of statistics, we can't figure out this one because sack A could have ALOTALOT of envelopes, but sack D could have 3 and still have 85000m. So we can't figure this one out because **WE DO NOT HAVE AN EXACT NUMBER OF HOW MANY ENVELOPES THERE ARE**
#### Third Question, add on to the question
There are 4 sacks with 1001 money envelopes each. Choose the sack with the most envelopes with more than 1000 dollars.
Lets start by taking another look at the average. We know that the sum of everything divided by 1001 is equal to the average in this case. But we don't necessarily have an idea of how the money is distributed. All the money could be in 1 envelope and everything else could have a very little amount of money... Hmm, so the average won't help us, and a problem solving strategy is to look at the information we haven't used to far, and we haven't used the median. 
- Sack A's median is 0, which means that for 1001 envelopes, 501 of them are going to have 0 as how much money there is
- Sack B has 501 envelopes less than 1000, (900)
- Sack C has a median of 1200, so that must be the one with the most since sack D has a median of 20.

#### Fourth Question, change number
Each of the 4 sacks has 1001 envelopes, which is the one with the most envelopes with 10,000.

- For all of these, we just know that more than half the sack is less than 10,000 dollars, but we can't figure out the exact value.
- In each sack there could be one envelope with a WHOLE lot of money, and then the rest is little amount

#### Last Question, individual envelope
There are 4 sacks of money, each sack has 1001 envelopes. Which sack is the one with an envelope with the most money.
- We run into the same problem for the fourth question
- In each of the sacks there could be one envelope with a LOT of money, then the rest have a little, or it could be equality distributed. We just don't know.

