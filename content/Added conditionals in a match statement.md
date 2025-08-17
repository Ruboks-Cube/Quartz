---
{"publish":true,"aliases":"use an if statement","created":"2025-07-25T13:55:07.000-04:00","modified":"2025-08-17T16:23:46.625-04:00","tags":["Coding/python"],"cssclasses":""}
---

So basically you can add an [[if statement python\|if statement]] to the end of a [[Match statement python\|match statement]] [[case in match statements\|case]]
```python
day = 1
month = "july"
match day:
	case 1 if month = "july":
		print("Monday in July")
	case 2 if month = "july":
		print("tuesday in July")
	case 3 if month != "july":
		print("wednesday not in july")
```

This also works if it’s a [[Combine cases in match statements\|combined case]], creating a [[complex cases match statements\|complex case]]
```python
  case 1 | 2 | 3 | 4 | 5 if month == 5:  
    print("A weekday in May")
```