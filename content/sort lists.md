---
{"publish":true,"aliases":"sort()","created":"2025-07-04T12:23:23.000-04:00","modified":"2025-08-17T16:23:38.938-04:00","tags":["Coding/python"],"cssclasses":""}
---

Using sort() will [[alphanumeric sorting\|alphanumerically]] sort items by default in a [[lists in python\|List]] → ascending by default

Sort this list alphabetically:
```python
mylist = ["banana", "cherry", "apple"]
mylist.sort()
print(mylist) #output ['apple', 'banana', 'cherry'
```

You can do descending by using the optional parameter `reverse=True`:   [[reverse = true in sorting]] 
```python
mylist = ["banana", "cherry", "apple"]
mylist.sort(reverse=True)
print(mylist) #output ['cherry', 'banana', 'apple'] Z-A sorting
```
By default sort is also case sensitive
```python
mylist = ["banana", "Cherry", "apple"]
mylist.sort()
print(mylist) #output ['Cherry', 'apple', 'banana'] → capital letters come before lowercase letters
```


[[customizing sort function]]
[[reverse()]]