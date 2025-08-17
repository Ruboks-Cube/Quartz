---
{"publish":true,"created":"2025-08-05T18:17:43.000-04:00","modified":"2025-08-17T16:23:52.054-04:00","tags":["Coding/python"],"cssclasses":""}
---

- [[function recursion]]

Example: 
```python
ef tri_recursion(k):
  if(k > 0):
    result = k + tri_recursion(k - 1)
    print(result)
  else:
    result = 0
  return result

print("Recursion Example Results:")
tri_recursion(5)
'''outputs:
Recursion Example Results:
1
3
6
10
15
'''
```
- This code starts a loop because the result [[variable in coding\|variable]] calls the `tri_recursion` function
	- It ends when the result = 15 
![[Files/Recursion in Python 2025-08-05 18.20.22.excalidraw]]