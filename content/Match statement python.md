---
{"publish":true,"aliases":"Match statements match statement","created":"2025-07-21T19:35:28.000-04:00","modified":"2025-08-17T16:23:21.430-04:00","tags":["Coding/python"],"cssclasses":""}
---

Match statements are like [[if statement python\|if statements]] but they have [[case in match statements\|cases]] instead of [[condition in if statement\|conditions]] 
- [[Default value in match statements]]
- [[Combine cases in match statements]]
- [[Added conditionals in a match statement]]
- [[The ultimate match statement]]
	- [[complex cases match statements]]
Basic syntax:
```python
match _expression_:  
  case x:  
    code block  
  case y:  
    code block  
  case z:  
    code block
```
- The [[expression in match statements]] is just a [[variable in coding\|variable]] 
Example:
```python
day = 4  
match day:  
  case 1:  
    print("Monday")  
  case 2:  
    print("Tuesday")  
  case 3:  
    print("Wednesday")  
  case 4:  
    print("Thursday")  
  case 5:  
    print("Friday")  
  case 6:  
    print("Saturday")  
  case 7:  
    print("Sunday")
```




- Match statements have a similar looking structure to [[Python Try Except\|Try Except]] blocks with [[many exceptions]]