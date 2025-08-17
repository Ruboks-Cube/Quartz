---
{"publish":true,"aliases":"arguments in python parameter arguments args","created":"2025-08-02T06:45:08.000-04:00","modified":"2025-08-17T16:23:51.498-04:00","tags":["Coding/python"],"cssclasses":""}
---

[[parameter\|parameters]] and arguments are basically the same thing in [[Python]]
- Parameters are the variables listed in the [[Python custom functions\|custom function]] definition
- [[Arguments in python]] are what’s sent to the function when its [[calling functions\|called]]

Define a parameter in the parenthesis when creating a function

```python
# Function to print the full name
def my_function(**fname**):  
  print(fname + " Refsnes")  
  
my_function(**"Emil"**)  
my_function(**"Tobias"**)  
my_function(**"Linus"**)
```
- [[Default number of arguments]]
- [[Arbitrary Arguments python]]
- [[positional arguments\|What are positional arguments?]]
	- [[positional only arguments\|How can I accept only positional arguments?]]
- [[keyword arguments python]]
	- [[keyword only arguments\|How can I accept only keyword arguments?]]
- [[combine positional and keyword only arguments\|How can I have both positional only and keyword only arguments??]]
- [[Default Parameter Value python\|How can I set a default parameter value?]]