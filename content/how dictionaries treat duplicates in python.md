---
{"publish":true,"created":"2025-07-20T09:51:26.000-04:00","modified":"2025-08-17T16:23:44.181-04:00","tags":["Coding/python"],"cssclasses":""}
---

[[duplicates are not allowed in sets]], and they aren’t allowed in [[Python Dictionaries\|Dictionaries]] as well
	A duplicate occurs when there are two of the same [[key in python dictionaries\|key]] 
	You can think of dictionaries as a [[math functions\|function]] with [[Input]] and [[Output]]
- The same input cannot have 2 different outputs
	- The same key cannot have 2 different values
	- The “earlier” key will be overwritten
```python
thisdict = {  
  "brand": "Ford",  
  "model": "Mustang",  
  "year": 1964,  
  "year": 2020  # duplicate
}  
print(thisdict) # output {'brand': 'Ford', 'model': 'Mustang', 'year': 2020} -> 1964 was overwritten
```