---
{"publish":true,"created":"2025-07-20T12:42:28.000-04:00","modified":"2025-08-17T16:23:45.358-04:00","tags":["Coding/python"],"cssclasses":""}
---

- Instead of creating the [[Nest dictionaries\|nested dictionaries]] inside a [[Python Dictionaries\|Dictionary]] we can also create multiple [[Python Dictionaries\|Dictionaries]] and refer them as [[value in dictionary\|Value]]
	- Another way is to create 3 dictionaries first and then nest them
```python
child1 = {
	"name" : "Emil",
	"year" : 2004
}
child2 : {  
    "name" : "Tobias",  
    "year" : 2007  
}
child3 : {  
    "name" : "Linus",  
    "year" : 2011 
}

myfamily = {
	"child1" : child1,
	"child2" : child2,
	"child3" : child3
}
```
- [[Playing backwards in violin]]