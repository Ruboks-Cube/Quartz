---
{"publish":true,"created":"2025-07-05T19:34:47.000-04:00","modified":"2025-08-17T16:23:45.660-04:00","tags":["Coding/python"],"cssclasses":""}
---



we use the `copy()` method to make a true copy of a list or [[Python Dictionaries\|Dictionary]]
```python
list1 = ["apple", "banana", "cherry"]
list2 = list1.copy() #makes a true copy of list1
list2.append("orange")
print(list1) #output: ['apple', 'banana', 'cherry']
print(list2) #output: ['apple', 'banana', 'cherry', 'orange']
```

```python
dict2 = dict1.copy() #making a copy of a dictionary
```


We can also use [[Using list constructor to create a list\|list()]] to make a copy of a list
We can use [[dict()]] to make a copy of a [[Python Dictionaries\|Dictionary]]