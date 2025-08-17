---
{"publish":true,"created":"2025-08-16T12:21:13.773-04:00","modified":"2025-08-17T16:23:18.134-04:00","tags":["Coding/python"],"cssclasses":""}
---

If you’re [[Using __init__() with child class]], you will either have [[method overriding]], [[Manual Method Resolution]], or [[super()]]
	With either way, you can add [[python variables\|properties]] to the [[python class\|class]]
[[method overriding]] is just a complete different [[__init__() method]] 

With manual method resolution or super tho you just add [[parameter\|parameters]] specific to the [[child class]] and then add them after the line with [[super()]] or [[Manual Method Resolution]]

Example:
```python
class Student(Person):  
  def __init__(self, fname, lname):  
    super().__init__(fname, lname)  # also works with manual Method Resolution
    self.graduationyear = 2019
```
- Graduation year will automatically be 2019, to change this we must add a [[parameters in python\|parameter]] to the [[__init__() method]] of the student class

```python
class Student(Person):  
  def __init__(self, fname, lname, year):  
    super().__init__(fname, lname)  
    self.graduationyear = year  
  
x = Student("Mike", "Olsen", 2019)
```