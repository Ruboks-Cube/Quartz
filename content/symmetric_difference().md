---
{"publish":true,"created":"2025-07-13T14:03:39.000-04:00","modified":"2025-08-17T16:23:42.242-04:00","tags":["Coding/python"],"cssclasses":""}
---

While the [[difference()]] method only takes values from the first [[set in python\|set]], symmetric_difference() creates a new [[set in python\|set]] with all the [[Element in array\|Elements]] both sets don’t have in common
```python
set1 = {"apple", "banana", "cherry"}
set2 = {"google", "microsoft", "apple"}

set3 = set1.symmetric_difference(set2)

print(set3) # output {'microsoft', 'banana', 'google', 'cherry'} -> in any order since sets are unordered
```

We can use the [[symmetric_difference operator]] instead BUTTT → [[Joining sets using operator vs using method]] tradeoff happens