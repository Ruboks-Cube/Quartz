---
{"publish":true,"aliases":"joining multiple sets using union() joining multiple sets using union operator","created":"2025-07-13T13:27:43.000-04:00","modified":"2025-08-17T16:23:41.687-04:00","tags":["Coding/python"],"cssclasses":""}
---

The [[union()]] [[Method]] can take multiple [[parameter\|parameters]]
	Therefore you can join multiple sets at a time
```python
set1 = {"a", "b", "c"}
set2 = {4, 2, 3} # originally was 1 but "1" and "True" are seen as duplicate values in sets
set3 = {True, False}
set4 = {"happy", "trees"}

set5 = set1.union(set2, set3, set4)
print(set5) #output {'happy', 2, 3, 'a', False, 'c', True, 4, 'b', 'trees'} -> in any order since sets are unordered
```
> [!fail]
> The comment about replacing 1 with 4 is actually false because [[Both union() and update() exclude duplicates]]


You can also use the [[union operator]] for the same effect:
```python
set1 = {"a", "b", "c"}
set2 = {4, 2, 3} # originally was 1 but "1" and "True" are seen as duplicate values in sets
set3 = {True, False}
set4 = {"happy", "trees"}

set5 = set1 | set2 | set3 | set4

print(set5) # output {'happy', 2, 3, 'a', False, 'c', True, 4, 'b', 'trees'} -> in any order since sets are unordered
```