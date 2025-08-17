---
{"publish":true,"created":"2025-07-01T11:34:01.000-04:00","modified":"2025-08-17T16:23:38.032-04:00","tags":["Coding/python"],"cssclasses":""}
---



The del keyword can remove a specific [[indexing\|index]] or delete the entire [[list in coding\|list]] → it can delete a [[variable in coding\|variable]]

deleting a specific index using del: 
```python 
thislist = ["apple", "banana", "cherry"] 
del thislist[0]  
print(thislist) #returns ['banana', 'cherry'] 
``` 

deleting the entire list using del: 
```python
thislist = ["apple", "banana", "cherry"]
del thislist #not specifying an index deletes entire list
print(thislist) #returns error as list no longer exists
```