---
{"publish":true,"created":"2025-07-03T15:45:28.000-04:00","modified":"2025-08-17T16:23:39.541-04:00","tags":["Coding/python"],"cssclasses":""}
---

The condition is literally an [[if statement python\|if statement]] built into the list comprehension:
```python
myfruitbasket = ["apple", "banana", "cherry", "apple", "kiwi", "mango", "apple"]
# lets say jerry hates apples, so we want to take out the apples from the basket
newbasket = [x for x in myfruitbasket if x != "apple"] #if the item equals "apple" it will not be included in the new list
print(newbasket) #output ['banana', 'cherry', 'kiwi', 'mango']
# lets say jerry also likes to sprinkle some sugar on his fruit
newbasket = [x + " with sugar" for x in myfruitbasket if x != "apple"] #this one edits the expression
print(newbasket) #output ['banana with sugar', 'cherry with sugar', 'kiwi with sugar', 'mango with sugar']

# If there is no if statement it acts like
for item in iterable:
	newlist.append(expression)
# Example with no condition
newbasket = [x for x in myfruitbasket] #this will just copy the list]
```
