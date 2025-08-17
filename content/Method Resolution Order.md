---
{"publish":true,"aliases":"MRO","created":"2025-08-16T09:34:36.000-04:00","modified":"2025-08-17T16:23:20.140-04:00","tags":["Coding/python","Coding/ObjectOrientedProgramming"],"cssclasses":""}
---

Method resolution order is how [[method overriding]] in [[python class\|classes]] work → [[Method Resolution]] automatically in [[Python]]
	The order for [[method overriding]] is `[child, parent, object]`  → [[Levels of MRO]]
- This means that when you [[Calling a function in python\|call]] something, the program:
	1. First checks if it exists at the current level (child, parent, or object)
	2. If it doesn’t then it moves to the next level
	3. If it reaches object and no method is found then an error will happen
> [!important]
> Method resolution order only goes forward, so if you have a [[parent class]] 

- [[Using __init__() with child class\|What is an example of python using method resolution order?]]