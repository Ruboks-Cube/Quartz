---
{"publish":true,"aliases":"customize sort functions","created":"2025-07-04T12:36:05.000-04:00","modified":"2025-08-17T16:23:21.548-04:00","tags":["Coding/python"],"cssclasses":""}
---

We can customize the sort function by passing a function to the `key` [[parameter]] of the `sort()` method.
	[[key parameter]]
The [[key parameter]] allows us to create “ghost” [[Element in array\|Elements]] of the [[lists in python\|List]] before sorting
		These ghost elements are the return values of the function we pass to the `key` → they never actually exist in the original list, they just correspond with it
		Instead of sorting the original list, it sorts the ghost elements and then reorders the original list based on that
```python
mylist = [100, 50, 65, 82, 23]
# sort by how close they are to 50

def myfunc(n):
		return abs(n - 50)
mylist.sort(key=myfunc) #ghost list is [50, 0, 15, 32, 27], which in order corresponds with the original list
# it's like there is a string attached to the corresponding original list element, 50 is attached to 100, 0 is attached to 50, etc
# The key parameter sorts the ghost list alphanumerically, and the original list moves with it
print(mylist) #output [50, 65, 23, 82, 100]
```
key=myfunc makes it so all values of the list are passed through the `myfunc` function before sorting
		takes each [[element]] and sets it to `n` in the `myfunc` function → then each original [[element]] is sorted by the [[Returning in code\|return]] value of `myfunc(n)`
		Then the [[sort lists\|sort()]] method sorts [[alphanumeric sorting\|alphanumerically]]
![[Files/customizing sort function 2025-07-04 12.46.23.excalidraw]]
We can use this to sort by [[Absolute Value]], [[len()\|length of string]], or any other custom criteria

[[making sort() case insensitive]]