---
{"publish":true,"created":"2025-07-13T13:40:26.000-04:00","modified":"2025-08-17T16:23:41.978-04:00","tags":["Coding/python"],"cssclasses":""}
---

When using [[union()]] and [[update()]], since [[duplicates are not allowed in sets]], these methods will automatically exclude duplicate items from the new [[set in python\|set]]
	So you wont get an error if you do something like this:
```python
set1 = {1}
set2 = {True}
set3 = set1 | set2
print(set3) #output {1} since True is considered equal to 1 in Python
```
