---
{"publish":true,"created":"2025-01-19T15:30:56.000-05:00","modified":"2025-08-17T16:23:26.903-04:00","cssclasses":""}
---

#Coding/Csharp 

Type casting is when you change the value of one [[Datatype]] to another.
- [[type conversion methods]]

There are two types of type casting, Implicit, and Explicit.

### Implicit Casting
**Implicit Casting** (automatically) - converting a smaller type to a larger type size  
`char` -> `int` -> `long` -> `float` -> `double`


```csharp
int myInt = 9;
double myDouble = myInt;       // Automatic casting: int to double

Console.WriteLine(myInt);      // Outputs 9
Console.WriteLine(myDouble);   // Outputs 9
```
### Explicit Casting
**Explicit Casting** (manually) - converting a larger type to a smaller size type  
`double` -> `float` -> `long` -> `int` -> `char` 
```csharp
double myDouble = 9.78;
int myInt = (int) myDouble;    // Manual casting: double to int

Console.WriteLine(myDouble);   // Outputs 9.78
Console.WriteLine(myInt);      // Outputs 9
```

- For explicit casting, you simply have to put in parenthesis what you’re converting to before the original [[variable math\|variable]]


