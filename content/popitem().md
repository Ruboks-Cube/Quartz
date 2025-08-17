---
{"publish":true,"created":"2025-07-20T11:51:57.000-04:00","modified":"2025-08-17T16:23:45.205-04:00","tags":["Coding/python"],"cssclasses":""}
---

Used to remove the last-added [[key value pair]]/[[key value pair\|item]] of a [[Python Dictionaries\|Dictionary]]
	[[Dictionaries used to be unordered]] → so this used to just [[pop()]] a random item
```python
thisdict = {
  "brand": "Ford",
  "model": "Mustang",
  "year": 1964 # -> last added item
}
thisdict.popitem()
print(thisdict) # output {'brand': 'Ford', 'model': 'Mustang'}
```