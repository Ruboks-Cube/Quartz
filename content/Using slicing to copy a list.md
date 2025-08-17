---
{"publish":true,"created":"2025-07-07T12:56:44.000-04:00","modified":"2025-08-17T16:23:39.718-04:00","tags":["Coding/python"],"cssclasses":""}
---

We can also use slicing to make a copy of a list
```python
list1 = ["apple", "banana", "cherry"]
list2 = list1[:] #makes a true copy of list1
list2.append("orange")
print(list1) #output: ['apple', 'banana', 'cherry']
print(list2) #output: ['apple', 'banana', 'cherry', 'orange']
```
