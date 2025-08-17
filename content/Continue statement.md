---
{"publish":true,"aliases":"continue keyword python continue keyword","created":"2025-07-25T16:34:15.000-04:00","modified":"2025-08-17T16:23:47.113-04:00","tags":["Coding/python"],"cssclasses":""}
---

The continue keyword goes to the next iteration of a [[iteration control structure\|loop]] in [[Python]]:
	Skipping the rest of the while loop iteration and going back to the start
The continue keyword can stop the current iteration like the [[Break statement\|break keyword]] but instead of stopping the entire loop it just goes to the next iteration
	“skips” an iteration
```python
i = 0  
while i < 6:  
  i += 1  
  if i == 3:  # now "3" won't be printed but everything else will be until 6
    continue  
  print(i)
```
