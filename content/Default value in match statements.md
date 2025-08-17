---
{"publish":true,"created":"2025-07-25T08:25:01.000-04:00","modified":"2025-08-17T16:23:47.039-04:00","tags":["Coding/python"],"cssclasses":""}
---

- You may be wondering how you can do [[Else\|else]] in [[Python]] [[Match statement python\|Match statements]]
- This is where the default value comes in 
	- If there aren’t any other matches the default [[case in match statements\|case]] happens
- Use the `_` symbol for a default [[case in match statements\|case]]
```python
day = 4  
match day:  
  case 6:  
    print("Today is Saturday")  
  case 7:  
    print("Today is Sunday")  
  case _:  
    print("Looking forward to the Weekend")
```
- The default case should be at the *bottom* because it will always match
- If it was at the top the [[Match statement python\|match statement]] wouldn’t try the other cases
