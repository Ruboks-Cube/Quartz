---
{"publish":true,"created":"2024-11-21T06:17:22.000-05:00","modified":"2025-08-17T16:23:23.168-04:00","cssclasses":""}
---

#gamedevelopment/robloxstudio #coding/robloxstudiolua 


You can change the size of a part in roblox studio in 2 main ways.

1. Changing it through setting the value in the game view
2. Changing it through a script

# Changing through game view
## how to do

Select part
navigate to properties
change size based on length width height, x,z,y
![[Files/Images/Pasted image 20240106180120.png]]
### advantages
simple and easy, provide value through properties section


### disadvantages

Cannot change *in game* meaning once the value is set, no longer changeable unless through script.
# Changing through script
## how to do
Code:
```lua
local part = game.Workspace.Part --or script.parent


part.Size = Vector3.new(10,10,10)

```

This uses [[Vector 3]] which requires knowledge of [[Vector]]s to understand fully.

Anyway, you see how we get the game object part from [[Referencing in Lua]] and then take that variable and go to the Size [[child]], there we assign it to Vector3.new(10,10,10). We're saying we want a new Vector3 that is x 10 y 10 and z 10.

This is how to change the size using [[script]]s


## advantages
- Convenient
- Easy
- Can happen during game,  you can use the script to change the size when the game is running! unlike [[Changing Size of a part roblox studio lua#Changing through game view]]





# When to use each one
Changing through game view is basically optional, but it's convenient
- use game view to set the default value
- use scripts to change when running