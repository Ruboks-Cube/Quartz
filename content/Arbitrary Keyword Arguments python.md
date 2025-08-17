---
{"publish":true,"aliases":"**kwargs","created":"2025-08-04T08:40:15.000-04:00","modified":"2025-08-17T16:23:51.130-04:00","tags":["Coding/python"],"cssclasses":""}
---

If you don’t know how many [[parameters in python\|arguments]] will be passed into your [[Python custom functions\|custom function]] in [[Python]] then you can use *arbitrary keyword arguments* or `**kwargs` for short
```python
def my_function(**kid):
  print("His last name is " + kid["lname"])

my_function(fname = "Tobias", lname = "Refsnes")
```
- Combines the functionality of [[keyword arguments python]] and [[Arbitrary Arguments python\|Arbitrary arguments]]
