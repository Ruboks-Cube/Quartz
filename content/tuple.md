---
{"publish":true,"aliases":"tuples","created":"2025-07-09T15:24:40.000-04:00","modified":"2025-08-17T16:23:51.900-04:00","tags":["Coding/python"],"cssclasses":""}
---

Tuples are one of the 4 built-in data types used to store multiple values in [[Python]]
	 The other 3 are [[lists in python\|Lists]], [[set in python\|sets]], and [[Python Dictionaries\|dictionaries]]
A tuple is a collection which is ordered and [[immutable]] (cannot be changed)
They are written with round brackets 
Example:
```python
# Creating a tuple
my_tuple = ("apple", "banana", "cherry")
print(my_tuple)
# Output: ('apple', 'banana', 'cherry')
```
- Tuples are [[indexing\|indexed]] and can be accessed using [[indexing]]
- They are ordered [[what does ordered mean in a list -python\|What does ordered mean in a list]]
- Tuples are unchangeable 
	- Cannot add, remove, or change items in a tuple after it is created
Tuples allow duplicate values like [[lists]] because they are indexed
```python
# Tuple with duplicate values
my_tuple = ("apple", "banana", "cherry", "apple", "cherry")
print(my_tuple)
# Output: ('apple', 'banana', 'cherry', 'apple', 'cherry')
```
Tuples work with [[len()]]
- [[Creating a tuple with one item]]

Tuples can contain any data type and have mixed data types
```python
# Tuple with mixed data types
my_tuple = ("apple", 1, True, 3.14)
print(my_tuple)
```
[[Using type() with a tuple]]

[[Tuple constructor]]
	[[Tuple constructor\|tuple()]]
## Things you can do with a tuples
[[accessing a tuple]]
	[[keyword 'in' in python\|checking a sequence]]
[[Changing a tuple]]
[[Concatenate tuples]]
- [[difference between joining and concatenation]]
[[loop through a tuple]]
[[Multiply tuples]]
[[Tuple methods]]
