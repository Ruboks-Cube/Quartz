---
{"publish":true,"created":"2025-08-01T10:04:33.000-04:00","modified":"2025-08-17T16:23:49.092-04:00","tags":["Coding/python"],"cssclasses":""}
---

When [[Raise an exception\|Raising an exception]] we can choose which [[python except\|error]] to raise
	[[Exception error types]]
- We still used an [[if statement python\|if statement]] using [[‘not’ in python\|not]] 
```python
x = "hello"

if not type(x) is int:
  raise TypeError("Only integers are allowed")
```
- Instead of saying “raise exception” we say “raise TypeError”