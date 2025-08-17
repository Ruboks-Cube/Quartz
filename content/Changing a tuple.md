---
{"publish":true,"created":"2025-07-09T15:54:42.000-04:00","modified":"2025-08-17T16:23:40.948-04:00","tags":["Coding/python"],"cssclasses":""}
---

[[tuple\|tuples]] are unchangeable, but you can add values with a workaround
	convert them to a [[lists in python\|List]], change them, then turn them back into a [[tuple]]
```python
my_tuple = ("apple", "banana", "cherry")
list(my_tuple)
my_tuple[0] = "apple with sugar"
tuple(my_tuple)
print(my_tuple) #output: ('apple with sugar', 'banana', 'cherry')
```
We used the [[Using list constructor to create a list\|list constructor]] as well as the [[Tuple constructor]]

Adding items can be done with [[append()]] if you convert to a list

[[Concatenate tuples]]

To remove items we can convert to a list and use the remove methods
	[[remove()]]
	[[clear()]]
	[[pop()]]
We can also use [[del keyword python\|del()]]
	[[del keyword python\|del()]] can be used to delete the tuple
```python
my_tuple = ("apple", "banana", "cherry")
del(my_tuple)
```