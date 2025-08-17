---
{"publish":true,"created":"2025-07-25T14:00:15.000-04:00","modified":"2025-08-17T16:23:45.862-04:00","tags":["Coding/python"],"cssclasses":""}
---

[[Match statement python\|Match statements]]! 
Here is an example combining these things you can do with match statements:
	[[Default value in match statements]]
	[[Combine cases in match statements]]
	[[Added conditionals in a match statement]]
		[[complex cases match statements]]
```python
x = input("what would you like me to do with the numbers? (+,-,*,/)").strip()
match x:
	case "+" | "add" | "plus" if troll == false: 
	#in this case troll is just a variable on whether or not the user has a "cheat code" where the calculator just gets stuff wrong on purpose
		print(number1+number2)
	case "-" | "subtract" | "minus" if troll == false:
		print(number1-number2)
	case "*" |"multiply"| "times" | "/" | "divide" | if troll = true
		print("thats too difficult for me to do sorry")
	case _:
		print("I either haven't gotten to coding this or you didn't put in an acceptable input")
	
```