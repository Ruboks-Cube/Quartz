---
{"publish":true,"created":"2025-07-20T11:39:04.000-04:00","modified":"2025-08-17T16:23:44.500-04:00","tags":["Coding/python"],"cssclasses":""}
---

It’s like [[remove()]] but instead refers to an [[indexing\|index]] rather than an item
	also returns the removed item

example: 
```python 
thislist = ["apple", "banana", "cherry"] 
print(thislist.pop(1)) # removes and returns 'banana'
print(thislist) #returns ['apple', 'cherry'] 

``` 

if you don’t specify an index, pop() removes the last item
```python  
thislist = ["apple", "banana", "cherry"] 
thislist.pop() 
print(thislist) #returns ['apple', 'banana'] 
```