---
{"publish":true,"created":"2024-11-21T06:17:30.000-05:00","modified":"2025-08-17T16:23:26.367-04:00","cssclasses":""}
---

#coding/robloxstudiolua  [[Roblox Studio Lua]]


Parameters are an extension of [[functions in lua]], they make functions more dynamic. The argument is in the parenthesis of the function, similar to [[math functions]], the parameter is the [[Input]], and there are variables inside the function itself, that are set to the value of the argument. The parameter allows the code in the function to change when you [[calling functions\|Call it]].

## What are parameters?
Parameters are [[Variable in Lua\|Variables]] existing in the function.
### Syntax of a parameter
Parameters go in the parenthesis, and the variable itself goes in the function. If you have multiple parameters then you separate with commas.
## Use case of parameters
###### When you want to slightly change a function:
Take this function
```lua
function myparameters()
	local part = Instance.new("Part")
	part.Position = Vector3.new(4,4,4)
	part.Name = ("My part")
	part.Color = Color3.new(0.317647, 0, 1)
	part.Parent = game.Workspace
end

myparameters()
```
If we wanted to make multiple new instances, each with different values for each property, we could use parameters. 
###### Already-existing functions
[[Built In Function Lua\|Built in Functions]] in [[Roblox Studio Lua\|Lua]] have parameters. Take a function like Print
```lua
print("hello")
```
The output will be hello, this is because the print function takes hello, and outputs it. If we assign a variable to what the print function outputs, lets say, "A", we now know that the print function outputs "A." If we want to print "hello", we assign "hello" to A. This is how parameters work, and I've already been using them since "Hello World!"


Another example would be [[instance.new]].
```lua
local mypart = instance.new("part")
```
We have a parameter called part in the built in function instance.new. What instance.new does is makes a new [[instance]] based on what we say, so it would look something like this: 
![[Files/Images/Parameters in Lua 2024-02-04 16.42.34.excalidraw\|500]]

You can see now that functions in lua can act as blocks of code, but also similar to [[math functions]], where they take inputs, in this case we call them parameters, and then get an output! 
## Examples:

#### Changing the properties of instances
```lua
function myparameters(name ,color , position)
	local part = Instance.new("Part")
	part.Name = name
	part.Color = color
	part.Position = position
	part.Anchored = true
	part.Parent = game.Workspace
end

myparameters("Part1", Color3.new(0.862745, 0.905882, 1), Vector3.new(4,4,4))
myparameters("part2", Color3.new(0.662745, 1, 0.776471), Vector3.new(10,10,10))
```
In this example, we have the parameters name, color and position. We call them:
![[Files/Images/Pasted image 20240204165639.png|100]]

#### Making our own print function
Here is a fun little absolutely USELESS way to use parameters, but it shows how they work pretty well.

```lua
function printbutbetter(whatiwant)
	print(whatiwant)
end
```
When we call `printbutbetter` and put a string for the parameter, it prints it, since the function has the built in print function inside it.