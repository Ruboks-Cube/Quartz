---
{"publish":true,"created":"2025-07-02T19:13:41.000-04:00","modified":"2025-08-17T16:23:38.423-04:00","tags":["Coding/python"],"cssclasses":""}
---

Looping through lists in [[Python]] can be done using [[for loop in python\|for loops]] or [[while loop in python\|while loops]]
    [[looping through str in python]] → like this

[[Print()\|printing]] each item in a list with a [[for loop in python\|for loop]]:
```python
mylist = ["apples", "bananas", "oranges"]
for item in mylist:
		print(item) #prints apples, bananas, oranges
```

Looping through using [[indexing]] 
```python
mylist = ["apples", "bananas", "oranges"]
for i in range(len(mylist)):
		print(mylist[i]) #prints apples, bananas, oranges
```
[[range()]] with [[len()]] is used to get the [[indexing\|indexes]] of the list
	When we print we are printing the [[loop variable]] (which is the index) of the list

Using a [[while loop]] to loop through a list:
```python
mylist = ["apples", "bananas", "oranges"]
i = 0
while i < len(mylist):
		print(mylist[i]) #prints apples, bananas, oranges
		i += 1 #makes sure we don't loop forever
```


- Using [[list comprehension to loop through lists]]