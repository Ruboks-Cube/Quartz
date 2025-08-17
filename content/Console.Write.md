---
{"publish":true,"created":"2024-11-21T06:17:22.000-05:00","modified":"2025-08-17T16:23:24.607-04:00","cssclasses":""}
---

#Coding/Csharp 

Console.Write is different from [[Console.WriteLine()]] since Console.Write does not form a new line.


Console.Write affects the line after it, meaning that if you do

```csharp
Console.WriteLine("Hello world");
Console.write("same line?");

```

the output would be
```
Hello world
same line?
```

but if you do

```csharp
Console.Write("Same line? "); //Put a space after the ? to show that there isspacebetween Same Line and Idk
Console.WriteLine("Idk");
```

the output would be

```
Same line? Idk
```

So you can see here how Console.Write affects the next line.