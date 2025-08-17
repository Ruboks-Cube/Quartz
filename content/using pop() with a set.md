---
{"publish":true,"created":"2025-07-13T12:19:22.000-04:00","modified":"2025-08-17T16:23:41.061-04:00","tags":["Coding/python"],"cssclasses":""}
---

Since [[set in python\|sets]] don’t have [[indexing\|indexes]] using [[pop()]] just deletes a random value and returns it
```python
thisset = {"apple", "banana", "cherry"}

x = thisset.pop()

print(x)

print(thisset) # output will be the set with one item removed randomly
```
