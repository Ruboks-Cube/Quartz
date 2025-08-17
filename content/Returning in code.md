---
{"publish":true,"aliases":"Returns","created":"2024-11-21T06:17:32.000-05:00","modified":"2025-08-17T16:23:41.179-04:00","cssclasses":""}
---

#coding/robloxstudiolua [[Roblox Studio Lua]] #Coding 


Returning in  allows you to send back data from a [[function]] so it can be used later on
- Returning essentially sets the value of a [[function]] to the [[variable in coding\|variable]] (of your choice) you returned
- [[functions in lua]]
- [[Use cases of Returning in Lua]]

## The problem
Here is an example function:
```lua
function myclacloosason(number1, number2)
	local result = number1+number2
	print(result)
end

myclacloosason(3,5) --8

--what if we wanted to do print(result)

```
Here, we have a function that takes number1 and number2,  stores the [[addition\|Sum]], and prints it. If we [[calling functions\|Call it]] with the [[Parameters in Lua\|Parameters]] 3, and 5, it prints 8.

Now that we've calculated it, what if we want to do something with it later on? What if we wanted to print it outside of the function, or do another calculation with result? Well, we cannot currently because it's not stored anywhere. 
It's stored locally inside result, so it exists only within the function.

![[Files/Images/Returning in Lua 2024-02-04 17.22.02.excalidraw\|500]]
Calling the function simply runs the code of the function and goes directly to the [[Output]].



## The solution
We can use RETURN!!!!
Return basically creates a bridge  of the returned value, to where you called it.
![[Files/Images/Returning in Lua 2024-02-04 17.33.14.excalidraw\|500]]
When you return a value, the "call" of the function is now equal to that value.
```lua
function myclacloosason(number1, number2)
	local result = number1+number2
	return result
end

local myreturnedvalue = myclacloosason(3,5) --8
print(myreturnedvalue)
```
Here you can see we return result, which sends the data to the calling of myclacloosason, and set a variable equal to myclacloosason, which now holds the value of the returned value, result.
We can now print "myreturnedvalue", and it will equal 8.

