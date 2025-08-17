---
{"publish":true,"created":"2025-01-19T16:10:10.000-05:00","modified":"2025-08-17T16:23:28.732-04:00","cssclasses":""}
---

#Coding/Csharp 

- How we get [[User Input]] in [[Coding Csharp]]
- [[Console.ReadLine()]] is to write, `Console.ReadLine()` is to read


- Example:
	```csharp
	// Type your username and press enter
	Console.WriteLine("Enter username:");
	
	// Create a string variable and get user input from the keyboard and store it in the variable
	string userName = Console.ReadLine();
	
		// Print the value of the variable (userName), which will display the input value
	Console.WriteLine("Username is: " + userName);
	```
- `Console.ReadLine()` stores a [[String]] inside it, to actually “use” that string we have to store it in a [[variable in coding\|variable]] → [[Making variables Csharp]] 
	- Since it returns a string if we want an “[[int]]” it will just return an error
		```csharp
		Console.WriteLine("How old are you?:");
		int age = Console.ReadLine();
		Console.WriteLine("age is:" + age); //ERROR
		```
	- Instead, we have to use the [[type conversion methods\|Type conversion method]] `Convert.To`
		```csharp
		Console.Write("AGE:");
		int age = Convert.ToInt32(Console.ReadLine());
		Console.WriteLine("your age is " + age);
		```




