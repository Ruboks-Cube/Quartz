---
{"publish":true,"aliases":"complex case","created":"2025-07-25T14:35:21.000-04:00","modified":"2025-08-17T16:23:47.360-04:00","tags":["Coding/python"],"cssclasses":""}
---

Complex cases are ones that apply to multiple [[expression in match statements\|expression]] values and [[Added conditionals in a match statement\|use an if statement]] in order to filter it out what the case applies to

Here is an example: 
```python
 match day:  
  case 1 | 2 | 3 | 4 | 5 if mood = good:  
    print("Today is a  nice weekday")  
  case 6 | 7 if mood = good:  
    print("I love weekends!")
```
- [[Complex default in match statements]] 