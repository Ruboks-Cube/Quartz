---
{"publish":true,"created":"2025-08-05T18:05:32.000-04:00","modified":"2025-08-17T16:23:51.831-04:00","tags":["Coding/python"],"cssclasses":""}
---

You may or may not recall that when making a [[Python custom functions\|custom function]], anything after the `*` is [[keyword only arguments\|keyword only]] and anything before the `/` argument is a [[positional only arguments\|positional only]]
	Because when creating [[positional only arguments]] we put the `/` AFTER all the arguments
	When creating [[keyword only arguments]] we use the `*` BEFORE all arguments
So to combine their usage we do something like this:
```python
def my_function(a, b, /, *, c, d):  
  print(a + b + c + d)  
  
my_function(5, 6, c = 7, d = 8)
```
- Anything after the `*` is [[keyword only arguments\|keyword only]], anything before the `/` is [[positional only arguments\|positional only]] 