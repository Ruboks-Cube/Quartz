---
{"publish":true,"created":"2025-07-09T15:48:35.000-04:00","modified":"2025-08-17T16:23:40.832-04:00","tags":["Coding/python"],"cssclasses":""}
---

We can check a [[tuple]] with [[keyword 'in' in python\|in]] and [['not In' in python\|not in]] in [[Python]] like any other [[Sequence]]
```python
my_tuple = ("apple", "banana", "cherry")
print("apple" in my_tuple) #output # True
```
[[using print() with (in) in python]]

```python
my_tuple = ("apple", "banana", "cherry")
if "banana" in my_tuple:
	print(true) #output # True
```
[[using (in) in an if statement in python]] 


This would be different than [[keyword 'in' in python\|checking a list]] because tuples have a strict order and are [[immutable]] while lists are [[mutable]]
	There is less reason to check a tuple because once you have the tuple you have it