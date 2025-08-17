---
{"publish":true,"created":"2024-11-21T06:17:36.000-05:00","modified":"2025-08-17T16:23:26.798-04:00","cssclasses":""}
---

#coding/robloxstudiolua [[Roblox Studio Lua]]

 [[variable in coding \|variable]]s are in Lua! In fact, we've already used them with [[Referencing in Lua \|referencing]]. When you do
```lua
local part = script.parent
```
We are assigning the "part"(the [[variable identifier]]) to script.parent (the [[part]] we made)

See [[variable in coding]], to understand the variables and [[Datatype]] for basic datatypes used in variables. Of course, in [[roblox studio]] and probably [[Unity]], we can make parts variables too by [[Referencing in Object Oriented Programming \| referencing]] the part (basically assigning it to a variable so we skip saying game.workspace.model.part.hibajaba1)... TOO MANY DOTS!!! When you could say part.hibajaba1.


So what are the parts of making a variable in Lua?


# Declaring a variable in Lua

we start with [[Local in Lua]]. This is infront of functions, and variables. You *can* declare a variable in lua without local, but it's good practice to do this. Then is the [[variable identifier]], whatever name the variable is (just make sure it's not another variable name.) When you create the variable identifier, you are creating the box for the contents (thing the variable will store) to go inside. Notice how you can create a variable but you can store the contents later:
![[Files/Images/Pasted image 20240111195547.png]]

Thats because you can get the box to store something without actually having the store anything. This is the same for values without a variable, you don't need to store most values inside a variable (unless it's user input) but you can! And why not? It's a pretty sweet shortcut.


So you need
1. Local
2. [[variable identifier\|identifier]]
3. Value



# The main types of variables you will be using in Lua

[[Datatype]]s!

- [[integer]]
- [[String]]
- [[Bool]]
- [[Referencing in Object Oriented Programming\| Object References]] in [[object oriented programming]] ([[Roblox Studio Lua]])
Unlike [[Coding Csharp \|in c#]] where you have to state the [[Datatype]] before you say the [[variable identifier]], you don't have to do that in Lua, it'll figure it out with the value itself.