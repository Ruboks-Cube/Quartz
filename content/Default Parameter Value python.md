---
{"publish":true,"created":"2025-08-04T08:45:06.000-04:00","modified":"2025-08-17T16:23:50.396-04:00","tags":["Coding/python"],"cssclasses":""}
---

The default [[parameters in python\|parameter]] value is what the parameter will be assigned if when the [[Python custom functions\|custom function]] is [[calling functions\|called]] the parameter slot is empty
```python
def my_function(country = "Norway"):  
  print("I am from " + country)  
  
my_function("Sweden")  
my_function("India")  
my_function()  
my_function("Brazil")
```
We set the parameter to a [[key value pair]] 
	This is what it equals unless you change it