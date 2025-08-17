---
{"publish":true,"created":"2025-08-16T08:57:53.517-04:00","modified":"2025-08-17T16:23:18.511-04:00","tags":["Coding/python"],"cssclasses":""}
---

 The [[__init__() method]] of the child overrides the parent class’s __init__
	This means that if the [[child class]] has the [[__init__() method]], then it doesn’t [[python inheritance\|inherit]] that anymore from the [[parent class]]
In order to keep the inheritance of `__init__()` [[Calling a function in python\|call]] the `__init__()` of the [[parent class]] inside the [[child class]]

Example with [[Manual Method Resolution]]
```python
class child(parent):
	def __init__(self, parentarg1, parentarg2) # still need parameters of parent class for it to work
		def parent.__init__(self, parentarg1, parentarg2)
```
Example with [[super()]]
```python
class child(parent)
	def __init__(self, parentarg1, parentarg2)
		super().__init__(parentarg1, parentarg2)
```
- [[Method Resolution Order\| How does the child override the parent?]]
	- [[Method Resolution]]
	- [[method overriding]]