---
{"publish":true,"created":"2025-06-20T08:58:35.000-04:00","modified":"2025-08-17T16:23:31.765-04:00","cssclasses":""}
---

#Coding/python #Coding 

- You output with the [[Print()\|Print function]]


# Outputting [[Strings in Python]]
Let this be true for all following instances:
```python
x = "you"
y = "are"
z = "cool"
```
You can output a variable using [[Print()]]
```python
print(x)
```
You can combine variables with commas
```python
print(x,y,z)
```
This will lead to “you are cool”
- Commas automatically give a space


You can combine variables with a +
```python
print(x + y + z)
```
This yields: “youarecool”

“+” does not automatically give spaces


# Outputting [[int\|ints]]

```python
x = 15 #print(type(x)) will lead to int
y = 20 #print(type(y)) will lead to int

print(x+y) #output will be 35
```

> [!failure] The following does not work:
>```python 
>x=15
>y="hello"
>print(x+y) #will result in an error because int+String does not work
>```



