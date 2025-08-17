---
{"publish":true,"created":"2025-08-11T18:30:07.000-04:00","modified":"2025-08-17T16:23:19.804-04:00","tags":["Coding/python"],"cssclasses":""}
---

The `__init__()` [[Built In Function\|Built in method]] is used almost in all *real* useful classes
	The examples in the [[python class\|classes]] notes are very basic and not really useful
It stands for initialize, and gets [[Calling a function in python\|Called]] automatically every time you [[Creating an object in python\|create an object from a class with the init method]] 


```python
class Person:  
  def __init__(self, name, age):  
    self.name = name 
    self.age = age  
  
p1 = Person("John", 36)  # creating a class calls __init__() with its parameters
  
print(p1.name)  
print(p1.age)
```
- [[self parameter in classes]] 

- [[__str__()\|what’s another example of a built in method for classes?]] 
- [[Using __init__() with child class\|how do we keep parent properties when using __init__()?]] 