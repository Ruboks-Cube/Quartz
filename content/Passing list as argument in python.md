---
{"publish":true,"created":"2025-08-04T08:50:10.000-04:00","modified":"2025-08-17T16:23:50.641-04:00","tags":["Coding/python"],"cssclasses":""}
---

This is an example of [[Passing different datatypes through a function]]
	How to do it with a list? 
	One of the most common use cases is just passing through the function to use a [[for loop]] → [[for loop in python\|for loop]]
```python
mybasket = ["apples" , "oranges", "bananas"]
def availablefood(food)
	for x in food
		if x = "apples"
			pass
		print(x) 
availablefood(mybasket) # this will print each item in the list except "apples"
```