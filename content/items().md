---
{"publish":true,"created":"2025-07-20T11:15:12.000-04:00","modified":"2025-08-17T16:23:44.131-04:00","tags":["Coding/python"],"cssclasses":""}
---

Returns each item in a [[Python Dictionaries\|Dictionary]] as [[tuple\|tuples]] in a [[lists in python\|List]]
```python
thisdict = {  
  "brand": "Ford",  
  "model": "Mustang",  
  "year": 1964  
}
x = thisdict.items()
print(x) #output dict_items([('brand', 'Ford'), ('model', 'Mustang'), ('year', 1964)])
```

This is a [[view in python\|view]] of the [[Datatype]], just like [[keys()]] and [[values()]]