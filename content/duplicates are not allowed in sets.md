---
{"publish":true,"created":"2025-07-11T19:19:25.000-04:00","modified":"2025-08-17T16:23:43.664-04:00","tags":["Coding/python"],"cssclasses":""}
---

You cannot have the same value in [[set in python\|sets]]

[[python bool\|True]] and 1 are the same value in sets
[[python bool\|False]] and 0 are the same value

Sets simply ignore duplicates
```python
my_set = {1, 2, 3} my_set.add(2) # Adding a duplicate print(my_set) # Output: {1, 2, 3}
```
This differs to [[how dictionaries treat duplicates in python]] as they have the added component of a [[key value pair]] 
