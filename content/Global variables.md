---
{"publish":true,"created":"2025-06-20T09:32:17.000-04:00","modified":"2025-08-17T16:23:31.885-04:00","cssclasses":""}
---

#Coding 

- [[variable in coding\|variables]] that are declared outside a [[Functions in coding\|function]]

- If a variable is created inside a function then it can only be used by that function
	- ([[local variable]] → [[Local in Lua]]??)
- However, if you want the variable to be used everywhere (become a global variable) use the **global** keyword
```python
def randomfunc():
	global x = 5 #x is now a global variable
	print(x)
print(x) #x can be printed outside the function
#Lack of indentation shows how the second print(x) is outside the function
```

```python
# Refer to a global variable with global keyword
x = 5

def randomfunc():
	global x = 6 #change the value of x to 6
print(x)
```