---
{"publish":true,"created":"2025-07-07T12:51:02.000-04:00","modified":"2025-08-17T16:23:45.613-04:00","tags":["Coding/python"],"cssclasses":""}
---

Attempting to copy a list by doing `list2 = list1` doesn't actually copy it, it just creates a new reference to the same list in memory
		Changes made to `list2` will also affect `list1` and vice versa → they are the same object
```python
list1 = ["apple", "banana", "cherry"]
list2 = list1
list2.append("orange")
print(list1) #output: ['apple', 'banana', 'cherry', 'orange']
```
[[copy()]]
[[Using list constructor to create a list\|list()]]
[[Using slicing to copy a list]]