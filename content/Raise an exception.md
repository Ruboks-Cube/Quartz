---
{"publish":true,"aliases":"Raising a custom exception Raising an exception","created":"2025-08-01T09:57:51.000-04:00","modified":"2025-08-17T16:23:49.245-04:00","tags":["Coding/python"],"cssclasses":""}
---

We can use the [[Raise keyword\|Raise Keyword]] in order to raise a custom [[python except\|exception]]/[[python errors\|error]] 
	this is different from [[Python Try Except]]

- We use an [[if statement python\|if statement]] 
```python
# Raise an exception
x = -1  
  
if x < 0:  
  raise Exception("Sorry, no numbers below zero")
```

[[Define which error type to raise when raising an exception]]