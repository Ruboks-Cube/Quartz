---
{"publish":true,"created":"2025-08-12T08:46:03.000-04:00","modified":"2025-08-17T16:23:19.096-04:00","tags":["Coding/python"],"cssclasses":""}
---

Instead of manually [[changing object properties in python]], we can do so with a [[Custom class methods\|Custom class method]]
	These are useful if you want to change many at a time, or if you want to standardize what you can change each property to
> [!hint]
> We can also have a [[Custom class methods\|Custom class method]] [[deleting object properties in python\|delete a property]] itself (probably)

One use case would be like for a task manager with todos
	One change to how you mark the “incomplete” status in the class will be standardized throughout the program
```python
class todo:
	def __init__(self, name, status)
		self.name = name
		self.status = "incomplete"
	def completetask(self)
		self.status = "complete"
	def incompletetask(self)
		self.status = "incomplete"
newtodo = todo()
newtodo.completetask() # status will be "complete"
```