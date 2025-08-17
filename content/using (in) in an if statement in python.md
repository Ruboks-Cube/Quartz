---
{"publish":true,"created":"2025-06-23T12:05:55.000-04:00","modified":"2025-08-17T16:23:32.269-04:00","cssclasses":""}
---

#Coding/python 

a more sophisticated approach to [[keyword 'in' in python\|using keyword in to check a sequence]] than [[using print() with (in) in python]]

it’s an alternative to [[using print() with (in) in python]]

We use an if statement instead:

```python
txt = "The best things in life are free!"  
if "free" in txt:  
  print("Yes, 'free' is present.")
```
This one makes more grammatical sense than [[using print() with (in) in python\|using print to check]] 

literally translates to “if free is in the text, print ‘yes, “free” is present’” 

Can do this for other [[sequence in python\|sequences]] than [[Strings in Python\|str]]

```python
a = [1,2,3,4]
if 3 in a:
	print("3 is accounted for")
```