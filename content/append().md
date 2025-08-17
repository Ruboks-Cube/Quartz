---
{"publish":true,"created":"2025-06-30T18:38:15.000-04:00","modified":"2025-08-17T16:23:38.667-04:00","cssclasses":""}
---

#Coding/python 

This is like [[insert()]] but it always adds the item to the END of the list
```python
mylist = ["apples" , "bananas", "oranges"]
mylist.append("pears") #we add pears to the back of the list
print(mylist) # prints: ['apples', 'bananas', 'oranges', 'pears']
 ```
This is kind of like [[String Concatenation\|concatenation]] but for [[lists in python\|lists]] 

[[doing append() with insert()]]

You can create the same affects of [[extend()]] with [[append()]] and [[insert()]] in a loop → [[for loop in python]]
```python
mylist = ["apples" , "bananas", "oranges"]
anotherlist = ["pears", "grapes"]
for item in anotherlist:
		mylist.append(item) #append each item from anotherlist to mylist
```

With [[insert()]] it would look like this:
```python
mylist = ["apples" , "bananas", "oranges"]
anotherlist = ["pears", "grapes"]
for item in anotherlist:
		mylist.insert(len(mylist), item) #insert each item from anotherlist to the end of mylist
```
