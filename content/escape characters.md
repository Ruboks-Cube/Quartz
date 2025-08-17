---
{"publish":true,"created":"2025-06-27T09:45:39.000-04:00","modified":"2025-08-17T16:23:36.495-04:00","cssclasses":""}
---

#Coding/python 


In [[Python]] use escape characters to insert characters that would otherwise be illegal in a [[Strings in Python\|string]]

Example:
```python
text = "we are the so-called "vikings" from the north" 
print(text) #returns an error you cannot have "" inside a string
```

However, you can use a “\” followed by the character you want to insert
```python
text = "we are the so-called \"vikings\" from the north"
print(text) #returns "we are the so-called "vikings" from the north"
```

There are other escape characters
	Some have the same functionality as allowing you to print an illegal character like “`\\`” or “`\'`”  
	Others have more functionality
[[New line in python\|\n]]
[[tab\|\t]]
[[carriage return\|\r]]

