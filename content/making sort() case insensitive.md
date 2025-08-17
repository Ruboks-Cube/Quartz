---
{"publish":true,"created":"2025-07-04T13:12:23.000-04:00","modified":"2025-08-17T16:23:39.220-04:00","tags":["Coding/python"],"cssclasses":""}
---

In order to [[customizing sort function\|customize sort functions]] so they are case insensitive, we can use the `key` [[parameter]] of the `sort()` method to create a ghost list of the original items in lowercase and sort based on that
```python
mylist = ["banana", "Cherry", "apple"]
mylist.sort(key=str.lower) # first creates a ghost list of the original items in lowercase
print(mylist) #output ['apple', 'banana', 'Cherry']
```
