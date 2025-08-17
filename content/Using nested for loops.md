---
{"publish":true,"created":"2025-07-26T18:26:12.000-04:00","modified":"2025-08-17T16:23:47.616-04:00","tags":["Coding/python"],"cssclasses":""}
---

## [[Nested Loops]] with for loops
We can nest [[for loop in python\|for loops]], meaning that loops can be inside each other
	[[Nested Loops]]
```python
adj = ["red", "big", "tasty"]
fruits = ["apple", "banana", "cherry"]

for x in adj:
  for y in fruits:
    print(x, y)
'''every single output:
red apple
red banana
red cherry
big apple
big banana
big cherry
tasty apple
tasty banana
tasty cherry
'''
```