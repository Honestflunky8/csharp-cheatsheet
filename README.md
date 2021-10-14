# CSharp Cheat Sheet Template

Keyword |                  Summary                   | Sample Code | Mentioned In
------- | ------------------------------------------ | ------------ | ------------
`;`     | Used to separate statements from each other.| `int i = 5; i++; Console.WriteLine(i);` | [Script Execution](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#0-script-execution)
`//`    | Used for single-line comments              | `float multiplier = 0.01f; // % to float (e.g. 24% = 0.24)` | [Comments](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#single-line-comments)
Variable Initialization | When a value is assigned to a variable for the first time | `int a = 5;` | [Variables](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#variable-initialization)
`dotnet new console -o project-name` | Creates new project | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.1-hello-world.md
Script Execution Order | Top to bottom | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types
Formatting | ? | ? | ?
`Console.WriteLine` | Print function. Prints whatever you insert into it in a new line. | `Console.WriteLine("Hello World")` | ?
`Console.Write` | Print function. Prints whatever you insert into, on the same line. | `Console.Write("Hello World")` | ?
Multi-Line Comment | Comments out everything within its scope. | `*/ .... */` | ?
XML Documentation Comment | Generates several lines of comments for easy use of commenting. | ? | ?
Variable | ? | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types
Variable Declaration | ? | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types
Variable Assignment | ? | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types
Uninitialized Variable | ? | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types
`=` (Assignment Operator) | ? | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types
Scope | {whatever is inside this} | `if (cat != dog){whatever is inside this happens}` | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types
Variable Scope | ? | ? |https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types
`int` | Number without decimals | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types
`float` | Numbers with decimals | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types
`double` | numbers with decimals, can be bigger. | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types
`bool` | True or false | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types
`char` | Single letter | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types
`string` | Text | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types
`byte` | ? | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types
Implicit Casting | ? | ? | ?
Explicit Casting | ? | ? | ?
Type Conversion | Convert one thing to another, like string to an int if it has numbers. | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types
`Convert.ToInt32` | Easy | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types
Operators | Easy | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types
Arithmetic Operators | ? | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types
`+` | easy | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types
`-` | easy | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types
`*` | easy | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types
`/` | easy | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types
`%` | Modulo, Division and returns what's left. | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types
`+=` | easy | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`-=` | easy | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`++` | easy | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`--` | easy | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
Post-Increment `i++` | i+1 | `if(i=0;i<10;i++) {Console.WriteLine("Hello World")}` | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types
Pre-Increment `++i` | ? | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#4-basic-data-types
`System.Math` | Access math from system | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`static` | In C#, static means something which cannot be instantiated. You cannot create an object of a static class and cannot access static members using an object. | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`Math.Max` | Checks which number is max | `Math.Max(5,10)` | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`Math.Min` | Checks which number is min | `Math.Min(5,10)` | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`Math.Sqrt` | Square root | ? |https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`Math.Abs` | ? | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`Math.Round` | Rounds the number | `Math.Round(1.34)` = 1 | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`Math.Floor` | Checks the floor of the value | `Math.Floor(1.34)` = 1 | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`Math.Ceiling` | Checks the top number of the value | `Math.Floor(1.34)` = 2 | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`Math.Clamp` | Take a number and checks if it is within its scope | `Math.Clamp(5, 0, 3)` = 3 | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`Math.Pow` | Raises number 1 to the power of number 2. 5^2 = 25 | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`string.Length` | The lenght of a string, amount of characters | ? |https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`string.ToUpper` | Forces the string to be UPPERCASE | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`string.+` | A string + something | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`$"{}"` | Interpolated string. You can insert a variable into a string with this. Very Useful! | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`string.[]` | ? | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`string.IndexOf` | ? | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`string.SubString(int)` | ? | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`string.Substring(int, int)` | ? | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`string.Replace` | ? | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
immutable | Cannot be changed | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
Logical Operators | ? | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`!` | Not | `if(a != b)` | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`&&` | And | `if(a == b && b == 5)` | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
Comparison Operators | ? | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`>` | ? | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`==` | Equal to | `if(a==b)` | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`!=` | Not equal to | `if(a!=b)` | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`||` | Or | `if(a == b || a == c)` | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`>=` | More or equal to | `if(a >= b)` | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`<=` | Less or equal to | `if(a <= b)` | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`if` | Easy | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`else` | Easy | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`else if` | Easy | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`? :` | ? | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
Flow Control Statements | ? | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`System.Random` | ? | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
pseudo-random | Random isnt actually random, but appears so. | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
seed | You can input a seed into random and the outcome of random will always follow that seed. | `Random random = new random(33221100)` | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`Random.Next(int, int)` | Generates random number between int1 and int2 | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`Random.Next()` | Generates random number | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`Random.NextDouble()` | Generates random number between 0 and 1 | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.2-console-basics-2.md#8-math
`while` | Easy | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.3-console-basics-3.md#13-while-loops
bool-expression | ? | ? | ?
`do..while` | ? | ? | https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.3-console-basics-3.md#13-while-loops
`for` | ? | ? | ?
iteration statement | ? | ? | ?
loop body | Loop body is the part that happens every loop. | ? | ?
loop | The whole loop, goes around and around and around | ? | ?
execution | Runs specific code. | ? | ?
execution jump | Foregoes normal top to bottom approach of execution and jumps to another point and execute thats first. Example in loops. | ? | ?
`break` | ? | ? | ?
`continue` | ? | ? | ?
`Array` | List of variable | int[] array = int[5] | ?
`int[]` | ? | ? | ?
Array Initialization | ? | ? | ?
Array Access for Assignment | ? | ? | ?
Array Access for Reading | ? | ? | ?
`Array.Resize` | ? | ? | ?
`Array.Length` | ? | ? | ?
`foreach` | ? | ? | ?
`2D-Array` | ? | ? | ?
2D-Array Initialization | ? | ? | ?
2D-Array Access for Assignment | ? | ? | ?
2D-Array Access for Reading | ? | ? | ?
Jagged Arrays | ? | ? | ?
Method | ? | ? | ?
`void` | ? | ? | ?
Return Type | ? | ? | ?
`()` | ? | ? | ?
Parameter | ? | ? | ?
Argument | ? | ? | ?
Parameter | ? | ? | ?
Parameter-List | ? | ? | ?
Named Arguments | ? | ? | ?
Optional Arguments | ? | ? | ?
Default Value | ? | ? | ?
`return` | ? | ? | ?
Code Paths | ? | ? | ?
Method Overloading | ? | ? | ?
Object-Oriented Programming | ? | ? | ?
Data | ? | ? | ?
Function | ? | ? | ?
Structured Programming | ? | ? | ?
Objects | ? | ? | ?
Instance Method | ? | ? | ?
Class | ? | ? | ?
Type | ? | ? | ?
`class` | ? | ? | ?
`new` | ? | ? | ?
Class Member | ? | ? | ?
Class Instance | ? | ? | ?
Garbage Collector | ? | ? | ?
`null` | Nothing | ? | ?
Invoke | ? | ? | ?
Field | ? | ? | ?
Static Class Member | ? | ? | ?
Static Class | ? | ? | ?
Global Access | ? | ? | ?
Constructor | ? | ? | ?
Initial Class Values | ? | ? | ?
Parameterless | ? | ? | ?
Default Contructor | ? | ? | ?
Finalizer | ? | ? | ?
Object Destruction | ? | ? | ?
`GC.Collect` | ? | ? | ?
Encapsulation | ? | ? | ?
Access Modifier | ? | ? | ?
`private` | ? | ? | ?
`protected` | ? | ? | ?
`public` | ? | ? | ?
`internal` | ? | ? | ?
Class Member Access | ? | ? | ?
Inheritance | ? | ? | ?
Property | ? | ? | ?
Getter Method | ? | ? | ?
Setter Method | ? | ? | ?
Validation | ? | ? | ?
Processing | ? | ? | ?
`get` | Part of property. The get part just allows you to get the value. | ? | ?
`set` | part of property. The set part is what usually does the calculation and just set the value. Usually not public  | ? | ?
Expression Body Syntax | ? | ? | ?
Auto Property | ? | ? | ?
Read-Only Property | ? | ? | ?
Auto Property | ? | ? | ?
base-Class | ? | ? | ?
Inherit From | ? | ? | ?
Derived Class | ? | ? | ?
Child Class | ? | ? | ?
Parent Class | ? | ? | ?
`sealed` | ? | ? | ?
Polymorphism | ? | ? | ?
`as` | ? | ? | ?
`virtual` | Allows something to be overwritten | ? | ?
`override` | Changes a copy of something that is virtual and can modify a version of it to your needs. | ? | ?
`base` | Where the inherited information comes from, the parent. It refers to that. | ? | ?
Abstraction | ? | ? | ?
`abstract` | ? | ? | ?
Implementation | ? | ? | ?
Composition | ? | ? | ?
"Composition over Inheritance" | ? | ? | ?
