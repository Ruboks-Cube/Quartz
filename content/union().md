---
{"publish":true,"created":"2025-07-13T13:23:35.000-04:00","modified":"2025-08-17T16:23:41.570-04:00","tags":["Coding/python"],"cssclasses":""}
---

[[Returning in code\|Returns]] a new [[set in python\|set]] based on what you have joined
	Returns it into a new [[variable in coding\|variable]]
```python
set1 = {"a", "b", "c"}
set2 = {1, 2, 3}

set3 = set1.union(set2)
print(set3) # output {'a', 1, 2, 3, 'c', 'b'} -> in any order since sets are unordered
```
- [[joining multiple sets]]
- You can get the same affect using [[union operator]]   
- [[Joining a set and a different iterable]]

