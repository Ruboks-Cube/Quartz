---
{"publish":true,"created":"2025-08-12T08:32:05.000-04:00","modified":"2025-08-17T16:23:18.797-04:00","tags":["Coding/python"],"cssclasses":""}
---

The self [[parameters in python\|parameter]] is a reference to the current [[instance]]
- It is used to access [[variables in python\|variables]] of the [[Creating an object in python\|object]] of the [[python class\|class]]

- *self* is a required [[parameters in python\|parameter]] and is always required to be the first [[parameters in python\|parameter]] of any [[Custom class methods]]
	- It doesn’t have to be *self* but it has to be the first parameter in any function of the [[python class\|class]]

```python
Use the words mysillyobject and abc instead of self:
class Person:  
  def __init__(mysillyobject, name, age):  
    mysillyobject.name = name  
    mysillyobject.age = age  
  
  def myfunc(abc):  
    print("Hello my name is " + abc.name)  
  
p1 = Person("John", 36)  
p1.myfunc()
```
- [[Arbitrary Arguments python\|Arbitrary argument]]