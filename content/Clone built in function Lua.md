---
{"publish":true,"created":"2024-11-21T06:17:22.000-05:00","modified":"2025-08-17T16:23:29.109-04:00","cssclasses":""}
---

#coding/robloxstudiolua/function 

The clone [[Built In Function Lua\|built in function]] in lua makes it so the part you called it on is duplicated it

```lua
game.workspace.part:clone()
```
- This code doesn't actually do anything however, since the script does not know where to put the [[part]].

- What we have to do is set this all to a [[Variable in Lua]]
- Just like what we did with [[Returning in code]], we have the part, but we don't have a [[Referencing in Lua\|Reference]] to it

```lua
local myclone = game.workspace.part:clone()
```

- The clone function returns the cloned part to the variable, so now we have a reference
- Now that we have a reference, we can set it's [[parent]], name, vectors, size, [[Properties in Object Oriented Programming\|Any Property!]]

Our code would now look like this:
```lua
local myclone = game.workspace.part:clone()
myclone.parent = game.workspace
myclone.name = clonedpart
```
