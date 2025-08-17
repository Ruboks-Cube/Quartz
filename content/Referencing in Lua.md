---
{"publish":true,"created":"2024-11-21T06:17:32.000-05:00","modified":"2025-08-17T16:23:27.453-04:00","cssclasses":""}
---

#coding/robloxstudiolua 

In [[Roblox Studio Lua]] we can reference objects in the game so we don't have to keep referring to it the long way.


# The long way:
![[Files/Images/Pasted image 20240101151459.png]]
so we have this part in our workspace/game. Now we want to manipulate it, so we make a script for it
[[how do I make a part in roblox studio]]
![[Files/Images/Pasted image 20240101151622.png]]
(Note, [[child]] of [[parent]]s in [[object oriented programming]] are referred to with ".", think of it as the path to a file in [[File Explorer]], only instead of > or /  it's dots, you can also think of it as the tag hierarchy in [[Obsidian]])

in the script, we refer to the part as ``game.Workspace.Part.Color
so [[robloxstudio]] knows what it is. But what if I don't want to say ``game.Workspace.Part.Color
all the time to refer to the part?

This is where [[Referencing in Object Oriented Programming]] comes in.  



# The Shortcut
Instead, we can assign a [[variable in coding]] to this part, so whenever we want to refer to it, all we have to do is get the variable
![[Files/Images/Pasted image 20240101153403.png]]
Here you can see we make a [[Variable in Lua]] called part and assign it to the value of the part in the workspace. Note that there is a [[Local in Lua]], don't worry about this for now, but know it also applies to [[functions in lua]]. It's like semicolons in [[Coding Csharp]], they are just there.

Note that there is a 
[[Comment in Coding]]:

```lua
game.Workspace.Part --or script.parent
```
you can see the ``--or script.parent
this is a comment, and this comment in particular shows that we can refer to the part as script.parent as well, since the script has a [[parent]] which is the part. 

Now that we have a variable assigned to the part, whenever we have to refer to it within this script, we can by just saying "part" instead of ``game.Workspace.Part
because the variable is the part now.

There is also the added fact that if you utilize [[model]]s a lot (which you should because better organization), it will take a VERY long time to add everything.