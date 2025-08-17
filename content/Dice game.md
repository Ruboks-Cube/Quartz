---
{"publish":true,"created":"2024-11-21T06:17:23.000-05:00","modified":"2025-08-17T16:23:23.943-04:00","cssclasses":""}
---

#Coding #coding/robloxstudiolua #Coding/ObjectOrientedProgramming 

We will make a dice game in [[roblox studio]] to show the use of [[variable in coding]], [[Referencing in Lua]], and [[function]]s in [[Roblox Studio Lua]]


# Making the dice

To make the dice we have to first make a [[part]]/[[Game Object]]
[[how do I make a part in roblox studio]], then we can edit the size property inside the part, as well as rename it to "dice 1" 

[[Changing Size of a part roblox studio lua]]
![[Files/Images/Pasted image 20240105194658.png]]
[[Renaming Game Objects in roblox studio lua]]
![[Files/Images/Pasted image 20240105194725.png]]



### finishing the dice
[[Toolbox in robloxstudio lua]

we will use this to find [[Decals]].
![[Files/Images/Pasted image 20240105194910.png]]
make sure in the toolbox it is in images on the dropdown next to the searchbar.


Search up Dice 1 and drag the image you want to the cube
![[Files/Images/Pasted image 20240105194945.png]]

Do this until you have all of the sides complete, you may have to move the dice up
[[Moving Objects in Roblox Studio]]

![[Files/Images/Pasted image 20240105195641.png]]
This is dice 1

To make dice 2, simply copy dice 1 and paste, make sure you rename
![[Files/Images/Pasted image 20240105195820.png]]
then make a model and put Dice 1 and 2 together, so by selecting the model you select both Die


![[Files/Images/Pasted image 20240105195941.png]]
You can then rotate the die, to select the die individually, click on it in the [[roblox studio explorer]]


Then position them a decent height up so they fall nicely
# Organization
Additionally, you can make a folder and put the model in to get some extra organization, this folder is also where we would put our script
![[Files/Images/Pasted image 20240105200313.png]]
# Programming the die
It is time to get scripting!! Make a script inside the folder!
Before you start programming, make sure they are [[anchored]] and [[can collide]] is on. These two [[Properties in Object Oriented Programming]] are important!!!

Rename the script to something related to dice, this is important for organization


Now we can start programming.
## the code
here is the code:
```lua
local dice1 = game.Workspace["Dice Game"]["Dice models"].dice1
local dice2 = game.Workspace["Dice Game"]["Dice models"].Dice2
--referencing

local function dropdice1()
	dice1.Anchored = false
end

local function dropdice2()
	dice2.Anchored = false
end


wait(5) --tells script to wait 5 seconds, built in function where the wait time in seconds is the parameter
dropdice2()
wait(0.2)--a little wait time so dice 2 can bump dice 1 on the way down
dropdice1()
```

## explaining the code
the first 2 lines are [[Referencing in Lua]]. Allowing the script to understand the [[variable in coding]] dice1 and dice2

the next lines are [[Declaring Functions]], basically making [[Functions in coding]].

the next lines are using [[Built In Function]] [[wait]] and does [[calling functions]] so the functions


# the result
What the game engine should do, is that after 5 seconds, the dice to drop. You can experiment with the wait times.