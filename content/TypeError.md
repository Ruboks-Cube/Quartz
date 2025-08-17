---
{"publish":true,"created":"2025-08-02T16:27:27.000-04:00","modified":"2025-08-17T16:23:50.038-04:00","tags":["Coding/python"],"cssclasses":""}
---

A TypeError is a [[python errors\|Python Error]] when combining 2 or more [[python datatypes]]
	For example, when trying to [[concatenation\|concatenate]] a [[Strings in Python\|string]] and a [[int]] it gives you a TypeError
- Instead you’ll need to use an [[format strings python\|f-string]]

It also happens if an operation is attempted with an unexpected [[Datatype]]
Example:
```python
my_list = ["apple", "banana", "cherry"]
x = items(my_list) # items() is a dictionary-specific method
print(x) #TypeError because trying to use dictionary method on a list
```
- [[items()]]
- [[Python Dictionaries\|Dictionary]]
- [[lists in python\|List]]
