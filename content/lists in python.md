---
{"publish":true,"aliases":"Python lists lists List","created":"2025-06-23T11:21:02.000-04:00","modified":"2025-08-17T16:23:46.021-04:00","cssclasses":""}
---

#Coding/python 

[[list in coding\|lists]] in [[Python]] are an ordered [[sequence in python\|sequence]] that are [[mutable]]
	[[list in coding]]
They are one of the 4 [[python datatypes\|Datatypes]] that store collections of data
	The other 3 are [[tuple]], [[set in python\|set]], [[Python Dictionaries\|dictionary]]
Lists are created using square brackets

example:
```python
mylist = ["apples", "bananas", "oranges"]
print(mylist) #returns ["apples", "bananas", "oranges"]
```
lists are a [[sequence in python\|sequence]], in [[Python]] (like all other [[sequence in python\|sequences]] in python) they use [[0 based indexing]]
- [[what does ordered mean in a list -python\|What does ordered mean in a list]]
Lists are changeable
	We can change, add, and remove items in a list

Lists allow duplicate values:
```python
mylist = ["apples", "apples"]
```
The items still have different [[indexing\|indexes]]

-  [[using len() to determine how many items a list has -python]]

```python

mylist = [true, "hello", 1, 2, false] #lists can contain any datatype AND have different datatypes
```

- [[Using type() with a list]]
- [[Using list constructor to create a list]]


## [[sequence in python\|sequence]] based things you can do with lists
- [[indexing in python]]
	- [[slicing sequences in python]]
	- [[negative indexing]]
- [[keyword 'in' in python\|using keyword "in" to check a sequence]]
- [[list comprehension]]

- [[change list items]]
- [[add list items]]
- [[Remove list items]] → removes list items (see below for more info) 
	- [[remove()]] → removes a specific item by value
	- [[pop()]] → removes an item by index and returns it
		- [[Using pop() with a list]]
	- [[del keyword python\|del]] → removes an item by index or slice or delete the entire list
	- [[clear()]]  → removes all items in the list
- [[loop lists]]
- [[sort lists\|sort()]]
	- [[key parameter]]
	- [[customizing sort function\|customize sort functions]]
- [[reverse()]]
- [[copy()]] → makes a copy of a list