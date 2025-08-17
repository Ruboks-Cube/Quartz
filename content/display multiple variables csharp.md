---
{"publish":true,"created":"2024-11-21T06:17:24.000-05:00","modified":"2025-08-17T16:23:26.017-04:00","cssclasses":""}
---

#coding/robloxstudiolua 
## Wdym display multiple variables?
the WriteLine() method ([[Console.WriteLine()]], [[Console.Write]]) allows you to COMBINE THE VALUES INSIDE IT!!! WHO COOLS IS THAT 

(I mean you *can* use Console.Write a bunch of times, but that is inefficient)


[[integer]] , [[String]]s
# Examples
So, what do I mean by combining values? HRMMM lets see.

## two strings
Lets take 2 string [[variable in coding]]s (nice grammar)

```csharp
string name = "Saumya ";
string lastname = "Dangol";

Console.WriteLine(name + lastname);
```
The output should be `Saumya Dangol`

So yes, we can combine ints(Which will lead to it doing math) and other things too. Combining an int with a string will pretend the int is also a string and just, stick it with the string.

## two ints

```csharp
int pagenumber1 = 400;
int pagenumber2 = 500;
int pagesread = (pagenumber1 + pagenumber2); /*you can also combine it through a variable*/

Console.WriteLine(pagesread)
//the output would be 900.
```