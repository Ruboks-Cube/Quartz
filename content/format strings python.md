---
{"publish":true,"aliases":"format() method f-strings format() f-string","created":"2025-06-26T01:15:35.000-04:00","modified":"2025-08-17T16:23:22.796-04:00","tags":["Coding/python"],"cssclasses":""}
---

We know that we cannot do something like this:
```python
age = 36  
txt = "My name is John, I am " + age  
print(txt) #returns error
```

As a solution to this, we can create an f-string
	Create an f-string by putting an f before the string
	use “{}” as placeholders for [[variable in coding\|variables]] and [[operators in code\|operators]]
```python
price = 54
output = f"The price is {price} dollars"
print(output) #Returns "The price is 54 dollars"
```

You can also do [[operators in code\|operators]]
```python
print("It's been {7*12} months!")
```

```python

price = 9.59
output = f"The price is {price:.2f} dollars"
print(output)
```
This one has a [[placeholder modifier]]

- [[__str__()\|They are useful with the __str__()]] method