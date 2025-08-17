---
{"publish":true,"created":"2025-04-21T17:32:12.000-04:00","modified":"2025-08-17T17:06:00.634-04:00","cssclasses":""}
---

#math/arithmetic/logarithm #math/function/exponential #math/graphing 


- Remember that [[Logarithm\|logarithms]] are the [[Inverse Functions\|inverse]] of [[exponential function\|exponential functions]]
> [!faq] Why is that important?
> This means that we can take the inverse of a [[Logarithm]] ([[exponential function]]), graph that → [[Graphing Exponential Functions]], and then switch the $x$ and $y$ values
> > [!note] Note
> We don’t actually have to graph the [[exponential function]], just find the values and you can switch them
> 
> So all we have to do is consider the inverse, then we can graph the log.
> This works but we could also take shortcuts :)



- The parent of a log function is $\log_{b}x$ 
- What is the inverse of $y=\log_{b} x$?
	- First switch the $x$ and $y$ values
	- $x=\log_{b} y$ 
	- Now we have to isolate $y$
	- We know that $\log_{b}y=x$ is $b^x=y$ 
	- Therefore the inverse of $y=\log_{b}x$ is $b^x=y$ 
- Different transformations can happen to a log function that will affect it
> [!Summary] Transformations
> - The parent function is $y=\log_{b}x$, the exponent from b→x
> 	- if $b$ is a positive value (has to be) then the function will look like this:
> 	![[Files/Pasted image 20250421180250.png|Here b is 10|300]]
> 	- Why? 
> 	- You are asking what the exponent will be from $b$ to $x$
> 	- No exponent can make $b$ equal $0$
> 	- Very small [[Fractional Exponent\|fractional exponents]] and/or [[Negative Exponents]] can make $b$ smaller than itself
> 	- Slightly bigger exponents make $b$ slightly bigger
> 	- $x$ has to get really big for $b$ to get big
> 	- $x$ intercept is $1$ because if $x$ is 1 the exponent of $0$ makes $b$ 1
> - Now that we understand the parent function lets move onto understanding transformations
> 
> > [!example] x is negative
>> If we have $y=\log_{b}(-x)$ the whole graph will reflect across the $y$ [[axis]]
>> This is because no exponent can make $b$ negative, if $x$ itself is negative then we have $--x$ which is positive, so the whole graph just reflects.
>> > [!important]
>> > This transformation affects the $x$ values in the final graph
>>
>> > [!faq] What if what's being multiplied to $x$ isn’t $-1$ but something else?
>> >  We should consider what we do for [[exponential function\|exponential functions]]. If we have ${} y=\log_{b}ax {}$ the inverse is $b^{ax}=y$, we apply $a$ to $b$. So we can use this idea and use the [[product logarithm rule]], $\log_{b}ax=\log_{b}a+\log_{b}x$, and now that $\log_{b}a$ becomes part of $d$ (see below).
>
>
>
> > [!example] A number is added to the whole equation
>> If we have something like $y=\log_{b}x+d$, the whole equation is raised by $d$
>> All $y$ values are changed by $d$ amount, depending on whether $d$ is [[Positive Numbers\|positive]] or [[Negative Number\|negative]], and the reason is pretty intuitive. Very similar change to the transformations for [[exponential function\|exponential functions]].
>> > [!important]
> The $y$ values are affected by this transformation by $d$ amount
> 
> > [!example] A number is being multiplied to the [[Logarithm\|log term]]
> > If we have $y=a\log_{b}x$ all the $y$ values are going to be multiplied by $a$. This results in a less sudden incline in the graph. A sort of “stretch” because the numbers start to get bigger quicker.
> > 	![[Files/Pasted image 20250421181944.png|before multiplying by 10|300]] ![[Files/Pasted image 20250421182351.png|after multiplying by 10|300]]
> > This also means that if $a$ is negative the graph is [[Reflection\|reflected]] across the $x$ [[axis]]
> > > [!important]
> The $y$ values are being affected here. Multiply the $y$ value by $a$ to get what the $y$ value will be.
> 
> 
> > [!example] Something is being added/subtracted to $x$
>> The $x$ [[Transformation\|transformations]] are more difficult to understand. If we have $y=\log_{b}(x+a)$, the whole graph moves by $-a$ points. So if $a$ is negative, it moves right, and if $a$ is positive, it moves left.
>> There’s also an [[Asymptote]] at ${} -a$ because $x \neq 0$ in $y=\log _{b}x$
>> > [!help]
>> > oh so you’re wondering why the fugue that happens. Recall exponential functions, think about how if we added something to $x$ in $y=b^x$ the whole graph moves left, this is because the larger exponent is happening quicker. Say if we had $y=b^x$ and input $5$, we just have $b^5$ at $x=5$ in the graph. If we had $y=b^{x+5}$ though, then at $x=0$ we have the $y$ value of $x=5$ in $y=b^x$. The larger exponent is literally happening sooner.
>> >
>> > What does this mean for logarithms? Since $y=\log_{b}x$ is the exponent from $b$ to $x$, and if we add something to $x$ like in $y=\log_{b}{x+a}$ then we’re finding the larger logs sooner.
>> > 
>>
>> > [!important]
> These transformations affect the $x$ values in the opposite direction.
> 
> > [!missing] Ok so now what
>> - These transformations can be combined in order to make a function. Keep in mind the transformations that affect the $x$ values and the ones that affect the $y$ values. That’s pretty easy to do. The ones that affect $x$ values are what’s in the parenthesis of the log, the ones that affect the $y$ values are literally everything else. 
>> - Take the parent of the log function, convert that to the parent [[exponential function]], find the values, flip the $x$ and $y$, and apply the transformations to graph your log function
>> > [!question] What order do the transformations go in?
>> think [[PEMDAS]], multiplication THEN addition right? For the $y$ transformations if something is multiplied to the $\log$ term apply that first THEN add.













 	

