---
{"publish":true,"created":"2025-07-01T10:24:09.000-04:00","modified":"2025-08-17T16:23:43.585-04:00","tags":["Coding/python"],"cssclasses":""}
---

Used to add [[Element in array\|Elements]] from another [[lists in python\|List]] to the current list (or any other [[iterable]])
	It’s like [[append()]] but on a larger scale
Basic syntax:
```python 
listname.extend(iterable) 
``` 

example with lists:
```python 
# Extend a list with elements from another iterable 
my_list = ['apple', 'banana', 'cherry'] 
another_list = ['orange', 'grape'] 
my_list.extend(another_list)  
# print(my_list) # Output: ['apple', 'banana', 'cherry', 'orange', 'grape'] 
```

example with [[Python Dictionaries\|dictionaries]]:
```python 
# Extend Extend a list with keys from a dictionary 
my_list = ['apple', 'banana', 'cherry'] 
my_dict = {'key1': 'value1', 'key2': 'value2'} 
my_list.extend(my_dict)  
# print(my_list) # Output: ['apple', 'banana', 'cherry', 'key1', 'key2'] ``` 
