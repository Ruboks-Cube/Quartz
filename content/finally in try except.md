---
{"publish":true,"created":"2025-07-31T13:00:38.000-04:00","modified":"2025-08-17T16:23:48.686-04:00","tags":["Coding/python"],"cssclasses":""}
---

Finally in [[Python Try Except\|Try Except]] executes after, regardless of whether there is an [[python errors\|error]] or not
```python
try:
  print(x)
except:
  print("Something went wrong")
finally:
  print("The 'try except' is finished")
```
This is useful if the try statement changes something and you want it not to be changed after
- Cleaner coding