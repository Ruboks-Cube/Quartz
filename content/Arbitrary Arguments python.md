---
{"publish":true,"aliases":"Arbitrary argument *args","created":"2025-08-02T16:44:18.000-04:00","modified":"2025-08-17T16:23:50.477-04:00","tags":["Coding/python"],"cssclasses":""}
---

Arbitrary arguments or `*args` are what is used when you don’t know how many [[parameters in python\|arguments]] will be passed
	This is a way to get around the [[Default number of arguments]] raising an error
Add `*` before the parameter
```python
def my_function(*kids):  
  print("The youngest child is " + kids[2])  
  
my_function("Emil", "Tobias", "Linus")
```
- The `*` makes it so the [[parameters in python\|arguments]] are a [[tuple]] that you can access accordingly
	- (we access the last kid in this example with an [[indexing\|index]] of 2)

[[Why there is type error when there’s a wrong number of arguments for custom functions]]

[[Arbitrary Keyword Arguments python\|What do I do if I want an arbitrary number of keyword arguments?]]
	[[keyword arguments python]]