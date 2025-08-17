---
{"publish":true,"created":"2025-08-12T08:22:35.000-04:00","modified":"2025-08-17T16:23:18.702-04:00","tags":["Coding/python"],"cssclasses":""}
---

`__str__()` is a [[Built In Function\|Built in method]] for [[python class\|classes]] 
- Assigns what is [[Return in python\|Returned]] when the [[Creating an object in python\|object]] is represented as a [[Strings in Python\|string]]

Without str:
```python
class Person:
  def __init__(self, name, age):
    self.name = name
    self.age = age

p1 = Person("John", 36)

print(p1) # output <__main__.Person object at 0x...>
```


With str:
```python
class Person:  
  def __init__(self, name, age):  
    self.name = name  
    self.age = age  
  
  def __str__(self):  
    return f"{self.name}({self.age})"  
  
p1 = Person("John", 36)  
  
print(p1) # output John(36)
```
- Use [[format strings python\|f-strings]] to use certain variables with the `__str__()` method