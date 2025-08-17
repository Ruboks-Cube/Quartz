---
{"publish":true,"created":"2025-07-13T14:09:29.000-04:00","modified":"2025-08-17T16:23:42.183-04:00","tags":["Coding/python"],"cssclasses":""}
---

It’s like [[symmetric_difference()]] and [[update()]] had a baby!!!
	Instead of creating a new [[set in python\|set]] with the values different in both [[set in python\|sets]], it simply changes the current [[set in python\|set]]
```python
set1 = {"apple", "banana", "cherry"}
set2 = {"google", "microsoft", "apple"}

set1.symmetric_difference_update(set2)

print(set1) # output {'banana', 'microsoft', 'cherry', 'google'}
```