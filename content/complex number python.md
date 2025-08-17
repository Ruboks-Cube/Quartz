---
{"publish":true,"created":"2025-06-20T09:45:55.000-04:00","modified":"2025-08-17T16:23:32.082-04:00","cssclasses":""}
---

#Coding/datatype #Coding/python 



- In [[Python]] write complex numbers with a “j” j is [[Imaginary Numbers\|the imaginary part]]
```python
x = 5+j
``` 
> [!bug]
> You cannot [[Type casting in Python\|cast]] complex numbers into another type

```python
x = 5
x = complex(5) #cast int to complex
b = int(x) #wont work?
```