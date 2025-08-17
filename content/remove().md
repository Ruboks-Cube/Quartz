---
{"publish":true,"created":"2025-07-01T11:08:23.000-04:00","modified":"2025-08-17T16:23:41.238-04:00","tags":["Coding/python"],"cssclasses":""}
---

The remove() method removes a certain item from a [[lists in python\|List]] or [[set in python\|set]]

example:
```python
thislist = ["apple", "banana", "cherry"]  
thislist.remove("banana")  
print(thislist) # returns ['apple', 'cherry']
```

If there is more than one instance of that item, remove() will remove the first one

> [!fail] 
> If  what you are trying to remove does not exist an error will be raised, which is the difference between [[discard()]] because discard() does not raise an error



