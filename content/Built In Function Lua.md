---
{"publish":true,"created":"2024-11-21T06:17:21.000-05:00","modified":"2025-08-17T16:23:23.438-04:00","cssclasses":""}
---

#coding/robloxstudiolua [[Roblox Studio Lua]] #coding/robloxstudiolua/function 

A [[functions in lua]] is a block of code that has been defined so the user can call the function. In [[roblox studio]], there are some functions that have already been predefined before even opening the [[script]]

# Finding Built In Functions
To find some built in functions, you can go to the [[object browser]], select an object and the pink icons are all the already predefined functions. We can call built in functions just like normal functions.


> [!tip] Seeing what built in functions do
> Click on the built in function to see what they do
> ![[Files/Images/Pasted image 20240326201500.png|200]]

Here is a list of basic built-in functions:
```lua
Destroy()--Destroys the Part
Clone()--creates a duplicate of the object
ClearAllChildren()--deletes all the children of the Part
Wait()
Print()
```

# How to use built in functions
## General
There are 2 types of functions
Lets go back to the functions we had before

> [!example] functions
> - Destroy()
> - Clone()
> - ClearAllChildren()
> - Wait()
> - Print()


- The first 3 functions are functions that effect a [[Game Object]] in the game in some way
	- We call the function on a specific function
	- These are called <mark class="hltr-blue">Member Functions</mark>
- The bottom 2 don't have anything to do with any object, we call them <mark class="hltr-green">Global Functions</mark>

To use the Member Functions, we first get the objects [[Referencing in Lua\|Reference]] in the game
```lua
game.Workspace.TestPart:Destroy()
```
- You can see here that we first get the reference, game.workspace.testpart, then do a colon
- The colon is basically saying that we are [[calling functions\|calling]] the function.

> [!info] Important
> Whenever you want to use a built in member function, you use the colon to say that you want to call the built in function on that [[instance]]

- The reason for the parenthesis at the end is because it tells the script that we are running a function

## Specific
### Member 
[[Clone built in function Lua]]

### Global
[[Print()]]
[[Wait()]]