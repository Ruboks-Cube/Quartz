---
{"publish":true,"created":"2024-11-21T06:17:26.000-05:00","modified":"2025-08-17T16:23:25.587-04:00","cssclasses":""}
---

#coding/robloxstudiolua [[Roblox Studio Lua]]
### What is a function?

- Sequences of instructions that we give a name, called a [[function identifier]]
# Functions in coding
Functions are used in [[Coding]] for the program to actually work.

There are [[Built In Function]]s and then there are functions made by the user.

Functions when made by the user are blocks of code that have the ability to manipulate [[Datatype]]s and outputs when called, they are also shortcuts, since you don't have to write a block of code every time you want to execute it, you only have to [[calling functions\|call it]]
[[calling functions]] and [[parameter]]s

- They are blocks of code made by the user that can be called and repeated
- You can think of them as shortcuts
- Utilize parameters to go even faster


[[Declaring Functions]]


- [[function recursion]]

Functions in lua act like any other [[Functions in coding]], they have an input and a output, and must be [[calling functions\|called]]. Here is how to utilize functions in lua:

# Example Use Cases of functions in lua
## Repeating blocks of code
Imagine you want to make a bunch of new [[instance]]s (new parts), lets say you want to make 5. If each one takes 6 lines of code because you have [[instance.new]], [[Properties in Object Oriented Programming\|you are changing properties]] and setting the new instances [[parent]]. This will take a LOT of lines, maybe around 50, even for just 5 parts. (Imagine if there were more lolololol)

Having 50 lines dedicated to making 5 parts is 
- inefficient, takes less time, and even if you are just copy pasting it is...
- Less organized, looks ugly

Nobody wants to scroll that long, and what if your script needs to have other things? 

This is where [[function]]s come in.
## Slightly different blocks of code
What if we want to change the block of code slightly? Ok, we make a function that makes a part, but what if we want them to have different names, colors, or any other [[Properties in Object Oriented Programming\|Property]]. Welcome to [[Parameters in Lua]]
# Using Basic Functions in lua (no parameters)
## Declaring them
### Basic syntax
This is the basic syntax in [[Roblox Studio Lua\|Lua]] for declaring a function:
```lua
function myfunction()
	--contents
end
```

1. `function myfunction()` "function" tells the [[script]] that the following code is going to be a function
2. `myfunction()` is the name of the function, the parenthesis are required for the function, and any [[parameter]]s we need will go in here.
3. `end` states to the script that we are no longer creating a function, past line 3, it is other code
4. In line 2, and until end, will be our code for the function that the script will execute when it gets called


It's important to note that this code itself won't do anything, no matter whats in the contents, unless it's been [[calling functions\|called]]. the function won't do anything.

### Function examples
There are multiple times where you could use a function, here are some examples: 

> [!NOTE] NOTE
> The functions here won't do anything because they haven't been called LOL

#### Making a part
![[Files/Images/Pasted image 20240116170422.png]]
This function will make a part in the workspace when it is called

#### Printing the same thing
![[Files/Images/Pasted image 20240116170628.png]]
this function will print all these things when called
## Calling them
The basic syntax for calling a function in lua:
```lua
myfunction() --myfunction is the name of the function
```
Thats it, the name of the function with the parenthesis calls it.
you can call the function as many times as you want


> [!NOTE] ❗IMPORTANT ❗
> You cannot call a function if it's before the declaring of a function in a script


