---
{"publish":true,"created":"2025-07-13T13:59:31.000-04:00","modified":"2025-08-17T16:23:42.083-04:00","tags":["Coding/python"],"cssclasses":""}
---

We can use the - operator in place of the [[difference()]] method
```python
set1 = {"apple", "banana", "cherry"}  
set2 = {"google", "microsoft", "apple"}  
  
set3 = set1 - set2  
print(set3) # output: {'banana', 'cherry'} -> in any order since sets are unordered
```

In exchange for a slightly cleaner syntax we lose the ability to differentiate different [[Datatype\|datatypes]]
	[[Joining sets using operator vs using method]]