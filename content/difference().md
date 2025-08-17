---
{"publish":true,"created":"2025-07-13T13:57:26.000-04:00","modified":"2025-08-17T16:23:42.859-04:00","tags":["Coding/python"],"cssclasses":""}
---

The difference() [[Method]] only returns the values of the first [[set in python\|set]] that aren’t present in any of its [[parameter\|parameters]]
```python
set1 = {"apple", "banana", "cherry"}  
set2 = {"google", "microsoft", "apple"}  
  
set3 = set1.difference(set2)  
  
print(set3) # output:{'banana', 'cherry'} -> in any order since sets are unordered
```

We can use the [[- operator]] instead and get the same result
	[[Joining sets using operator vs using method]]
[[difference_update()]]