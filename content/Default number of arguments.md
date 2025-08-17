---
{"publish":true,"aliases":"Number of arguments matters when calling a function","created":"2025-08-02T16:21:22.000-04:00","modified":"2025-08-17T16:23:51.050-04:00","tags":["Coding/python"],"cssclasses":""}
---

By default, when [[Calling a function in python]] it must be called with the same number of [[parameters in python\|arguments]] as [[parameter\|parameters]]
	You get around this with [[Arbitrary Arguments python]]
	[[Arguments in python\|Difference between argument and parameter]]
Example:
```python
def my_function(fname, lname):  # 2 parameters
  print(fname + " " + lname)  
  
my_function("Emil", "Refsnes") # 2 arguments
```
[[Code errors\|error]] Example:
```python
def my_function(fname, lname):
  print(fname + " " + lname)

my_function("Emil") #TypeError
```
- A [[TypeError]] is raised
This can be changed:
- [[Arbitrary Arguments python]]

Additionally, the order matters in this scenario because how else would the function know which [[parameters in python\|parameter]] is which?
	This can also be changed:
- [[keyword arguments python]]