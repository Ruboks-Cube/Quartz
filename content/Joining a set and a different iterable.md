---
{"publish":true,"created":"2025-07-13T13:32:43.000-04:00","modified":"2025-08-17T16:23:41.745-04:00","tags":["Coding/python"],"cssclasses":""}
---

You can join a [[set in python\|set]] with a different [[iterable]] in [[Python]] using the [[union()]] method
```python
x = {"a", "b", "c"}
y = (1, 2, 3)

z = x.union(y)
print(z)  # output {'a', 1, 2, 3, 'c', 'b'} -> in any order since sets are unordered
```

- [[difference between union() and union operator]]