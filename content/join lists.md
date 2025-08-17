---
{"publish":true,"aliases":"concatenate lists","created":"2025-07-07T14:28:15.000-04:00","modified":"2025-08-17T16:23:52.610-04:00","tags":["Coding/python"],"cssclasses":""}
---


[[concatenation]] → it’s like [[String Concatenation]] but for lists!
The most simple way to do this is with the “+” [[Python Operators\|Operator]]

Another way is the [[append()]] method
```python
list1 = ["a", "b", "c"]
list2 = [1, 2, 3]
list1.append(list2)
print(list1)
# Output: ['a', 'b', 'c', [1, 2, 3]]
```

Another way is the [[extend()]] method
```python
list1 = ["a", "b", "c"]
list2 = [1, 2, 3]
list1.extend(list2)
print(list1)
# Output: ['a', 'b', 'c', 1, 2, 3]
```

