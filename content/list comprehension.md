---
{"publish":true,"created":"2025-07-03T15:24:37.000-04:00","modified":"2025-08-17T16:23:39.295-04:00","tags":["Coding/python"],"cssclasses":""}
---

List comprehension allows you to create a [[lists in python\|List]] based on an older list in shorter syntax
	Instead of using a [[for loop in python\|for loop]]
```python
fruits = ["apple", "banana", "cherry", "kiwi", "mango"]
newlist = []

for x in fruits:
  if "a" in x:
    newlist.append(x)
print(newlist) #output ['apple', 'banana', 'mango']
```
We can do this:
```python
fruits = ["apple", "banana", "cherry", "kiwi", "mango"]
newlist = [x for x in fruits if "a" in x] #x is a loop variable
print(newlist) #output ['apple', 'banana', 'mango']
```
[[loop variable]] 
	 saying that `newlist` is `x` for each `x` in `fruits` if `"a"` is in `x`

Basic syntax:
```python
newlist = [expression for item in iterable if condition]

#converting to a for loop would look like:

for item in iterable:
		if condition:
				newlist.append(expression)
```
Translation: newlist is equal to the expression for each item that meets the condition in the [[iterable]]
→ [[append()]] 

[[expression in list comprehension]]

[[Condition in list comprehension]]
[[using range() with list comprehension]]