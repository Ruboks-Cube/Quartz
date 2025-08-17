---
{"publish":true,"created":"2025-06-24T10:21:42.000-04:00","modified":"2025-08-17T16:23:38.106-04:00","cssclasses":""}
---

#Coding/python 


You can return a range of [[indexing\|indexes]] in a [[Sequence in coding\|sequence]] 

You just do the start [[indexing\|index]] and the end [[indexing\|index]] separated by a colon when you’re [[indexing]]
	The end index is not included when slicing

Slicing a [[list in coding\|list]]:
```python
a = [1, 2, 3, 4, 5, 6]
print(a[2:4]) #prints 3 4
print(a[:4]) #prints 1 2 3 4
print(a[2:]) #prints 3 4 5
sequence[start_index:end_index]
```

This works with [[negative indexing]] as well
```python
a = [1, 2, 3, 4, 5, 6]
print(a[-2:-4]) #prints 5 4 3
```

Since [[Strings are like arrays\|strings are sequences]] in [[Python]] you can [[slicing strings\|slice strings]]

