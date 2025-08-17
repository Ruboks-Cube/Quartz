---
{"publish":true,"created":"2025-07-26T18:24:29.000-04:00","modified":"2025-08-17T16:23:47.775-04:00","tags":["Coding/python"],"cssclasses":""}
---

## Using [[Continue statement\|continue keyword]]
The continue keyword can stop the current iteration like the [[Break statement\|break keyword]] but instead of stopping the entire loop it just goes to the next iteration
	“skips” an iteration if a [[condition in coding\|condition]] is true
```python
fruits = ["apple", "banana", "cherry"]  
for x in fruits:  
  if x == "banana":  
    continue  
  print(x)
```