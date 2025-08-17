---
{"publish":true,"created":"2025-08-16T11:49:23.000-04:00","modified":"2025-08-17T16:23:18.419-04:00","tags":["Coding/python"],"cssclasses":""}
---

super() is a [[Method]] that can make a [[child class]] or lower [[Levels of MRO\|Level of MRO]] inherit from a higher level like a [[parent class]]
	It’s a way to use [[Method Resolution Order]] instead of [[Manual Method Resolution]]
Here is an example:
```python
class Student(Person):  
  def __init__(self, fname, lname):  
    super().__init__(fname, lname)
```
The higher level right after is the [[parent class]] “person” and super takes the method from there using [[Method Resolution Order]]
- [[You don’t need self when using super()]]
