---
{"publish":true,"created":"2025-07-03T15:49:44.000-04:00","modified":"2025-08-17T16:23:39.480-04:00","tags":["Coding/python"],"cssclasses":""}
---

Basic syntax of [[list comprehension]]:
```python
newlist = [expression for item in iterable if condition]
```


>[!faq] What is the point of the expression?
> Do the expression and the item have to be the same?
> 	The expression is what will happen to each item in the [[iterable]]
> If the expression is not the item it will be applied to the item

Basic usage:
```python
jimmysfruits = ["apple", "banana", "cherry"]
alexfruits = [x for x in iterable] # nothing is changed, alex likes the same fruits as jimmy
print(alexfruits) #output ['apple', 'banana', 'cherry']
# lets say sarah wants sugar with every fruit because she's a sweet tooth
sarahfruits = [x + " with sugar" for x in jimmysfruits] # this will add " with sugar" to every fruit 
print(sarahfruits) #output ['apple with sugar', 'banana with sugar', 'cherry with sugar'] 
# we changed the expression
```

Making the [[Expression]] an [[if statement python\|if statement]] is also possible:
```python
myfruitbasket = ["apple", "banana", "cherry", "apple", "kiwi", "mango", "apple"]
# lets say jerry hates apples, so we want to take out the apples from the basket
# instead of apples, he wants to replace them with mangoes
newbasket = [x if x != "apple" else "mango" for x in myfruitbasket] #newbasket = x if x doesn't equal apple, ELSE it equals mango
print(newbasket) #output ['mango', 'banana', 'cherry', 'mango', 'kiwi', 'mango', 'mango'] 
```

