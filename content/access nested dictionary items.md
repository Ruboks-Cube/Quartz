---
{"publish":true,"created":"2025-07-20T12:44:06.000-04:00","modified":"2025-08-17T16:23:45.811-04:00","tags":["Coding/python"],"cssclasses":""}
---

In order to [[Access Dictionary Items]] from nested dictionaries we have to use the outer dictionary name first:
```python
print(myfamily["child1"]["name"]) #output: Emil
```
- You can see that we have the outer dictionary name, then the [[key in python dictionaries\|key]] for the nested dictionary, and finally the [[value in dictionary\|Value]]
- [[What happens if we don’t put the value after the key when accessing a nested dictionary]]