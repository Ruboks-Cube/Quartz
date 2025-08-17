---
{"publish":true,"created":"2025-07-20T11:05:17.000-04:00","modified":"2025-08-17T16:23:44.080-04:00","tags":["Coding/python"],"cssclasses":""}
---

[[Built In Function\|Built in method]] that returns a [[lists in python\|List]] of the [[key in python dictionaries\|keys]] in a [[Python Dictionaries\|Dictionary]]
```python
thisdict = {  
  "brand": "Ford",  
  "model": "Mustang",  
  "year": 1964  
}
x = thisdict.keys()
print(x) # output: dict_keys(['brand', 'model', 'year'])
```

The list is a [[view in python\|view]] of the dictionary
	Any changes done to the dictionary applies to the list