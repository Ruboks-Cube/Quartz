---
{"publish":true,"created":"2025-07-01T11:06:35.000-04:00","modified":"2025-08-17T16:23:38.177-04:00","cssclasses":""}
---

#Coding/python 

This is a list of methods to help you remove list items:
[[remove()]] → removes a specific item by value
[[pop()]] → removes an item by index and returns it
[[del keyword python\|del]] → removes an item by index or slice or delete the entire list 
[[clear()]]  → removes all items in the list

# Example Code

```python
# Example list
my_list = [10, 20, 30, 40, 50]
print("Original list:", my_list)
# Remove by value
my_list.remove(30)
print("After remove(30):", my_list)
# Remove by index using pop
removed_item = my_list.pop(1)
print("After pop(1):", my_list, "Removed item:", removed_item)
# Remove by index using del
del my_list[0]
print("After del my_list[0]:", my_list)
# Clear the entire list
my_list.clear()
print("After clear():", my_list)
```
# Output
```
Original list: [10, 20, 30, 40, 50]
After remove(30): [10, 20, 40, 50]
After pop(1): [10, 40, 50] Removed item: 20
After del my_list[0]: [40, 50]
After clear(): []
```

