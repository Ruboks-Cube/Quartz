---
{"publish":true,"created":"2025-08-16T10:47:13.000-04:00","modified":"2025-08-17T16:23:20.546-04:00","tags":["Coding/python"],"cssclasses":""}
---

[[Method Resolution]] is how you choose which [[Levels of MRO\|level of MRO]] the [[Method]] is called at
	(AKA which version of the [[Method]] is called) 
If you don’t want [[Method Resolution Order]] to happen (automatic), then you can do it manually
	All you have to do is have the method in your class with the same [[parameter\|parameters]] as the one you actually want to [[Calling a function in python\|call]], and then [[Calling a function in python\|call]] the one you actually want
An example is → [[Using __init__() with child class]] 

Basic syntax for doing:
```python
class someclass(otherlevelofMRO):
	def somemethod(self, parameters_of_method) # same parameters are required
		otherlevelofMRO.the_method_you_acc_wanna_call(self, parameters_of_method) # manually referring to another level of MRO
```
- This process essentially makes the “somemethod” [[Method]] into the “the_method_you_acc_wanna_call” method
	