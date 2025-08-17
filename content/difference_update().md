---
{"publish":true,"created":"2025-07-13T14:02:04.000-04:00","modified":"2025-08-17T16:23:42.798-04:00","tags":["Coding/python"],"cssclasses":""}
---

It’s like [[difference()]] and [[update()]] had a baby!!!
Differentiates and changes the current [[set in python\|set]] rather than create a new one
```python
set1 = {"apple", "banana", "cherry"}
set2 = {"google", "microsoft", "apple"}

set1.difference_update(set2)

print(set1) # output {'banana', 'cherry'} -> in any order since sets are unordered
```