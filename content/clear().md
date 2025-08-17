---
{"publish":true,"created":"2025-07-01T11:43:41.000-04:00","modified":"2025-08-17T16:23:45.755-04:00","tags":["Coding/python"],"cssclasses":""}
---

Clear() clears all items from a [[lists in python\|List]], [[set in python\|set]], or [[Python Dictionaries\|Dictionary]]

example:
```python
thislist = ["apple", "banana", "cherry"]
thislist.clear()
print(thislist) # returns []
```

This is different from [[del keyword python\|del]] as it only clears the [[collections in python\|collection]], not delete it

```python
thisset = {"apple", "banana", "cherry"}

thisset.clear()

print(thisset) # output: set() 
```