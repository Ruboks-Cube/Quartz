---
{"publish":true,"created":"2025-07-13T13:25:57.000-04:00","modified":"2025-08-17T16:23:41.630-04:00","tags":["Coding/python"],"cssclasses":""}
---

An alternative to the [[union()]] method to [[Join sets]]
```python
set1 = {"a", "b", "c"}
set2 = {1, 2, 3}

set3 = set1.union(set2)
print(set3) # output {'a', 1, 2, 3, 'c', 'b'} -> in any order since sets are unordered
```

You can get the same result with:
```python
set1 = {"a", "b", "c"}
set2 = {1, 2, 3}

set3 = set1 | set2
print(set3) # output {'a', 1, 2, 3, 'c', 'b'} -> in any order since sets are unordered
```

[[difference between union() and union operator]]
> [!error]
>```python
>x = {"a", "b", "c"}
>y = (1, 2, 3)
>z = x | y
>print(z) # output TypeError: unsupported operand type(s) for |: 'set' and 'tuple'
>```

