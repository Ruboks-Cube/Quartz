---
{"publish":true,"created":"2025-01-26T09:55:47.000-05:00","modified":"2025-08-17T16:23:27.999-04:00","cssclasses":""}
---

#coding/robloxstudiolua , [[functions in lua]], [[Roblox Studio Lua\|#coding/robloxstudiolua]]

## Use cases
#### Changing a property of a part
We can access a property of the part by returning the part, and changing the value
```lua
function mypart()
	local mypart = Instance.new("Part")
	mypart.Name = "hello"
	mypart.Anchored = true
	mypart.Position = Vector3.new(0,20,0)
	mypart.Parent = game.Workspace
	return mypart
end

local mypart = mypart()
wait(5)
mypart.Anchored = false
```
We have a variable set to an instance, we return the variable and we can change it's properties now!
This code creates an instance, and after 5 seconds, it sets the anchored to false.
