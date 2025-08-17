---
{"publish":true,"aliases":"using list() to make a copy of a list list constructor list()","created":"2025-06-29T10:56:57.000-04:00","modified":"2025-08-17T16:23:40.405-04:00","cssclasses":""}
---

#Coding/python 

We can use the list constructor to make a list in [[Python]]

```python
thislist = list(("apple", "banana", "cherry")) # note the double round-brackets  
print(thislist)
```

We can use list constructor to make a copy of a list → similar to [[copy()]] output
```python
list1 = ["apple", "banana", "cherry"]
list2 = list(list1) #makes a true copy of list1
list2.append("orange")
print(list1) #output: ['apple', 'banana', 'cherry']
print(list2) #output: ['apple', 'banana', 'cherry', 'orange']
```
