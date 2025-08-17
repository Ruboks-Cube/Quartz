---
{"publish":true,"created":"2025-06-30T18:33:14.000-04:00","modified":"2025-08-17T16:23:38.480-04:00","cssclasses":""}
---

#Coding/python 

Insert a new list item with .insert(), without replacing any other [[indexing\|index]]
	Instead of [[change list items\|replacing]] list items we’re INSERTING one at a certain [[indexing\|index]]
Basic syntax:
```python 
listname.insert(index, item) 
```
- Remember to use [[0 based indexing]] when figuring out the index 
	- You are changing the order of the list → [[what does ordered mean in a list -python\|What does ordered mean in a list]] 
 
Example of using insert()
```python
# Insert a new item at a specific index in a list
my_list = ['apple', 'banana', 'cherry']
my_list.insert(1, 'orange')  # Insert 'orange' at index 1
print(my_list)  # Output: ['apple', 'orange', 'banana', 'cherry']
```
- Notice how we use a “.”? → [[datatypes are just built-in classes]] 

If we insert at 2 this is what happens:
```python
my_list = ['apple', 'banana', 'cherry'] 
my_list.insert(2, 'orange') # Insert 'orange' at index 2 
print(my_list) # Output: ['apple', 'banana', 'orange', 'cherry'] 
```

> [!important]
> The [[element]] at [[indexing\|index]] 2 gets shifted to the right(to index 3) to make room for the new element 

[[doing append() with insert()]]

To see how you can use insert() to add smthn at the end look at [[append()]] note: