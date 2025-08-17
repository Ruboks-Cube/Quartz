---
{"publish":true,"created":"2025-07-20T12:45:35.000-04:00","modified":"2025-08-17T16:23:45.972-04:00","tags":["Coding/python"],"cssclasses":""}
---


We can [[iteration control structure\|loop]] nested dictionaries as well
	This is more complicated than [[Loop through dictionaries\|looping through normal dictionaries]]
- Requiring in total 3 [[loop variable\|loop variables]] and two [[for loop\|for loops]] just to get each [[key value pair]] of a 1 layer [[Nest dictionaries\|nested dictionary]]
```python
# loop through every item in myfamily dictionary AND nested dictionaries
for x, obj in myfamily.items():
    print(x) # x is the "child" keys and obj refers to their individual dictionaries
    
    for y in obj: # obj is their own individual dictionary and now y is the individual key inside each child dictionary
        print(y + ':', obj[y]) # printing 
        
'''
output:

child1
name: Emil
year: 2004
child2
name: Tobias
year: 2007
child3
name: Linus
year: 2011
'''
```