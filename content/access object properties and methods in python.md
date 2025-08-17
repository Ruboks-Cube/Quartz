---
{"publish":true,"created":"2025-08-12T08:39:27.000-04:00","modified":"2025-08-17T16:23:18.894-04:00","tags":["Coding/python"],"cssclasses":""}
---

In [[Python]] we [[Accessing sub variables with the dot\|access variables and methods of an instance from a class with a dot]] 
```python
class myclass:
	x = 5 # variable of the class
	func randommethod() #method of class
		 print("Hello world")

myobject = myclass()
print(myobject.x) # notice the dot, output is 5
print(myobject.randommethod) # output: Hello world
```

- [[changing object properties in python]]
- [[deleting object properties in python]]
- [[deleting an object in python]]