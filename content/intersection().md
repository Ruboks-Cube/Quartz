---
{"publish":true,"created":"2025-07-13T13:43:05.000-04:00","modified":"2025-08-17T16:23:41.865-04:00","tags":["Coding/python"],"cssclasses":""}
---

The intersection() [[Method]] for [[set in python\|sets]] is like finding the [[Greatest Common Factor]] between the two sets
	This is because it creates a new set ONLY with items both sets have
```python
set1 = {"apple", "banana", "cherry"}
set2 = {"google", "microsoft", "apple"}

set3 = set1.intersection(set2)
print(set3) # output {'apple'}
```
- [[intersection_update()]] 
You can also use the [[& operator]] but this wont allow you to intersect from different datatypes other than set
	[[Joining sets using operator vs using method]]

Note that when using [[intersection()]], [[duplicates are not allowed in sets\| true and 1 and false and 0 are the same]]
