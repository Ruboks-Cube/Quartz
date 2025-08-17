---
{"publish":true,"aliases":"Custom class method","created":"2025-08-12T08:27:56.000-04:00","modified":"2025-08-17T16:23:19.276-04:00","tags":["Coding/python"],"cssclasses":""}
---

We can create our own [[Python custom functions\|custom functions]] inside [[python class\|classes]] 
	they are used for [[Creating an object in python\|object-specific use cases]] 
Example:
```python
class Person:
	def __init__(self, name, age):
	    self.name = name
	    self.age = age
	def myfunc(self): # we define a function in the class
	    print("Hello my name is " + self.name) 

p1 = Person("John", 36)
p1.myfunc() # output Hello my name is John
```
- [[self parameter in classes]] 
- We can use these for [[Changing object properties with a class method]]