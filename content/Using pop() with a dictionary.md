---
{"publish":true,"created":"2025-07-20T11:43:12.000-04:00","modified":"2025-08-17T16:23:45.045-04:00","tags":["Coding/python"],"cssclasses":""}
---

Pop() removes an item from the [[Python Dictionaries\|Dictionary]] based on the [[key in python dictionaries\|key]]
	The key is the [[parameter]]
	[[Keys in dictionaries are like indexes for other collections]] 
```python
thisdict = {  
  "brand": "Ford",  
  "model": "Mustang",  
  "year": 1964  
}  
thisdict.pop("model")  
print(thisdict) # output: {'brand': 'Ford', 'year': 1964} the model is no longer a key
```
- [[popitem()]]