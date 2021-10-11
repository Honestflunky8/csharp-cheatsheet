# CSharp Cheat Sheet Template

Keyword |                  Summary                   | Sample Code | Mentioned In
------- | ------------------------------------------ | ------------ | ------------
`;`     | Used to separate statements from each other.| `int i = 5; i++; Console.WriteLine(i);` | [Script Execution](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#0-script-execution)
`//`    | Used for single-line comments              | `float multiplier = 0.01f; // % to float (e.g. 24% = 0.24)` | [Comments](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#single-line-comments)
Variable Initialization | When a value is assigned to a variable for the first time | `int a = 5;` | [Variables](https://github.com/marczaku/csharp-basics/blob/main/slides/003.3.1-console-basics-1.md#variable-initialization)
`dotnet new console -o project-name` | Creates new project | ? | ?
Script Execution Order | Top to bottom | ? | ?
Formatting | ? | ? | ?
`Console.WriteLine` | Print function. Prints whatever you insert into it in a new line. | `Console.WriteLine("Hello World")` | ?
`Console.Write` | Print function. Prints whatever you insert into, on the same line. | `Console.Write("Hello World")` | ?
Multi-Line Comment | Comments out everything within its scope. | `*/ .... */` | ?
XML Documentation Comment | ? | ? | ?
Variable | ? | ? | ?
Variable Declaration | ? | ? | ?
Variable Assignment | ? | ? | ?
Uninitialized Variable | ? | ? | ?
`=` (Assignment Operator) | ? | ? | ?
Scope | {whatever is inside this} | `if (cat != dog){whatever is inside this happens}` | ?
Variable Scope | ? | ? | ?
`int` | Number without decimals | ? | ?
`float` | Numbers with decimals | ? | ?
`double` | numbers with decimals, can be bigger. | ? | ?
`bool` | True or false | ? | ?
`char` | Single letter | ? | ?
`string` | Text | ? | ?
`byte` | ? | ? | ?
Implicit Casting | ? | ? | ?
Explicit Casting | ? | ? | ?
Type Conversion | Convert one thing to another, like string to an int if it has numbers. | ? | ?
`Convert.ToInt32` | Easy | ? | ?
Operators | Easy | ? | ?
Arithmetic Operators | ? | ? | ?
`+` | easy | ? | ?
`-` | easy | ? | ?
`*` | easy | ? | ?
`/` | easy | ? | ?
`%` | ? | ? | ?
`+=` | easy | ? | ?
`-=` | easy | ? | ?
`++` | easy | ? | ?
`--` | easy | ? | ?
Post-Increment `i++` | i+1 | `if(i=0;i<10;i++) {Console.WriteLine("Hello World")}` | ?
Pre-Increment `++i` | ? | ? | ?
`System.Math` | Access math from system | ? | ?
`static` | In C#, static means something which cannot be instantiated. You cannot create an object of a static class and cannot access static members using an object. | ? | ?
`Math.Max` | Checks which number is max | `Math.Max(5,10)` | ?
`Math.Min` | Checks which number is min | `Math.Min(5,10)` | ?
`Math.Sqrt` | Square root | ? | ?
`Math.Abs` | ? | ? | ?
`Math.Round` | Rounds the number | `Math.Round(1.34)` = 1 | ?
`Math.Floor` | Checks the floor of the value | `Math.Floor(1.34)` = 1 | ?
`Math.Ceiling` | Checks the top number of the value | `Math.Floor(1.34)` = 2 | ?
`Math.Clamp` | Take a number and checks if it is within its scope | `Math.Clamp(5, 0, 3)` = 3 | ?
`Math.Pow` | Raises number 1 to the power of number 2. 5^2 = 25 | ? | ?
`string.Length` | The lenght of a string, amount of characters | ? | ?
`string.ToUpper` | Forces the string to be UPPERCASE | ? | ?
`string.+` | A string + something | ? | ?
`$"{}"` | Interpolated string. You can insert a variable into a string with this. Very Useful! | ? | ?
`string.[]` | ? | ? | ?
`string.IndexOf` | ? | ? | ?
`string.SubString(int)` | ? | ? | ?
`string.Substring(int, int)` | ? | ? | ?
`string.Replace` | ? | ? | ?
immutable | ? | ? | ?
Logical Operators | ? | ? | ?
`!` | Not | `if(a != b)` | ?
`&&` | And | `if(a == b && b == 5)` | ?
Comparison Operators | ? | ? | ?
`>` | ? | ? | ?
`==` | Equal to | `if(a==b)` | ?
`!=` | Not equal to | `if(a!=b)` | ?
`||` | Or | `if(a == b || a == c)` | ?
`>=` | More or equal to | `if(a >= b)` | ?
`<=` | Less or equal to | `if(a <= b)` | ?
`if` | Easy | ? | ?
`else` | Easy | ? | ?
`else if` | Easy | ? | ?
`? :` | ? | ? | ?
Flow Control Statements | ? | ? | ?
`System.Random` | ? | ? | ?
pseudo-random | Random isnt actually random, but appears so. | ? | ?
seed | You can input a seed into random and the outcome of random will always follow that seed. | `Random random = new random(33221100)` | ?
`Random.Next(int, int)` | Generates random number between int1 and int2 | ? | ?
`Random.Next()` | Generates random number | ? | ?
`Random.NextDouble()` | Generates random number between 0 and 1 | ? | ?
`while` | Easy | ? | ?
bool-expression | ? | ? | ?
`do..while` | ? | ? | ?
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
