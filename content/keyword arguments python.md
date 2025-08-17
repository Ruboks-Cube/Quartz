---
{"publish":true,"created":"2025-08-03T14:27:10.000-04:00","modified":"2025-08-17T16:23:50.786-04:00","tags":["Coding/python"],"cssclasses":""}
---

In [[Python]] we can send [[parameters in python\|arguments]] to our [[custom functions]] in [[key value pair\|key value pairs]] 

```python
def myfunc(child1, child2, child3):
	print("The youngest child is" + child3)
	
myfunc(child3 = "yapper", child1 = "hi!", child2 = "quiet")
```
This way the order we send our arguments does not matter.


What do you do if you don’t know how many keyword arguments you’ll use when calling the function?
	[[Arbitrary Keyword Arguments python]]

- [[keyword only arguments\|How can we make it so only keyword arguments are accepted?]]