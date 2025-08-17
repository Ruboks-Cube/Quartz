---
{"publish":true,"created":"2025-07-27T20:56:52.000-04:00","modified":"2025-08-17T16:23:48.813-04:00","tags":["Coding/python"],"cssclasses":""}
---

In [[Python Try Except]] blocks, you can choose the type of [[Code errors\|error]] that triggers each [[many exceptions\|exception]]
`except:` without a error type will just carry out the code no matter the error unless another [[python except\|exception]] is carried out
	This can be used when [[Raise an exception\|Raising a custom exception]]
```python
# different error types
try:
  print(x)
except NameError: # different error type
  print("Variable x is not defined")
except: # default error type
  print("Something else went wrong")
```
- And here we used [[many exceptions\|Mulitple exceptions]]

- [[python errors]] → For a list of exceptions
	- [[NameError]]
