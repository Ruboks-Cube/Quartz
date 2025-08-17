---
{"publish":true,"created":"2024-11-21T06:17:27.000-05:00","modified":"2025-08-17T16:23:25.371-04:00","cssclasses":""}
---

#coding/robloxstudiolua #gamedevelopment/robloxstudio [[Roblox Studio Lua]]


Instancing allows you to insert things into the game through a [[script]].

We can insert things into the game usually by [[how do I make a part in roblox studio\|making a part]] but what <mark class="hltr-blue">if you want to do it while the game is running?</mark> Like how do you insert a part after you've already run the game?

WE INSERT AN [[instance]], which is where instance.new comes from.

## Instances

## How to make the instance

first we make a script
![[Files/Images/Pasted image 20240115105816.png|500]]
then write `instance.new("*What we want*")` We choose a part, but we can get anything from the [[object browser]]. 
![[Files/Images/Pasted image 20240115105922.png|500]]

If we insert a part, then run it, the script won't do anything and the part will not appear. this is because we haven't told the script *where* we want the part.

In the workspace? A model? 

### How to actually make instance.new do stuff
#### first method (not recommended)
Instance.new is a [[Functions in coding\|function]]. and it has [[parameter]]s. The first parameter is the [[String]], telling the function what we want a new instance of. The second, is where we want it.

Using this knowledge, we can use the parameter
![[Files/Images/Pasted image 20240115110900.png]]
This is not recommended because it's slow for the script to first put it into the game.workspace *then* change [[Properties in Object Oriented Programming\|properties]].
#### Second Method (recommended)
You can tell the script what the parent is

mypart.parent = game.workspace
mypart being the [[variable in coding]] the instance is equal to.
## changing properties with the instance

You may have noticed that we can't really manipulate the part since it <mark class="hltr-blue">doesn't exist in the game unless we run it</mark> so we can't reference it. <mark class="hltr-red">Or can we?</mark>



> [!NOTE] NOTE
> for the below screenshots, pretend they utilize the second parameter and actually do something or they use the recommended way and set the parent.



Add a variable to your instance to [[Referencing in Lua\|Reference]] it.
![[Files/Images/Pasted image 20240115110148.png]]
<mark class="hltr-green">We're setting a variable to be the instance. So now are we able to manipulate it?</mark>
![[Files/Images/Pasted image 20240115110223.png]]
yep. We can, just like a normal part. The script knows that the variable `myinstance` is set to a part instance.
![[Files/Images/Pasted image 20240115110344.png]]
As you can see, the<mark class="hltr-green"> properties change depending on what the instance is.</mark>
