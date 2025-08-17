---
{"publish":true,"created":"2025-07-13T13:53:40.000-04:00","modified":"2025-08-17T16:23:41.805-04:00","tags":["Coding/python"],"cssclasses":""}
---

[[intersection()]] on its own acts like [[union()]], it’s used to create a NEW [[set in python\|set]] rather than add on to an already existing one
	intersection update combines [[update()]] and [[intersection()]]
	We change the original set based on what both sets have in common
```python
set1 = {"apple", "banana", "cherry"}
set2 = {"google", "microsoft", "apple"}

set1.intersection_update(set2)

print(set1) # output {'apple'} -> only what both sets have in common
```