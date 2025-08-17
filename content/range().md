---
{"publish":true,"created":"2025-06-23T11:38:14.000-04:00","modified":"2025-08-17T16:23:46.778-04:00","cssclasses":""}
---

#Coding/python 


The range function in [[Python]] generates a [[sequence in python\|sequence]] of numbers

Works with [[iteration control structure\|loops]] ([[for loop]])

## Range parameters
Range has different [[parameter\|parameters]]
```python
range(start, stop, step):
```
Range’s default start is 0, the start parameter changes this


In `range(stop)`, it generates from 0 till (not including) the stop value
```python
for i in range(5):
	print(i) #prints 0, 1, 2, 3, 4
	# 5 is not included
```

start parameter sets the starting point 
	The stop parameter sets the end point (not included)
```python
for i in range(2, 5): #start = 2, stop = 5
	print(i) #prints 2, 3, 4
	# 5 is not included
```

The step parameter is by how much to increase each time
```python
for i in range(0,10,2): #start = 0, stop = 10, step = 2
	print(i) #prints, 0, 2, 4, 6,8
```
- All these are using [[for loop in python\|for loops]]

## converting a range list
Range only works in loops or when converting to a [[lists in python\|List]]
Converting to a list will give you the sequence of numbers
```python
print(list(range(5))) #prints [0, 1, 2, 3, 4]
```