---
{"publish":true,"created":"2025-07-20T12:04:41.000-04:00","modified":"2025-08-17T16:23:45.507-04:00","tags":["Coding/python"],"cssclasses":""}
---


- The basics of looping through a [[Python Dictionaries\|Dictionary]] is with a [[for loop]]
```python
mydictionary = {
	"hello" : "greeting"
	"Salutations" : "More advanced greeting"
	"welcome" : "Another greeting"
	"yyyyeellow!" : "informal greeting"
	"wsg" : "chill greeting"
}

for x in mydictionary:
	print(x) # prints all [[key in python dictionaries|keys]]
```

- In order to print all values:
```python
for x in mydictionary:
	print(mydictionary[x]) # x refers to the key so having mydictionary[x] is accessing the value
```

- You can also loop through the [[view in python\|views]] of a dictionary
	- [[keys()]] and [[values()]]
```python
for x in mydictinoary.keys():
	print(x)
```

- The [[items()]] [[view in python\|view]] is a little bit more complex 
	- It requires [[Multiple loop variables]]
```python
for x,y in mydictionary.items():
	print(x,y)
```
- x refers to the [[key in python dictionaries\|key]], y refers to the [[value in dictionary\|Value]] since [[items()]] returns a [[lists in python\|List]] of [[tuple\|tuples]]