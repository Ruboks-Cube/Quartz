---
{"publish":true,"created":"2024-11-21T06:17:21.000-05:00","modified":"2025-08-17T16:23:23.835-04:00","cssclasses":""}
---

#Coding/Csharp

In [[Coding Csharp]] there is syntax, like all coding languages. The basic syntax (which is what first appears when you boot up a program is what is used)

```csharp
using System;

namespace HelloWorld
{
  class Program
  {
    static void Main(string[] args)
    {
      Console.WriteLine("Hello World!");    
    }
  }
}
```

All of the lines have different meanings. But the  ``Console.WriteLine("Hello World!"); 
is what forms the [[Output]] since [[Console.WriteLine()]] is a [[function]].

So what does the other lines above that mean? There is 
```csharp
using system;

namespace HelloWorld

class Program

static void Main(string[] args)

so what do all of these things mean?
```

**Line 1:** `using System` means that we can use the [[class]] from the `System` namespace.

**Line 2:** A blank line. C# ignores white space. However, multiple lines makes the code more readable.

**Line 3:** `namespace` is used to organize your code, and it is a container for classes and other namespaces.

**Line 4:** The curly braces `{}` marks the beginning and the end of a block of code.

**Line 5:** `class` is a container for data and methods, which brings functionality to your program. Every line of code that runs in C# must be inside a class. In our example, we named the class Program.
**Line 7:** Another thing that always appear in a C# program, is the `Main` method. Any code inside its curly brackets `{}` will be executed. You don't have to understand the keywords before and after Main. You will get to know them bit by bit while reading this tutorial.

**Line 9:** `Console` is a class of the `System` namespace, which has a `WriteLine()` method that is used to output/print text. In our example it will output "Hello World!".

If you omit the `using System` line, you would have to write `System.Console.WriteLine()` to print/output text.


[[using system]]
[[namespace]]
[[class]]
[[Main method]]
[[Method]]


These don't matter that much, but you will have to understand them at some point. However, to write simple code you do not have to. BUT! [[Unity]] requires this to be understood so you can actually code.





