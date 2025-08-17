---
{"publish":true,"created":"2025-06-28T13:53:59.000-04:00","modified":"2025-08-17T16:23:36.708-04:00","tags":["Coding/python"],"cssclasses":""}
---

The bool function allows you to evaluate any value

Most values are true
```python
print(bool("hello")) #returns true
```

Only these values are false:
```python
bool(())
bool([])
bool({})
bool("")
bool(0)
bool(None)
bool(False)
```


There is one more value that can be false
That is if you use the [[len()]] function and make it return 0 in a [[class]]
```python
class myclass():
	def __len__(self) #defining a function that gives the "length" of the instance
		return 0 #telling that the length is 0
myobj = myclass() #creating an instance
print(bool(myobj)) #using bool() automatically goes to the __len__ function, since it equals 0 this returns false


```