---
{"publish":true,"created":"2025-07-04T13:16:04.000-04:00","modified":"2025-08-17T16:23:39.957-04:00","tags":["Coding/python"],"cssclasses":""}
---


Reverse the order of a list with the `reverse()` method
```python
mylist = ["banana", "cherry", "apple"]
mylist.reverse()
print(mylist) #output ['apple', 'cherry', 'banana']
```

This is different from [[reverse = true in sorting]] which sorts the items in descending order instead of simply reversing the order of the items.
```python
mylist = ["banana", "cherry", "apple"]
mylist.sort(reverse=True)
print(mylist) #output ['cherry', 'banana', 'apple'] Z-A sorting
```

This method does not sort the items; it just reverses their order.
```python
mylist = [3, 1, 2]
mylist.reverse()
print(mylist) #output [2, 1, 3]
```