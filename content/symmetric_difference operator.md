---
{"publish":true,"aliases":"^ operator","created":"2025-07-13T14:05:21.000-04:00","modified":"2025-08-17T16:23:42.300-04:00","tags":["Coding/python"],"cssclasses":""}
---

We can get the same effect of [[symmetric_difference()]] using the ^ operator

```python
set1 = {"apple", "banana", "cherry"}
set2 = {"google", "microsoft", "apple"}
set3 = set1 ^ set2
print(set3) #output {'microsoft', 'banana', 'google', 'cherry'} -> in any order since sets are unordered
```
The [[Joining sets using operator vs using method]] tradeoff happens