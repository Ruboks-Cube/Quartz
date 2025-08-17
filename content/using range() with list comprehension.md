---
{"publish":true,"created":"2025-07-03T15:46:52.000-04:00","modified":"2025-08-17T16:23:42.997-04:00","tags":["Coding/python"],"cssclasses":""}
---

We can create a list of numbers using `range()` in a list comprehension
```python
mylist = [x for x in range(10)]  # Creates a list of numbers from 0 to 9]
```

We can add a [[Condition in list comprehension\|condition]]]] to do this as well
```python
mylist = [x for x in range(10) if x % 2 == 0]  # Creates a list of even numbers from 0 to 9]
```
[[Modulus]]
