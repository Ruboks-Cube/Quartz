---
{"publish":true,"aliases":"Mulitple exceptions","created":"2025-07-27T20:54:34.000-04:00","modified":"2025-08-17T16:23:48.364-04:00","tags":["Coding/python"],"cssclasses":""}
---

In a [[Python Try Except\|try except]] [[control structure]] in [[Python]] you can have as many exceptions as you want
```python
try:  
  print(x)  
except NameError:  
  print("Variable x is not defined")  # if name error
except:  # if error in general
  print("Something else went wrong")
```
- [[NameError]]
- It’s kind of like a [[Match statement python\|match statement]] *specifically* for errors