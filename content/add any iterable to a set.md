---
{"publish":true,"created":"2025-07-13T11:36:59.000-04:00","modified":"2025-08-17T16:23:42.029-04:00","tags":["Coding/python"],"cssclasses":""}
---

To add items from one [[set in python\|set]] to another [[set in python\|set]] it’s like using [[add()]] but it’s a different [[Method]]
	Instead we use [[update()]]
```python
thisset = {"apple", "banana", "cherry"}  
tropical = {"pineapple", "mango", "papaya"}  
  
thisset.update(tropical)  
  
print(thisset)
```

We can add any [[iterable]] to a set:
```python
thisset = {"apple", "banana", "cherry"}  
mylist = ["kiwi", "orange"]  
  
thisset.update(mylist)  
  
print(thisset)
```

We can also use [[union()]]