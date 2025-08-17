---
{"publish":true,"created":"2025-08-07T17:07:26.000-04:00","modified":"2025-08-17T16:23:52.519-04:00","tags":["Coding/python"],"cssclasses":""}
---

- [[Python Lambda]] is useful when you want to use an [[anonymous function]] for a short period of time

Here is an example:
```python
def myfunc(n):  
  return lambda a : a * n  
  
mydoubler = myfunc(2)  
mytripler = myfunc(3)  
  
print(mydoubler(11))  
print(mytripler(11))
```
-  `mydoubler = myfunc` when `n=2`
	- This basically means that `mydoubler = a: a*2` 
- `mytripler=myfunc` when `n=3`
	- This basically means that `mytripler= a: a*3`
- It’s a lot cleaner than making [[Python custom functions\|custom functions]] for each use case