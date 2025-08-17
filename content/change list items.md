---
{"publish":true,"created":"2025-06-30T18:09:30.000-04:00","modified":"2025-08-17T16:23:40.235-04:00","tags":["Coding/python"],"cssclasses":""}
---

Use the [[indexing\|index]] number of a [[lists in python\|List]] [[Element in array\|Element]] to change it
```python
mylist = ["apples", "bananas", "oranges"]
mylist[1] = "pears"  # Change the second item
print(mylist)  # Returns ["apples", "pears", "oranges"]
```

You can change a range of items by using [[slicing sequences in python\|slicing]]
```python
mylist = ["apples", "bananas", "oranges"]
mylist[1:3] = ["pears", "grapes"]  # Change the second and third items
print(mylist)  # Returns ["apples", "pears", "grapes"]
```
Banana’s and oranges get replaced

Change the second and third [[indexing\|indexes]] to a single value:
```python
mylist = ["apples", "bananas", "oranges"]
mylist[1:3] = ["pears"]  # Change the second and third items to a single item
print(mylist)  # Returns ["apples", "pears"]
```
As you can see the length of the [[lists in python\|List]] can change due to [[slicing sequences in python\|slicing]] method
	

You can also change the entire list by assigning a new list to it
```python
mylist = ["apples", "bananas", "oranges"]
mylist[:] = ["pears", "grapes"]  # replace the entire list with these items
print(mylist) #returns ["pears", "grapes"]
```

- [[insert()]]
	- [[len()]]
- [[append()]]
